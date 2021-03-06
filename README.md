[![Travis CI Build Status](https://travis-ci.com/calekochenour/jupyter-book-env.svg?branch=main)](https://travis-ci.com/calekochenour/jupyter-book-env)
[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/32r7s2skrgm9ubva?svg=true)](https://ci.appveyor.com/project/calekochenour/jupyter-book-env)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4216297.svg)](https://doi.org/10.5281/zenodo.4216297)
[![BSD 3-Clause License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

# Jupyter Book Conda Environment

This repository contains a Conda environment to create computational publications with Jupyter Book and host published content on GitHub Pages.

## Prerequisites

To run and use this environment locally, you will need:

 * Conda ([Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://docs.anaconda.com/anaconda/install/))

## Local Setup Instructions

Local instructions expect the user has cloned or forked the GitHub repository. In a terminal, navigate to the folder containing the local repository.

From the terminal, you can create and activate the Conda environment.

Create environment:

```bash
$ conda env create -f environment.yml
```

Activate environment:

```bash
$ conda activate computational-publications
```

## Jupyter Book Instructions

This repository contains a `Makefile` that automates the commands to clean, build, and publish the Jupyter Book. To complete these tasks, change the `jupyter_book` variable to the name of the folder containing the Jupyter Book and change the `github_pages_commit_message` to a commit message the captures the updates.

Once all variables are set, run the following command to clean, build, and publish the updated Jupyter Book:

```bash
$ make publish-book
```

## Contents

### `Makefile`

Contains instructions to automate Jupyter Book builds and GitHub commits.

### `environment.yml`

Contains information to set up the Conda environment to create computational publications with Jupyter Book.  
