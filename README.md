[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/exchez/amazon-bayes/) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/exchez/amazon-bayes/master) [![NBViewer](https://raw.githubusercontent.com/jupyter/design/bfbff5d7eec8bd8be413deffecff0f4de29fd5cf/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/exchez/amazon-bayes/blob/master/amazon-bayes.ipynb)

# How a Bayesian Shops on Amazon
This notebook uses Bayesian analysis to determine the probability that one product is better than another.

## Motivation
The reason I chose to publish this notebook are three-fold:
1. I wanted to tackle a problem that used the multinomial and dirichlet distributions rather than the typical binomial with a beta prior
2. I hoped to show that Bayesian analysis can be used to solve very practical problems and give intuitive results
3. I wanted to help people who are familiar with the basics of Bayes' Rule and probability extend the concept for use with distributions and relative likelihoods

### Run with Docker on your machine (must have Docker installed)
1. `git clone https://github.com/exchez/amazon-bayes.git`
2. `cd amazon-bayes`
3. `docker-compose up`
4. `docker-compose down` when you're done

### Run on Binder
1. Click the link to binder above
2. Get up and grab a coffee (optional). It may take ~15 minutes to build the image if it's not cached.
3. Replace "tree" at the end of the url with "lab" to run in Jupyter Lab (optional). Though I actually think it looks nicer in a notebook.
