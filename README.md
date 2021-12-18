# MDSAPT-Workflow-Testing
Series of Jupyter Notebooks testing workflows for [MDSAPT](https://github.com/alescoulie/MDSAPT)

## Replicating Environment

These are the steps to set up the environment used to run. This process uses git and anaconda to set up the MDSAPT environment.

1. Clone this repository and MDSAPT as a submodule
``` bash
git clone --recurse-submodules https://github.com/ALescoulie/MDSAPT-Workflow-Testing.git
```

2. Enter the MDSAPT directory and create a new conda environment with the correct dependencies
```bash
cd MDSAPT-Workflow-Testing/MDSAPT
conda env create --name mdsapt --file mdsapt_env.yaml python=3.8
```
