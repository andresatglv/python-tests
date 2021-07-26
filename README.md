[![Build Status](https://travis-ci.com/lfponton/python-tests.svg?branch=main)](https://travis-ci.com/lfponton/python-tests)

# python-tests

This reporsitory is a test to include Travis CI and Codecov in a repository.

The code included is from the Unit Testing for [Data Science in Python by Dibya Chakravorty](https://learn.datacamp.com/courses/unit-testing-for-data-science-in-python).

Before running `pytest`, make sure you have installed the package `univariate_linear_regression` using pip. Otherwise, `ImportError`s might be raised.

To install, first clone the repo
```
git clone https://github.com/lfponton/python-tests.git
```
Then install the package locally using pip, while in the repo's folder, making sure that your Python version is `>=3.6`.
```
pip install -e .
```
To run all the test do
```
cd univariate_linear_regression
pytest --mpl
```
