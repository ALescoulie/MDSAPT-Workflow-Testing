# MDSAPT-Workflow-Testing
Series of Jupyter Notebooks testing workflows for [MDSAPT](https://github.com/alescoulie/MDSAPT)

## Replicating Environment

These are the steps to set up the environment used to run. This process uses git and anaconda to set up the MDSAPT environment.

1. Clone this repository
``` bash
git clone https://github.com/ALescoulie/MDSAPT-Workflow-Testing.git
```

2. Enter the repository directory
```bash
cd MDSAPT-Workflow-Testing
```

3. Use git submodule to add MDSAPT to the directory
```bash
git submodule https://github.com/ALescoulie/MDSAPT.git
```

4. Enter the MDSAPT directory and create a new conda environment with the correct dependencies
```bash
cd MDSAPT
conda env create --name mdsapt --file mdsapt_env.yaml python=3.8
```
