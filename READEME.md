# Pandas Exercise with vscode jupter notebook

## python environment and jupyter install
We need the latest python3 environment, first check the python version
```python
python --version
```
Expect it return 
Python 3.1x.x for example 3.12.0

if the python version below 3.6.x, please update the python version.

### Python windows install
Download the latest python3 windows installer from https://www.python.org/downloads/windows/
or
install the anaconda package manager from https://www.anaconda.com/products/individual

### Python osx install
if you are the mac user, you can use the brew package manager to install the python3.
```bash
brew install python3
```

### use the pyenv as the python version manager to manage the multiple version of python
Pyenv is the tools to help you to install and manage multiple version of python. on the osx system, you can use the brew to install it.
```bash
brew install pyenv
```
please use google to install the pyenv on other os.

### Jupyter install
Jupyter is the web interface to run the python code interactivly on the browser.

```bash
python3 -m venv .venv # create a new virtual environment
source .venv/bin/activate # activate the new virtual environment
pip install jupyter altair vega-datasets vega pandas jupyter_http_over_ws wheel
jupyter serverextension enable --py jupyter_http_over_ws
``` 
now you can use jupyter
```bash
jupyter notebook
```