# Influenza

## Preparations

- conda create -n clustering
- conda activate clustering
- conda install -c conda-forge jupyterlab jupyter-resource-usage jupyterlab-git jupyterlab-fasta r-base=4.1.2 pandas numpy scipy biopython umap-learn hdbscan scikit-learn nodejs
- conda install -c bioconda raxml mafft
- R
- install.packages('IRkernel')
- install.packages('tidyverse')
- install.packages('BiocManager')
- BiocManager::install('ggtree')
- BiocManager::install('ggtreeExtra')
- jupyter labextension install @techrah/text-shortcuts

## Pipeline

Nearly fully automated as of 2022/01/19 in two Juyter Notebooks.

1. Python: FASTA + Settings -> CSV tables
2. R: CSV tables + Settings -> Grafics