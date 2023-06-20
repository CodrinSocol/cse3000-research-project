# Identifying non-monotonicity in Empirical Learning Curves through anchor-point slope approximation

This repository contains all the code to run experiments and generate plots for the *Non-Monotonicity in Empirical Learning Curves - Identifying non-monotonicity through anchor-point slope approximation* research project. This paper has been produced as part of the CSE3000 - Research Project course at Delft University of Technology, The Netherlands.

**Author:** Codrin Socol *(C.Socol@student.tudelft.nl)*

### 1. Install dependencies
To install dependencies, run the following commands. Python 3.9, Anaconda as well as Pip are required to run the experiments. 

**Note:** You need to be in the root of the repository as cd to run the commands.
```bash
conda env create env_monotone.yaml
conda activate monotone 
pip install lcdb
pip install func-timeout
```


### 2. Running the Experiments
To run the experiments, first activate the Anaconda environment with `conda activate monotone`. Then in a conda terminal, open Jupyter Notebook with `jupyter notebook`. Simply run the cells in the notebook to get the experimental results.

**Note:** Running the experiments requires one data archive `df_total.gz` from the LCDB repository *(https://github.com/fmohr/lcdb)*. Currently, this file is not publicly available, but authors may publish it in the future. If you want to run the experiments, please contact the authors of the LCDB paper and request access to the archive.