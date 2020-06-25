# Big Data Analytics Projects

This file is a short readme about setting up the environment for running the projects.

## Setup Anaconda environment

### The fast way
```
> conda env create -f environment.yml
> conda activate big-data-projects
```

### The manual way
```
> conda create --name big-data-projects python=3.7
> conda activate big-data-projects
> conda install pandas
> conda install matplotlib
> conda install seaborn
> conda install pymongo
> conda install -c anaconda neo4j-python-driver
> conda install nltk
> conda install -c intel scikit-learn
```