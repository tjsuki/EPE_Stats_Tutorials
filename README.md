# EPE Stats Tutorials

## Install Conda

Install conda: https://docs.conda.io/projects/conda/en/latest/user-guide/install/



First, create an environment with only the packages for this tutorial, so that you can keep it separate and other installs on your system won’t interfere with it, and activate the environment so that you can access those packages.

conda create --name EPE_Stats_Packages python

conda activate EPE_Stats_Packages


Now that you are in the appropriate environment, install the following packages:

- conda install - c conda-forge jupyterlab (this gives you access to the full jupyterlab integrated development environment, or IDE, if you just want the base functionality you can use conda install -c conda-forge notebook)
- conda install -c anaconda scipy
- conda install -c conda-forge matplotlib
- conda install -c anaconda numpy (if you don’t have it already or by default)

You can use: 
- conda list to see the packages you’ve installed in this environment
- conda info --envs to see which environments are available/you’ve created

cd to your favorite directory and clone this repository:

Git clone https://github.com/cartervu/EPE_Stats_Tutorials.git

Open the notebook:

jupyter-notebook PATH/TO/NOTEBOOK.ipynb or jupyter-notebook PATH/TO/DIRECTORY if you like jupyter's GUI.

Heads up: eventually, we want to move to reproducing the plots in the paper here (https://arxiv.org/pdf/1007.1727.pdf), where we’ll want to have some familiarity with numpy, matplotlib, and scipy. Hold on to your hats!

