# EUMEN - Quantum Hardware Chemistry

A Python package for quantum chemistry on quantum hardware
built on top of tket. Supported versions of Python are 
v3.7, v3.8, v3.9.

This repo contains public documentation for using EUMEN.  EUMEN is currently in closed beta.  For enquiries regarding beta access to EUMEN, please contact eumen-support@cambridgequantum.com.


# Getting Started

To install EUMEN and the packages necessary to run EUMEN, the package management
system pip is required (see https://pypi.org/project/pip). We recommend using Python 3.8 for running EUMEN.
The most convenient way to do this is to create a conda environment. To
install conda, see

http://conda.io/projects/conda/en/latest/user-guide/install

Then create a conda environment with python version 3.8 specified. In a
terminal, type:

| ``conda create -n your-env python=3.8``
| ``conda activate your-env``

Then install EUMEN from the private python index provided with the beta credentials:

``pip install eumen -i <index-url>``

For support with Jupyter Notebooks (required for the tutorials and demonstrations), please also type:

``pip install notebook``

Within the private documentation accessible by beta testers, there are several tutorials and examples of how to use EUMEN.
