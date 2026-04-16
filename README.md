# scRNA-seq Analysis of PBMC 3k Dataset

## Overview
Performed end-to-end single-cell RNA-seq analysis using Seurat on the 10X Genomics PBMC 3k dataset.

## Workflow
- Quality control filtering (mitochondrial %, gene counts)
- Normalization and variable feature selection
- PCA and UMAP dimensionality reduction
- Graph-based clustering (resolution = 0.5)
- Marker gene identification using FindAllMarkers
- Manual cell type annotation (9 immune populations)
- Differential expression analysis

## Key Results
- ~2600 cells retained after QC filtering
- 9 distinct immune cell populations identified
- Clear separation observed in UMAP embedding

## Tools
R, Seurat, ggplot2, tidyverse, R Markdown

## Data Source
10X Genomics PBMC 3k dataset