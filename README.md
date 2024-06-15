# check if env is already made
conda env list

# if not, create it
# this creates a new env
conda create --name newenv

# activate 
conda activate newenv

# install jupyter notebook (this takes a while)
conda install jupyter
# or install jupyter lab
conda install -c conda-forge jupyterlab

# create environment from yaml file
conda env create -f env.yml

# activate new env
conda activate newenv

# start jupyter
jupyter notebook


List all environments: conda env list
Remove an environment: conda env remove --name myenv
Install a package: conda install packagename
Update a package: conda update packagename
Remove a package: conda remove packagename
List installed packages: conda list
Install a specific Python version: conda create --name myenv python=3.8
Update Python version in an environment: conda install python=3.8
Export environment to a YAML file: conda env export > environment.yml
Create an environment from a YAML file: conda env create -f environment.yml
