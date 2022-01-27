# Influenza

## Environment recreation

- conda env create -f clustering.yml
- conda activate clustering
- jupyter lab

## Pipeline execution

Nearly fully automated as of 2022/01/19 in two Juyter Notebooks.

1. Clusterer.ipynb (Python): FASTA + Settings -> CSV tables
2. Graphics.ipynb (R):  CSV tables + Settings -> Grafics
