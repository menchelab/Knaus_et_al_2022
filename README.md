# Knaus_et_al_2022
[![DOI](https://zenodo.org/badge/568744384.svg)](https://zenodo.org/badge/latestdoi/568744384)

This repository contains information and code about the analysis of metabolomics, lipidomics and proteomics for Knaus et al. Large neutral amino acid levels tune perinatal neuronal excitability and survival

# Install kernel
To reproduce the results you first have to install the conda environment using the following command
```bash
conda env create --file environment.yml
```

If you do not have conda installed yet see [here](https://docs.conda.io/en/latest/miniconda.html) on how to do this. Once you have created the environment you need to activate it and install the ipykernel for jupyter to find it using
```bash
python -m ipykernel install --user --name nova --display-name nova
```

After this you can simply type
```bash
jupyter lab
```

and inspect and run all the python notebooks in the `notebooks` directory.
