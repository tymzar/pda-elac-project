# Languages, Automata and Computations - Project

Compiled Notebook can be found [here](https://tymzar.github.io/pda-elac-project/).

## Prerequisites

### Python

```bash
python --version
Python 3.10.6
```

This project is written in Python 3.10.6. It is recommended to use `venv` to install dependencies.

### Install `venv` with:
```bash
sudo apt install python3-venv
python3 -m venv .env
```

### Install Graphviz
Python package `pygraphviz` requires `graphviz` to be installed. On Ubuntu, this can be done with:

```bash
sudo apt install graphviz-dev
```

### Install Python packages
Python packages required for this project are listed in `requirements.txt`.
Those can be installed with:
```bash
pip install -r requirements.txt
```

### Running Jupyter notebooks in Visual Studio Code
1. Install the Jupyter extension in Visual Studio Code.
2. Open the Command Palette (Ctrl+Shift+P) and type 'Jupyter: Create New Blank Notebook'.
3. Once the notebook is open, you can run your code cells by clicking the 'Run Cell' button that appears at the top of each cell.
4. To view the output of a code cell, select the cell and the output will appear below the cell.