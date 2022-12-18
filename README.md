# IP Modeling tutorial

<div width="50%">
<img src="https://www.pygimli.org/_images/pg_logo.png" width=40%>
</div>

## Installation instructions

### Step 1: Prerequisites

There are a few things you'll need to follow the tutorial:

1. A working Python installation (Anaconda or Miniconda). For details on how to install Anaconda, we refer to: https://docs.anaconda.com/anaconda/install/
2. A modern web browser that works with JupyterLab or Jupyter Notebook (Internet explorer will not work)
3. Intermediate experience in Python programming (Python, numpy, matplotlib, jupyter)
4. Background on geophysical modeling and inversion

### Step 2: Download material for the tutorial

- [Download the course material](https://github.com/florian-wagner/ip_modeling/archive/refs/heads/main.zip) and unzip it a folder of your choice.
- or, alternatively, open a terminal, navigate to a folder of your choice, and execute `git clone https://github.com/florian-wagner/ip_modeling`.


### Step 3: Install the tutorial environment

1. Open a terminal (Linux & Mac) or the Anaconda Powershell Prompt (Windows). Navigate to the folder from step 2 (using the `cd` command) and type:

- 1.1: If you have not created a `pg` environment before.
```
conda env create
```

- 1.2: If you already have an existing `pg` environment.
```
conda env update
```

2. Activate the environment in the terminal by typing:

```
conda activate pg
```

3. To test if everything works correctly you can do the following:

```
python -c "import pygimli; import pybert"
```

4. Make the environment available in Jupyter

```
python -m ipykernel install --user --name pg --display-name "pyGIMLi 1.3.1"
```