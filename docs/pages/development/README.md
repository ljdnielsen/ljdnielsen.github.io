---
layout: default
---

<div id="header" style="text-align: center;">
  <img src="{{ site.baseurl }}/docs/images/header.development.png" alt="Centered Image" style="margin-top: 20px;">
</div>

## Measuring Gene Expression Changes Along the Internal Branches of Species Trees

In a paper by scientists at the University of Lausanne and the Swiss Institute of Bioinformatics, [published in 2011 in the prominent journal Nature](https://doi.org/10.1038/nature10532), Brawand and colleagues investigated the transcription rate changes along branches of species trees build from contemporary samples of RNA-seq reads from nine mammalian species.

To initially improve the annotation of genes from the RNA-seq reads, sampled from various tissues, the authors mapped the reads against the corresponding species' reference genomes. Because introns are separated from exons during normal pre-mRNA processing the reads mapped only to exons, revealing gene splice sites. This allowed the identification of alternative splice sites, appearing as introns surrounded by low or intermediately expressed exons allowing for a more accurate description of the expressed genes.

The researchers then identified orthologous genes of the nine species, or subsets thereof, and created species trees based on expression profiles. The total branch length of these trees varied among tissues, with testis showing the highest level of expression divergence among species. They also found that there is a limit to the accumulation of expression divergence. For example, humans are as different in their expression levels from marsupials as they are from chickens, despite having diverged 110 million years earlier from chickens than from marsupials.

To identify chromosomes having undergone significant expression changes in the past, the authors compared the lenghts of equivalent branches between expression trees from different chromosomes. Here they found a disproportionate change in expression of genes on the X chromosome compared to those of autosomes on the branch leading from the common ancestor of all mammals, including monotremes (such as the platypus), to the common ancestor of all therian mammals (marsupials and eutherians). This branch represents an alternative route from the branch leading to the egg-laying monotremes, that involved a dramatic change in the number of sex chromosomes towards the therian branch of mammals that birth live young. Monotreme males have five X chromosomes, whereas therians have one. The observed expression change in X-linked genes on the branch leading to therians likely reflects the associated loss of gene dosage from.[^1]

[^1]: Brawand, D., Soumillon, M., Necsulea, A. *et al.* [The Evolution of Gene Expression Levels in Mammalian Organs](https://doi.org/10.1038/nature10532). *Nature* 478, 343-348 (2011). https://doi.org/10.1038/nature10532









