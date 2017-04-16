---
title: bcgTree
github: https://github.com/molbiodiv/bcgTree
logo: https://github.com/molbiodiv/bcgTree/raw/master/doc/bcgTree.png
permalink: /en/projects/bcgTree
lang: en
ref: bcgtree
---

A tool to automatically infer bacterial phylogeny from a set of core genes.

Building phylogenetic trees for bacteria is often done by using the standard 16S rDNA marker only.
Big amounts of genomic DNA data are available for bacteria that can be utilised to build more robust trees.
However selection of suitable gene sets for the taxonomic groups of interest is a challenge.
Therefore `bcgTree` uses a pre-defined list of 107 essential single-copy core genes.
It extracts those genes from all provided proteomes automatically and performs the subsequent alignment, preparation and tree building steps.

![Workflow](/images/bcgTree_workflow.svg)

See the repository on [GitHub]({{page.github}}).
An article describing `bcgTree` is published in [Genome](https://www.nrcresearchpress.com/doi/abs/10.1139/gen-2015-0175).

