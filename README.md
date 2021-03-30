# calc-distributions
This python package can be installed to use statistical operations for several distributions.

## How to use
To use this python package you have to clone or download the repository. In the calc-distribution folder you need to execute the command `pip install .`.
This installs the package to your global python installation. Note: Maybe you want to use a virtual environment to try out the package first without installing it to your global python installation.
To use the methods in python you can write: `from distributions import Gaussian, Binomial`

## Files
* distributions/ : This folder contains the actual implementation of the package functionality
* test.py: Unit tests that ensure the correct functionality
* test_data/ : Folder that contains small .txt files that contain data that is used in the unit tests
* setup.py: File that is needed to install this package 
