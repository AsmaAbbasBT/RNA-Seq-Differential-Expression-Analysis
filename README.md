# RNA-Seq-Differential-Expression-Analysis
Title

RNA-Seq Based Differential Gene Expression and Functional Enrichment Analysis Using GEO Dataset

Overview

This project demonstrates a complete RNA-Seq analysis workflow starting from raw count data to differential expression, visualisation, and functional enrichment. I created this repository to show my understanding of transcriptomics, statistical testing, and pathway-level interpretation.

Background

RNA-Seq allows us to quantify gene expression across conditions and identify genes involved in disease mechanisms. I built this workflow while analysing cancer-related datasets during my internship at Genomac Institute. It helped me strengthen my skills in R, Python, DESeq2, GEOquery, and downstream enrichment tools.

Objectives

-Retrieve RNA-Seq data from GEO

-Perform differential expression using DESeq2

-Generate key plots: PCA, volcano plot, heatmap

-Identify significantly upregulated/downregulated genes

-Conduct GO and KEGG enrichment

-Interpret biological meaning

Methods

-Dataset retrieved using GEOquery

-Pre-processing: filtering, normalisation

-DESeq2 for differential analysis

-Visualisations with ggplot2 and pheatmap

-ClusterProfiler for enrichment

-Interpretation of pathways relevant to disease phenotype

Results 

-Identified ~400 significant DEGs (padj < 0.05)

-Upregulated genes linked to metabolic reprogramming

-Downregulated genes associated with immune suppression

-Pathways enriched: PI3K-Akt signalling, apoptosis, cytokine-mediated processes

Tools & Skills Demonstrated


-R (DESeq2, ClusterProfiler, tidyverse)

-Python (pandas, seaborn)

-Statistical modelling

-Biological interpretation

-Data visualisation

-Bioinformatics workflow design

How to Run

Open the .ipynb notebook in Google Colab or Jupyter Notebook and install packages as required.
