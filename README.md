# UoB-Orcid-2019

## Title
Univeristy of Bristol Orcid and PURE data 2019

## Overview

Each researcher has pieces of text associated with them that to some extent define their research interests. This may be a set of published articles, blog posts, biographies or even the contents of a reference manager. However, the methods available to search these are usually global solutions, which often provide poor results, returning the most obvious results, and fail to offer insight into their methodology.

By using freely available data on a relatively small group of people, it should be possible to provide a superior search method and allow us to explore the relationships within. Ideally this would provide some level of explainability, e.g. which words/concepts were most important in identifying a person. Modern text embedding methods make this kind of problem relatively easy to approach, but how can we explain the findings they deliver? In addition, what can we identify within this group of people? Can we identify communities and annotate them with suitable terms? Can we predict collaborations? Can we predict future areas of research? Is it possible to identify knowledge gaps?

# Data

See [data/README.md](data/README.md)

# Notebooks

1. People and publications
 - How to get data from PubMed
 - How to get data from ORCID
 - How to automate the above

## Setup

#### Prerequisites

Using Anaconda (recommended)

Clone tutorial repo:

```
#SSH
git clone git@github.com:elswob/UoB-Orcid-2019.git

#HTTPS
git clone https://github.com/elswob/UoB-Orcid-2019.git
```

Activate jupyterlab environment:

```
cd UoB-Orcid-2019
conda env create -f environment.yml
conda activate UoB-Orcid-2019
jupyter lab
```

you will see a jupyter lab in your browser
