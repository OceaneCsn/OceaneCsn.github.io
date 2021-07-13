---
abstract: Statistical inference of a gene regulatory network in Arabidopsis under the combination of climate change and nutritional starvations
all_day: true
authors: [Océane Cassan]
date: "2021-07-06"
event: JOBIM 2021
event_url: https://jobim2021.sciencesconf.org/
featured: true
image:
  caption: 'Image credit: [**JOBIM**](https://jobim2021.sciencesconf.org/)'
  focal_point: Right
math: true
summary: Presentation of the Dashboard for the Inference and Analysis of Networks from Expression data (DIANE)
tags: []
title: Poster - JOBIM
url_slides: files/poster_JOBIM.pdf
---

High-throughput transcriptomic datasets are often examined to discover new actors and regulators of a biological response. To this end, graphical interfaces have been developed and allow a broad range of users to conduct standard analyses from RNA-seq data, even with little programming experience. Although existing solutions usually provide adequate procedures for normalization, exploration or differential expression, more advanced features, such as gene clustering or regulatory network inference, often miss or do not reflect current state of the art methodologies. We developed a user interface called DIANE, designed to harness the potential of multi-factorial expression datasets from any organisms through a precise set of methods.
DIANE interactive workflow provides normalization, dimensionality reduction, differential expression and ontology enrichment. Gene clustering can be performed and explored via configurable Mixture Models, and Random Forests are used to infer gene regulatory networks. DIANE also includes a novel procedure to assess the statistical significance of regulator-target influence measures based on permutations for Random Forest importance metrics.  All along the pipeline, session reports and results can be downloaded to ensure clear and reproducible analyses.

We demonstrate the benefits of DIANE using a recently published dataset describing the transcriptional response of Arabidopsis thaliana under the combination of temperature, drought and salinity perturbations. We show that DIANE can intuitively carry out informative exploration and statistical procedures with RNA-Seq data, perform model based gene expression profiles clustering and go further into gene network reconstruction, providing relevant candidate genes or signalling pathways to explore. Our novel approach to sparsify the output of Random Forests regulatory weights is benchmarked against two databases of known regulatory interactions in A. thaliana and E. coli, and shows more precise predictions as compared to a naive hard-thresholding of Random Forests importance metrics. DIANE is available as a web service (https://diane.bpmp.inrae.fr), or can be installed and locally launched as a complete R package. For this jobim poster session, we propose a live demonstration of the tool, by conducting a standard analysis of the package's companion dataset.
