# Introduction to Machine Learning - Final Project

The final project for Introduction to Machine Learning subject.

---

## Table of Contents

- [Setup Instructions](#setup-instructions)
  - [Dependencies Installation](#dependencies-installation)
    - [Using Anaconda or Miniconda (Environment)](#using-anaconda-or-miniconda-environment)
    - [Using Python (Standalone)](#using-python-standalone)
  - [.env File](#env-file)
- [Running the Program](#running-the-program)
- [License](#license)
- [Contributors](#contributors)

---

## Setup Instructions

Below are the steps on how to run the code in your local machine. This will
assume that you already have Python or Anaconda in your machine.

### Dependencies Installation

The project has several dependencies that are needed. To install these
dependencies, just follow one of the items below.

#### Using Anaconda or Miniconda (Environment)

If you are using Anaconda or Miniconda, you can open to the directory using
terminal. If Python is able to run in your terminal, then you could use the
following command:

```bat
conda install --f "requirements.txt"
```

#### Using Python (Standalone)

Using a standalone python without environments such as Miniconda or Anaconda,
you could simply use the `pip` command in your terminal.

```bat
pip install -r "requirements.txt"
```

### .env File

The project comes with a file named `.env.example`, which serves as a template
for a `.env` file or `environment` file. The `.env` file contains all the
secret tokens that will be used by the program during runtime.

To set one up, you just have to copy the `.env.example` file and rename that
copy to `.env` file.

Open the file and provide the two tokens. These tokens are spotify's developer
API tokens which grants developers to use their web API for free.

**You can see yours in:**\
`Dashboard` → `<project_name>` → `Settings`

**Or basically, in a url similar to this:**\
`https://developer.spotify.com/dashboard/<project_id>/settings`

## Running the Program

Running the program is as simple as pressing a button (assuming you already have
Jupyter installed). If Jupyter is not yet installed, either install a VSCode
extension or install [Jupyter Notebook](https://jupyter.org/) into your local
machine.

When running the program, just press the `Run All` button or manually run every
cell from the top until the bottom.

## License

This project uses and is distributed under the [Unlicensed License](https://unlicense.org)
and is subject to all its terms and conditions.

See `LICENSE` for more information.

## Contributors

[![Contributors](https://contrib.rocks/image?repo=Virus5600/CCMACLRL_FINAL_PROJECT_COM222ML)](https://github.com/Virus5600/CCMACLRL_FINAL_PROJECT_COM222ML/graphs/contributors)
