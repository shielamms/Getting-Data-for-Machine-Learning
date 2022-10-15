# Setting up your Python environment

This project was tested with Python 3.8. To ensure that all code in the book can be executed in your local environment, I recommend installing a Python environment manager like `pyenv` and install Python version 3.8 or any of its sub-versions.

```
pyenv version install 3.8.8
pyenv local 3.8.8
```

You can create a virtual environment using `virtualenv` to install dependencies and run the code in an isolated environment.

```
virtualenv venv
source venv/bin/activate
```

Inside your virtual environment, install the following libraries:

```
matplotlib==3.5.1
numpy==1.22.3
```
