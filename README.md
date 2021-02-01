# ISM\*@ST Machine Learning tutorial sessions
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jwuphysics/ism-star-ml)

Presented by John F. Wu ([@jwuphysics](https://github.com/jwuphysics)) and Josh Peek ([@jegpeek](https://github.com/jegpeek)).

# Getting started

## Running on Google Colab (*recommended*)
Open the Colab notebooks for the [introductory machine learning (part 1)](https://colab.research.google.com/drive/1MxWjF1vdBF3ArQ6WAR3meV-ytNOVnIOr?usp=sharing) and the [deep learning (part 2)]() sessions.

## Running locally (*not recommended*)
If you want to run these notebooks locally, then you should clone the repository and set up a conda environment with the necessary packages (`numpy`, `scipy`, `matplotlib`, `pandas`, `scikit-learn`, `pytorch`, `fastai`). The installation process might depend on (a) whether you have an NVIDIA graphics card, and (b) what version of CUDA your system is running. To avoid these complications, just use the Colab notebook!

# Part 1 - Introductory Machine learning 
[![Colab - Part 1](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jwuphysics/ism-star-ml/blob/main/notebook/ISM_ST_Introductory_Machine_Learning.ipynb)

0. Before getting started
1. Can we predict a galaxy's neutral hydrogen (HI) content?
    - Examine data with pandas
    - A very simplified glossary for xGASS
    - Examine and clean features
    - Visualize correlations
2. Polynomial regression
    - Multivariate linear regression
    - Train-test split
    - Cross-validation
    - Quadratic and higher-order polynomial models
    - Overfitting
3. Decision trees
    - How scikit-learn does it
    - Random forests
    - Optimize hyperparameters
    - Feature importances

# Part 2 - Deep learning

1. Introducing the science problem (again)
2. Solving the task with a CNN
3. Understanding convolutions
4. Other neural network ingredients
5. Backpropagation and optimization
6. Hyperparameters

# Other resources

- [ISM\*@ST Bayesian tutorials by Erik Tollerud](https://github.com/eteq/bayes-ismstar)
- [Data analysis recipes: Fitting a model to data](https://arxiv.org/abs/1008.4686)
- [Scikit-learn - Machine learning with Python](https://scikit-learn.org/stable/)
- [Fast.ai - Practical Deep Learning for Coders](https://course.fast.ai/)
