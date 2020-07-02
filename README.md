# Big Data Analytics Projects

Questo file è un breve README con le istruzioni per creare l'environment con le dipendenze necessarie per eseguire i progetti.

## Setup Anaconda environment

### Import automatico dell'environment da file (Consigliato)
```
> cd path/to/dir
> conda env create -f environment.yml
> conda activate big-data-projects
```

### Setup manuale
```
> conda create --name big-data-projects python=3.7
> conda activate big-data-projects
> conda install pandas
> conda install matplotlib
> conda install seaborn
> conda install pymongo
> conda install -c anaconda neo4j-python-driver
> pip install neo4j-driver
> conda install nltk
> conda install -c intel scikit-learn
> conda install -c conda-forge tqdm
```
