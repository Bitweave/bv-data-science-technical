# Data Science technical test

## Overview

This repository contains two technical tests:
 - Titanic Survival, iterate on a very simple classification model
 - Wikipedia Edits, explore a time series graph dataset

You can explore one or both depending on time.

## Setup

NB: If setup on your system is not possible, do not worry someone from Bitweave will share their screen and the technical test will be done as a pair programming exercise.

### Pre-requisites:
 - pipenv
 - pyenv

### Install

Option 1 - Recommended:
```bash
$ pipenv install --skip-lock
$ pipenv shell
```

Option 2 - **NOT** recommended:
```bash
$ pip install jupyter pandas networkx sklearn matplotlib
```

### Run Jupyter
```bash
$ jupyter notebook
```

## Contents
```dir
\bv-data-science-technical
    \data
        - \titanic
            - test.csv
            - train.csv
        - \wikipedia
            - test.csv
            - train.csv
  - Pipfile
  - Pipfile.lock
  - Titanic Survival.ipynb
  - Wikipedia Edits.ipynb
```
