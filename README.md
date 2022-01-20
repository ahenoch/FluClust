# Influenza

## Preparations

- conda config --add channels bioconda
- conda config --add channels conda-forge
- conda create -n clustering jupyterlab jupyter-resource-usage jupyterlab-git jupyterlab-fasta r-base=4.1.2 pandas numpy scipy biopython umap-learn hdbscan scikit-learn nodejs raxml mafft
- conda activate clustering
- R
- install.packages('IRkernel')
- IRkernel::installspec()
- q()
- jupyter labextension install @techrah/text-shortcuts
- R
- install.packages('tidyverse')
- install.packages('BiocManager')
- BiocManager::install('ggtree')
- BiocManager::install('ggtreeExtra')
- install.packages('plotly')
- install.packages('viridis')
- q()

## Pipeline

Nearly fully automated as of 2022/01/19 in two Juyter Notebooks.

1. Python: FASTA + Settings -> CSV tables
2. R: CSV tables + Settings -> Grafics
