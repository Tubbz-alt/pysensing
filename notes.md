# Quickstarter Python Notebooks


## Todo
1. Look into nbgrader
2. Look into nbdime
3. Look into pytest
4. Look into flake8
5. Set up environment.yml


## Running Notes

### Conda environment


#### Creating conda environments:
1. created environment.yml file
2. conda env create -f environment.yml

Note: To update the environment:

'''
source deactivate;
conda env update -f whatever.yml;
source activate my_environment_name; # Must be AFTER the conda env update line!
'''
