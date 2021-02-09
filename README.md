# Welcome to COMP-137!
The COMP 137 course staff for Spring, 2021 is going to release all the homework assignments in this repository. You can clone this repository using the command:
 `git clone https://github.com/kap-devkota/Comp137-assignments.git`

# Code Setup

## CONDA setup

We are using `conda` to manage the packages and dependencies in our assignments. For Windows user, you can install conda using [this link](https://www.anaconda.com/products/individual).

If you are in a linux system, you can follow the instructions given [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html) to install conda.

## Creating new environments

After you have installed conda, go to the conda terminal (or the actual terminal in Linux systems) and run the following command:

> conda create -n dnn python=3.7

Doing this will create a new independent python environment where you can download packages from.

In order to activate the environment, run:

> conda activate dnn

Now, since we are using tensorflow version 2.3, (which is not apparently included in conda yet), use pip to install it. 

> pip install tensorflow==2.3

For other important packages, we can conda installer, as installing from conda is usually a safer option. 

> conda install -c conda-forge notebook
> conda install -c anaconda matplotlib

## Running Notebook

To run the notebook, go to the folder containing the `.ipynb` notebook and type
> ipython notebook

# Help

If you have problems configuring the conda environment, feel free to post the problem in [piazza](https://piazza.com/class/kkj9mox3wc3676), or come to my office hours. You can also contact me through email at kapil.devkota@tufts.edu.
