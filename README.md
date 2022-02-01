# Influenza

## Environment recreation

### Automatic Install
- conda env create -f clustering.yml
- conda activate clustering
- jupyter lab

### Manual Install
- mamba create -n clustering2 jupyterlab jupyter-resource-usage jupyterlab-git jupyterlab-fasta jupyterlab-lsp pandas numpy scipy biopython umap-learn hdbscan scikit-learn nodejs tqdm kneed plotly rpy2 python-lsp-server r-languageserver raxml mafft r-base r-irkernel r-tidyverse r-plotly r-ggstar bioconductor-ggtree bioconductor-ggtreeextra r-phangorn bioconductor-tanggle
- conda activate clustering
- jupyter lab

## Pipeline execution

Nearly fully automated as of 2022/01/19 in two Juyter Notebooks.

1. Clusterer.ipynb (Python): FASTA + Settings -> CSV tables
2. Graphics.ipynb (R):  CSV tables + Settings -> Grafics
