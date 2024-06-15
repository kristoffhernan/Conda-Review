# check if env is already made
conda env list

# if not, create it
# this creates a new env
conda create --name newenv

# activate 
conda activate newenv

# install jupyter (this takes a while)
conda install jupyter

# create environment from yaml file
conda env create -f env.yml

# activate new env
conda activate newenv

# start jupyter
jupyter notebook

