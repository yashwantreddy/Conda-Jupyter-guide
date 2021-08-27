# Conda-Jupyter-guide

## First create a conda virtual environment
_conda create --name your_env_name_here python=3.8_

## Next activate your environment
_conda activate your_env_name_here_

## Next install Jupyter and ipykernel
_conda install notebook_ <br>
_conda install ipykernel_


## Add a new Jupyter kernel so that you can summon it and use the libraries accordingly
_ipython kernel install --user --name=your_env_name-kernel_

## Launch Jupyter and we are good!
_jupyter notebook_
