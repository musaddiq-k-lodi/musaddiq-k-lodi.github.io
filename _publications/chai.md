---
title: "CHAI: consensus clustering through similarity matrix integration for cell-type identification "
collection: publications
category: manuscripts
permalink: /publication/chai
excerpt: 'Consensus clustering algorithm for scRNAseq cell-type identification'
date: 2024-8-29
venue: 'Briefings in Bioinformatics'
citation: 'Lodi MK, Lodi M, Osei K, Ranganathan V, Hwang P, Ghosh P. CHAI: Consensus Clustering Through Similarity Matrix Integration for Cell-Type Identification. Brief Bioinform. 2024;25(5):bbae411. doi:10.1093/bib/bbae411.'
---
Several methods have been developed to computationally predict cell-types for single cell RNA sequencing (scRNAseq) data. As methods are developed, a common problem for investigators has been identifying the best method they should apply to their specific use-case. To address this challenge, we present CHAI (consensus Clustering tHrough similArIty matrix integratIon for single cell-type identification), a wisdom of crowds approach for scRNAseq clustering. CHAI presents two competing methods which aggregate the clustering results from seven state-of-the-art clustering methods: CHAI-AvgSim and CHAI-SNF. CHAI-AvgSim and CHAI-SNF demonstrate superior performance across several benchmarking datasets. Furthermore, both CHAI methods outperform the most recent consensus clustering method, SAME-clustering. We demonstrate CHAI’s practical use case by identifying a leader tumor cell cluster enriched with CDH3. CHAI provides a platform for multiomic integration, and we demonstrate CHAI-SNF to have improved performance when including spatial transcriptomics data. CHAI overcomes previous limitations by incorporating the most recent and top performing scRNAseq clustering algorithms into the aggregation framework. It is also an intuitive and easily customizable R package where users may add their own clustering methods to the pipeline, or down-select just the ones they want to use for the clustering aggregation. This ensures that as more advanced clustering algorithms are developed, CHAI will remain useful to the community as a generalized framework. CHAI is available as an open source R package on GitHub: https://github.com/lodimk2/chai.
