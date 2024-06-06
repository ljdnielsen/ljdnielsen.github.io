---
layout: default
---

<div id="header" style="text-align: center;">
  <img src="{{ site.baseurl }}/docs/images/header.development.png" alt="Centered Image" style="margin-top: 20px;">
</div>

## Binding Affinity of Transcription Factor Binding Sites Determines Digitnumber of Mice in a Linear Fashion

The Shh gene is responsible for digit development through its expression in the Zone of Polarizing Activity region, in the developing limb bud, during embryonic development in mice and humans. It is controlled by an enhancer region called ZPA Regulatory Sequence (ZRS) which has multiple transcription factor binding sites. One of these transcription factor binding sites, ETS-A, is associated with known SNVs causing polydactyly (having more than five fingers) in humans.

In a research paper published January 2024 in the prominent journal Nature, Emma Farley and colleagues measured the binding affinity of the ETS-1 to the binding sites of ZRS. They found that the pathogenic mutations causing polydactyly increase the binding affinity of ETS-1 to the binding site ETS-A. They then created alternative ETS-A mutant variants, different from the known SNVs causing polydactyly, but with the same increased binding affinity, and showed that they resulted in the same phenotypic change, establishing that it is the increased binding affinity of the ETS-A site that casuses the change in phenotype associated with the known mutations.

To establish that the change in phenotype stems from an increased expression of shh in the affected tissues, the authors measured gene expression of affinity-enhanced mutants in cell-lines of limb cells. This was difficult to show suggesting that increased binding affinity might only have caused a slight increase in expression, that none-the-less was sufficient to drive the increased number of digits.

The authors then went on to show that of all the SNVs known to cause phenotypic changes in humans, the majority are mutations that increase binding affinity of transcription factors to enhancers.[^1]

## Measuring Gene Expression Changes Along the Internal Branches of Species Trees

In a paper by scientists at the University of Lausanne and the Swiss Institute of Bioinformatics, [published in 2011 in the prominent journal Nature](https://doi.org/10.1038/nature10532), Brawand and colleagues investigated the transcription rate changes along branches of species trees build from contemporary samples of RNA-seq reads from nine mammalian species.

To initially improve the annotation of genes, the RNA-seq reads were mapped against the corresponding species' reference genomes. Because introns are separated from exons during normal pre-mRNA processing the reads mapped only to exons, revealing gene splice sites. This allowed for the identification of alternative splice sites, appearing as introns surrounded by low or intermediately expressed exons, letting the authors make a more accurate description of the expressed genes.

The researchers then identified orthologous genes of the nine species and created species trees based on expression profiles. The total branch length of these trees varied among tissues, with testis showing the highest level of expression divergence among species. They also found that there is a limit to the accumulation of expression divergence. For example, humans are as different in their expression levels from marsupials as they are from chickens, despite having diverged 110 million years earlier from chickens than from marsupials.

To identify chromosomes having undergone significant expression changes in the past, the authors compared the lenghts of equivalent branches between expression trees for different chromosomes. Here they found a disproportionate change in expression of genes on the X chromosome compared to those of autosomes on the branch leading from the common ancestor of all mammals, including monotremes (such as the platypus), to the common ancestor of all therian mammals (marsupials and eutherians). This branch represents an alternative route from the branch leading to the egg-laying monotremes that involved a dramatic change in the number of sex chromosomes towards the therian branch of mammals that birth live young. Monotreme males have five X chromosomes, whereas therians have one. The observed expression change in X-linked genes on the branch leading to therians likely reflects the associated loss of gene dosage.[^2]

[^1]: Lim, F., Solvason, J.J., Ryan, G.E. *et al.* [Affinity-optimizing enhancer variants disrupt development](https://doi.org/10.1038/s41586-023-06922-8). *Nature* __626__, 151–159 (2024). https://doi.org/10.1038/s41586-023-06922-8
[^2]: Brawand, D., Soumillon, M., Necsulea, A. *et al.* [The Evolution of Gene Expression Levels in Mammalian Organs](https://doi.org/10.1038/nature10532). *Nature* __478__, 343-348 (2011). https://doi.org/10.1038/nature10532









