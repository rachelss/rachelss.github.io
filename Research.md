---
layout: page
title: Research
---

## Phylogenetically informative data from next-generation sequencing

We have long expected that complete genomic information will provide us with the tools to determine relationships among organisms, from strains of pathogens to the whole tree of life. However, while whole genome sequencing is now possible, extracting information from these data remains challenging. I have developed software ([SISRS](https://github.com/rachelss/SISRS)) that uses a "composite genome" to identify phylogenetically informative sites.

We are currently improving this software in three ways:
(1) We are developing a new "genome assembler" to identify conserved regions of the genome from multiple taxa, regardless of the location of these regions in the genome.
(2) We are developing new statistical models to call genotypes from multi-species datasets with sequencing error.
(3) We will automate the identification of phylogenetic markers for different clades to reduce the impact of noisy data when constructing large phylogenies and resolve previously undetermined evolutionary relationships.

This research is funded by NSF grant [DBI-1356548](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1356548&HistoricalAwards=false) (ABI Innovation) to R. Cartwright.

[Schwartz, R.S., K.M Harkins, A.C. Stone, and R.A. Cartwright. 2015. A composite genome approach to identify phylogenetically informative data from next-generation sequencing. BMC Bioinformatics. 16:193.](http://www.biomedcentral.com/1471-2105/16/193)

[Talk from Evolution 2014 describing SISRS and its application](https://www.youtube.com/watch?v=0OMPuWc-J2E&list=UUq2cZF2DnfvIUVg4tyRH5Ng)

---------------------------------------

## Evolution of infectious disease

[Winter, D.J., M. Andreina Pacheco, A.F. Vallejo, **R.S. Schwartz**, M. Arevalo-Herrera, S. Herrera, R.A. Cartwright, and A.A. Escalante. Whole genome sequencing of field isolates reveals extensive genetic diversity in Plasmodium vivax from Colombia.](http://biorxiv.org/content/early/2015/08/23/025338)

[Harkins, K.M., **Schwartz, R.S.**, A.C. Stone, and R.A. Cartwright. Phylogenomic reconstruction supports supercontinent origins for Leishmania.](http://biorxiv.org/content/early/2015/10/13/028969)

---------------------------------------

## Diagnostic loci from next-generation sequencing

Distinguishing among potential causes of infectious disease is important for pathogens that are morphologically indistinguishable but must be treated differently. We will use the phylogenetically informative data produced by SISRS (see above) to identify diagnostic sites / combinations of sites for each species. We can then identify the adjacent sequence in the genome, and determine whether this sequence is a cut site for a restriction enzyme. The output data can be used in a lab to amplify the locus and diagnose a species based on whether the DNA is cut using that enzyme.

---------------------------------------

## Biogeography of marmots (Marmota flaviventris) in the Great Basin

[R Shiny Map of Survey Sites](https://rachelss.shinyapps.io/marmot_map_app)
