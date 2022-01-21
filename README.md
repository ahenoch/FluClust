# Influenza

## Preparations

- conda config --add channels bioconda
- conda config --add channels conda-forge
- conda create -n clustering jupyterlab jupyter-resource-usage jupyterlab-git jupyterlab-fasta pandas numpy scipy biopython umap-learn hdbscan scikit-learn nodejs tqdm raxml mafft r-base r-irkernel r-tidyverse r-plotly r-ggstar bioconductor-ggtree bioconductor-ggtreeextra
- conda activate clustering
- jupyter lab

## Pipeline

Nearly fully automated as of 2022/01/19 in two Juyter Notebooks.

1. Python: FASTA + Settings -> CSV tables
2. R: CSV tables + Settings -> Grafics
