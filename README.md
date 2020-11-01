[![Travis CI Build Status](https://travis-ci.com/calekochenour/computational-publication-environment.svg?branch=main)](https://travis-ci.com/calekochenour/computational-publication-environment)
[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/32r7s2skrgm9ubva?svg=true)](https://ci.appveyor.com/project/calekochenour/computational-publication-environment)
[![BSD 3-Clause License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

# Computational Publication Environment

This repository contains a Conda environment to create computational publications with Jupyter Book and host published content on GitHub Pages.

## Prerequisites

If install and use the environment locally, you will need:

 * Conda ([Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://docs.anaconda.com/anaconda/install/))

## Local Setup Instructions

Local instructions expect the user has cloned or forked the GitHub repository. In a terminal, navigate to the folder containing the local repository.

### Create and Activate Conda Environment

From the terminal, you can create and activate the Conda environment.

Create environment:

```bash
conda env create -f environment.yml
```

Activate environment:

```bash
conda activate computational-publications
```

## Contents

### `Makefile`

Contains instructions to automate Jupyter Book builds and GitHub commits.

### `environment.yml`

Contains all information to create the Conda environment required to create content with Jupyter Book.  
