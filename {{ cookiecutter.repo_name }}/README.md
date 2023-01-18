# {{cookiecutter.algorithm_name}}
* {{cookiecutter.description}} *

## Quick Start
To get {{cookiecutter.algorithm_name}} up and running, ...

## Directory structure
The directory structure of this algorithm is as follows:

```
├── algorithm_name     <- The core files of the algorithm.
│   └── __init__.py
│   └── central.py     <- Functions for the server.
│   └── remote.py      <- Functions for the nodes (which have access to the data).
│
├── docs               <- Files of the algorithm's Sphinx documentation.
│
├── examples           <- Examples of how to use the algorithm in the
|   |                     shape of Jupyter notebooks.
│   └── 01_xyz_running_the_algorithm.ipynb
│
├── tests              <- Functions for testing the algorithm.
│   └── test_environment.py       
│
├── .gitignore
|
├── Dockerfile
|
├── LICENSE
|
├── Makefile
|
├── README.md          <- The current README.
|
├── requirements.txt   <- The requirements file for reproducing the algorithm
|                         environment.
│
├── setup.py           <- Makes the algorithm pip installable (pip install -e .)
|                         so algorithm_name can be imported.
│
└── tox.ini            <- tox file with settings for running tox.
                          See https://tox.wiki/
```


--------

<p><small>Project based on the <a target="_blank" href="https://github.com/vantage6/cc_algorithm_python">Cookiecutter for Python Algorithm Development for vantage6</a></small></p>
