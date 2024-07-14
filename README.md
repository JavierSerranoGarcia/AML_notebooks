# DSA 8401 Applied Machine Learning in Data Science

This repository is a complement to the Course AML in the Master in Data Science at Strathmore University

## Quick Start
Want to play with these notebooks online without having to install anything?

    Open In Colab (recommended)

* Colab provides a temporary environment: anything you do will be deleted after a while, so make sure you download any data you care about.*

## Want to install this project on your own machine?

Start by installing Anaconda (or Miniconda), git, and if you have a TensorFlow-compatible GPU, install the GPU driver, as well as the appropriate version of CUDA and cuDNN (see TensorFlow's documentation for more details).

Next, clone this project by opening a terminal and typing the following commands (do not type the first $ signs on each line, they just indicate that these are terminal commands):

```
$ git clone https://github.com/JavierSerranoGarcia/AML_notebooks.git
$ cd AML_notebooks
```

Next, run the following commands: 

```
$ conda env create -f environment.yml # Change to a python virtual environment
$ conda activate homl3
$ python -m ipykernel install --user --name=python3
```

Finally, start Jupyter:

  jupyter notebook

