# PhD-Thesis-Notebooks
Notebooks containing the code used to generate most of the figures of my Ph.D. Thesis

## Prerequisites

Before you begin, ensure you have met the following requirements:
- You have installed [Anaconda](https://www.anaconda.com/products/individual) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html).
- You have a basic understanding of Python programming.

## Setting Up Your Development Environment

To set up the project development environment, follow these steps:

### Cloning the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/albertomercurio/PhD-Thesis-Notebooks
cd PhD-Thesis-Notebooks
```

### Creating a Conda Environment

Create a new Conda environment by running:

```bash
conda create -n myenv python=3.12
conda activate myenv
```

Replace `myenv` with a name of your choice, and feel free to specify another version of Python if needed.

### Installing Dependencies

Install the required packages using `pip` from the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### Configuring VSCode to Use the Conda Environment

To use the newly created Conda environment in VSCode, particularly for running Jupyter notebooks, follow these steps:

1. Open VSCode.
2. Press `Ctrl+Shift+P` to open the Command Palette.
3. Type `Jupyter: Select Interpreter to Start Jupyter Server` and select it.
4. Choose the Conda environment you created earlier (it should be prefixed with `Python 3.12` or the version you installed).

## Running the Notebook

Make sure to activate your Conda environment and start VSCode from the same terminal to ensure the environment settings are retained:

```bash
conda activate myenv
code .
```

Now you can run the Jupyter notebooks from VSCode, ensuring all code executes within the context of your Conda environment.
