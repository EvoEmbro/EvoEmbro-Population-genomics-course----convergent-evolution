# Exploring the selfing syndrome related genes in the Capsella genus using RNA-seq data

A 2-weeks project with Zebin Zhang \
Plant Ecology and Evolution \
Evolutionary Biology Centre (EBC) \
Uppsala University

## Introduction
Convergent evolution occurs when the same biological function or similar phenotypes between species evolve independently more than once. For instance, the evolution of wings in birds and bats is an example of convergent evolution. Another excellent example of convergent evolution is the mating system transition from outcrossing to selfing in flowering plants, as the transition to selfing often evolved similar phenotypic changes such as reduced flower size, decreased production of pollen, nectar and scent. Therse changes have been named the “selfing syndrome”.
Outcrossing is a prevalent reproduction mode in plants and animals, while selfing mating occurs at a much lower frequency; however, it is still far from negligible. Across all plant species, approximately 11% of species are solely selfing, and 24% of species have a mixed mating system. On the one hand, selfing species are chatarcterized by intrinsic inbreeding depression, higher deleterious mutation loads, lower selection efficacy and  lower adaptive capacity. On the other hand, being a selfer also means reproductive assurance, especially when mates and/or pollinators are scarce. Hence it is not hard to imagine why the transition from outcrossing to selfing is one of the most common evolutionary processes in flowering plants, particularly when the transition advantage of selfing outweighs the cost of inbreeding depression.

## Project Aims
1.	Gain a better understanding of convergent evolution
2.	Get familiar with essential steps of bulk RNA-seq analysis (requiring basic knowledge of the R programming language)
3.	Identify how many and which genes are related to the selfing syndrome
4.	Write a research report

## Subjects and methods

The Capsella genus comprises three diploid species and one tetraploid, C. bursa-pastoris. Among the three diploid species one is outcrossing, C. grandiflora, and two are self-fertilizing, C. orientalis and C. rubella. C. orientalis derived from the ancestor of C. grandiflora some 1M years ago while C. rubella derived from C. grandiflora recently, around 50,000 years ago. The outcrossing species C. grandiflora has large flowers and long flowering times, while the other two selfing species both have drastically smaller flower sizes and relatively shorter flowering times, and without significant differences between the two selfers.
We  will take advantage of the double mating system transition in Capsella and use already available gene expression data of these three species in flowers, leaves and roots, to explore the genetic basis of convergent evolution and identify selfing syndrome related genes.
The primary analysis steps include:
1.	Normalize gene expression data across species.
2.	Perform PCA to explore the main variance in gene expression.
3.	Using EdgeR (R package) to explore differentially expressed genes between species
4.	Analysis genes under convergent evolution in terms of mating system transition
5.	Identifying genes related to the selfing syndrome
6.	Gene Ontology (GO) analysis on identified selfing syndrome genes to verify functions.
