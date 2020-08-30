# Project Structure
Machine learning engineering is software engineering. So, ML projects and production should follow software development
 practices and principles. Project structure and organization are a fundamental component to any form of software
  development.
 
An organized project structure makes your work navigable to you and other developers. You'll notice popular
 repositories and open source projects on [GitHub](https://github.com) have an intentional structure.

## Project Templates

There's fantastic project templates available for python development. 

### Cookiecutter

From the [Cookiecutter](https://cookiecutter.readthedocs.io/en/latest/README.html) documentation:
> A command-line utility that creates projects from cookiecutters (project templates), e.g. creating a Python package project from a Python package project template.

Cookiecutter can be used to **create** a project template. We care about **using** templates.

#### Recommended Templates

1. [Cookiecutter PyPackage](https://github.com/audreyfeldroy/cookiecutter-pypackage)

The PyPackage template is a great resource for building a PyPI supported package. The primary features of the template:

>- Testing setup with unittest and python setup.py test or pytest
>- Travis-CI: Ready for Travis Continuous Integration testing
>- Tox testing: Setup to easily test for Python 2.7, 3.5, 3.6, 3.7
>- Sphinx docs: Documentation ready for generation with, for example, ReadTheDocs
>- bump2version: Pre-configured version bumping with a single command
>- Auto-release to PyPI when you push a new tag to master (optional)
>- Command line interface using Click (optional)

2. [Cookiecutter Data Science](https://github.com/drivendata/cookiecutter-data-science)

Template directory structure: 
```
├── LICENSE
├── Makefile           <- Makefile with commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── src                <- Source code for use in this project.
│   ├── __init__.py    <- Makes src a Python module
│   │
│   ├── data           <- Scripts to download or generate data
│   │   └── make_dataset.py
│   │
│   ├── features       <- Scripts to turn raw data into features for modeling
│   │   └── build_features.py
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │   │                 predictions
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations
│       └── visualize.py
│
└── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io
```

#### Getting Started

Follow the [installation guide](https://cookiecutter.readthedocs.io/en/latest/installation.html):
1. Install the package 

    ```$ python3 -m pip install --user cookiecutter```

2. Clone the template of your choice

    ```$ git clone git@github.com:audreyr/cookiecutter-pypackage.git```

3. Once you've cloned a template, you can reuse it to create additional projects

    ```$ cookiecutter cookiecutter-pypackage/```