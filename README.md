# IL-1α / IL-1R microbiota analysis

This repository contains the scripts used for processing and downstream analysis of 16S rRNA gene sequencing data from cecal samples of WT, Il1a-/- and Il1r-/- mice.

## Overview
The analysis was performed using the DADA2 pipeline for sequence processing, followed by downstream microbiota analyses in R using the phyloseq framework and additional R packages. 
Diversity analyses were conducted on rarefied data, and differential abundance testing was performed using ANCOM-BC.

## Requirements
- R (≥ 4.2.0)
- R packages:
  - phyloseq
  - dada2
  - ANCOMBC
  - ggplot2
  - tidyverse
  - pairwiseAdonis
  - Vegan

## Usage
Scripts were run in the order indicated by their filenames. Input data paths may need to be adjusted according to the local file structure.

## Data availability


## Citation
If you use this code, please cite the associated manuscript.
