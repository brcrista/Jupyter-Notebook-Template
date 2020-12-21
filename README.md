# <NAME>

## Prerequisites

* Miniconda with Python 3.7 or later

## First-time setup

Create the conda environment on your system:

```bash
conda env create -f environment.yml
```

After doing this once, activate the environment with:

```bash
conda environment-name
```

(**Note:** conda environments don't work in PowerShell.)

## Running the notebook

```bash
cd src/
jupyter lab analysis.ipynb
```