# A Notebook about NLP Spacy course

## About this notebook

This notebook is based on Ines Montani's free online course, available at:

https://course.spacy.io/

https://github.com/ines/spacy-course

## How to install spacy:

The instructions are in the link below :

https://spacy.io/usage

To install spacy, please use:

conda install -c conda-forge spacy

This notebook is tested for version 2.1.3

As per May, 4th 2019, installing Spacy via "conda install -c conda-forge spacy" delivers 2.0.8 version so I used "pip install -U spacy" to have version 2.1.3 in my computer

## How to download the models:

https://github.com/explosion/spacy-models/releases/

To download a model:

python -m spacy download pt
python -m spacy download en
To download a model:

python -m spacy download en_core_web_sm
python -m spacy download pt_core_news_sm
python -m spacy download en_core_web_md
python -m spacy download pt_core_news_md - there is not... :-(

## Using nbextensions

I highly recommend you to install table of contents from nbextensions, that makes the navigation in the sections much more easier.

Instructions can be found here:

https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/install.html

conda install -c conda-forge jupyter_contrib_nbextensions

jupyter nbextension enable toc2

## Additional information

Unfortunatedly gitHub is having issues to render these notebooks.

If you want to visualize them from the web, use nbviewer:

https://nbviewer.jupyter.org/github/Cristianasp/spacy/blob/master/Chapter_00.ipynb

https://nbviewer.jupyter.org/github/Cristianasp/spacy/blob/master/Chapter_01.ipynb

https://nbviewer.jupyter.org/github/Cristianasp/spacy/blob/master/Chapter_02.ipynb

