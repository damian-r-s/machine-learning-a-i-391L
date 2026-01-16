# Python 3.8 Machine Learning Environment

This project uses a Conda environment with Python 3.8 and common machine learning libraries.

## Prerequisites
- Anaconda or Miniconda

## Create the environment
```bash
conda create -n machinelearning_ai391l python=3.8
conda activate machinelearning_ai391l

conda install -c conda-forge jupyter scikit-learn pandas matplotlib seaborn

python -m ipykernel install --user --name machinelearning_ai391l --display-name "Python 3.8 (machinelearning_ai391l)"

jupyter notebook

jupyter lab

import sys
import sklearn
import pandas
import matplotlib

print(sys.version)
print("sklearn:", sklearn.__version__)
print("pandas:", pandas.__version__)
print("matplotlib:", matplotlib.__version__)

conda env export > machinelearning_ai391l.yml


I can also make a **shorter, GitHub-style “quick start” version** if you want your README to be compact. Do you want me to do that?