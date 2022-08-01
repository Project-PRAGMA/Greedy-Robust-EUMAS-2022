# Robustness of Greedy Approval Rules

This repository contains source code used to run experiments in the paper "Robustness of Greedy Approval Rules" by Piotr Faliszewski, Grzegorz Gawron, and Bartosz Kusek

# Setup

## Initialise

- `conda env update -f environment.yml`
- `python -m ipykernel install --user --name esearch --display-name "Python (esearch)"`
   (you may have to install `pyarrow` with pip)
- `conda install dask distributed -c conda-forge` to install dask distributed
- `conda activate esearch`

## Run experiments
- `python counting_rradius_raw.py`
  Results will be stored in: `out/manual/counting_rradius_raw/generated/`
  
