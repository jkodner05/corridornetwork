# Modeling Language Change in the St. Louis Corridor
https://ling.auf.net/lingbuzz/004819

Framework described in https://www.aclweb.org/anthology/P18-1106/


## Setup

Just run **setup.sh** or create a plots directory in the parent directory. Nothing to install. 

## Dependencies

Everything was implemented in Python 2.7. Numpy is the only external library required to run things.

## Experiment Files

There is no user interface yet. Files of the form exp_*.py reproduce plots provided in our papers and serve as code examples

- **exp_corridorgeographic.py** Modeling the characteristic two-peak spread of NCS in the St. Louis Corridor and testing Friedman 2014's hypothesis

- **exp_corridor.py** Modeling the characteristic two-peak spread of NCS in the St. Louis Corridor and testing Friedman 2014's hypothesis

## Model Files

These implement the model

- **applyT.py** Apply T learner transition matrix

- **calcP.py** Calculate P learner input matrix matrix

- **calcTfromextensions.py** Automatically create T matrix from grammar extensions

- **generateA.py** Generate A adjacency matrix

- **updateB.py** Update B grammar expression matrix

