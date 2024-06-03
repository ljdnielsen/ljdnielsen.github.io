---
layout: default
---

<div id="header" style="text-align: center;">
  <img src="{{ site.baseurl }}/docs/images/header.development.png" alt="Centered Image" style="margin-top: 50px;">
</div>

## Measuring Gene Expression Changes Along the Internal Branches of Species Trees

In a paper by scientists at the University of Lausanne and the Swiss Institute of Bioinformatics, [published in 2011 in the prominent journal Nature](https://doi.org/10.1038/nature10532), Brawand and colleagues investigated the transcription rate changes along branches of species trees build from contemporary samples of RNA-seq reads from nine mammalian species.

The RNA-seq reads, sampled from various tissues, were pooled and mapped against the corresponding species' reference genomes to refine existing annotations. During normal pre-mRNA processing, introns are separated from exons, so the reads mapped only to exons, revealing gene splice sites. This allowed the identification of alternative splice sites, appearing as introns surrounded by low or intermediately expressed exons.

The researchers then identified orthologous genes of the nine species, or subsets thereof, and created species trees based on expression profiles. The total branch length of these trees varied among tissues, with testis showing the highest level of expression divergence among species. They found that there is a limit to the accumulation of expression divergence. For example, humans are as different in their expression levels from marsupials as they are from chickens, despite having diverged 110 million years earlier from chickens than from marsupials.

To identify chromosomes undergoing significant expression changes compared to others, the authors compared the branch lengths of different expression trees and found a disproportionate change in expression of X-linked genes compared to those of autosomes on the branch leading from the common ancestor of all mammals, including egg-laying monotremes (such as the platypus), to the common ancestor of all therian mammals (marsupials and eutherians). Monotreme males have five X chromosomes, whereas therians have one. The observed expression change likely reflects the loss of gene dosage due to the reduction in the number of X chromosomes.[^1]

[^1]: Brawand, D., Soumillon, M., Necsulea, A. *et al.* [The Evolution of Gene Expression Levels in Mammalian Organs](https://doi.org/10.1038/nature10532). *Nature* 478, 343-348 (2011). https://doi.org/10.1038/nature10532









