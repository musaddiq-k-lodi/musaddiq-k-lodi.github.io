---
title: "COFFEE: Consensus Single Cell-Type Specific Inference for Gene Regulatory Networks"
collection: publications
category: conferences
permalink: /publication/ijms
excerpt: 'Python software for wisdom of crowds marker gene inference on scRNAseq data.'
date: 2024-09-23
venue: Briefings in Bioinformatics
paperurl: ''
citation: 'Lodi MK, Chernikov A, Ghosh P. COFFEE: Consensus Single Cell-Type Specific Inference for Gene Regulatory Networks. Brief Bioinform. 2024;25(6):bbae457. doi:10.1093/bib/bbae457.'
---

The inference of gene regulatory networks (GRNs) is crucial to understanding the regulatory mechanisms that govern biological processes. GRNs may be represented as edges in a graph, and hence, it have been inferred computationally for scRNA-seq data. A wisdom of crowds approach to integrate edges from several GRNs to create one composite GRN has demonstrated improved performance when compared with individual algorithm implementations on bulk RNA-seq and microarray data. In an effort to extend this approach to scRNA-seq data, we present COFFEE (COnsensus single cell-type speciFic inFerence for gEnE regulatory networks), a Borda voting-based consensus algorithm that integrates information from 10 established GRN inference methods. We conclude that COFFEE has improved performance across synthetic, curated, and experimental datasets when compared with baseline methods. Additionally, we show that a modified version of COFFEE can be leveraged to improve performance on newer cell-type specific GRN inference methods. Overall, our results demonstrate that consensus-based methods with pertinent modifications continue to be valuable for GRN inference at the single cell level. While COFFEE is benchmarked on 10 algorithms, it is a flexible strategy that can incorporate any set of GRN inference algorithms according to user preference. A Python implementation of COFFEE may be found on GitHub: https://github.com/lodimk2/coffee
