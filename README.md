This repository contains a notebook about ConvNets that was presented at ML Sirius on April 30th 2018.

# Installation

You should have [Python 3](https://www.python.org/) (and pip) installed on you machine.

We'll use `vitualenv` for setting up our work environment. If you don't have it installed,
you can do so by running in a terminal (with admin privilege) `pip install virtualenv`.

To create the environment run 
```sh
virtualenv env
```

Now we can activate the environment and install all dependencies.
```sh
source env/bin/activate  # On Window's PowerShell run "env\Scripts\activate.ps1"
pip install -Ur top-requirements.txt
```

# Running

Once everything is installed, you can run Jupyter and navigate to the notebook
by running in a terminal (with the environment activated) `jupyter notebook`.
