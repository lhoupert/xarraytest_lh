Test repository to document issue in Xarray library
==============================
[![Build Status](https://travis-ci.com/lhoupert/xarraytest_lh.svg?branch=master)](https://travis-ci.com/lhoupert/xarraytest_lh)
[![codecov](https://codecov.io/gh/lhoupert/xarraytest_lh/branch/master/graph/badge.svg)](https://codecov.io/gh/lhoupert/xarraytest_lh)
[![License:MIT](https://img.shields.io/badge/License-MIT-lightgray.svg?style=flt-square)](https://opensource.org/licenses/MIT)

A repositiory to document a bug in the conversion of [Pandas DataFrame](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html) into [Xarray](http://xarray.pydata.org/en/stable/index.html).

## Issue

For a reason unknown, the DataSet coordinates have not been sorted by ascending order at the creation of the DataSet (using the DataFrame.to_xarray .. The original multi-level DataFrame has been generated by the concatenation of two DataSeries.

Interestingly, this problem doesnt occur if the original Multi-level DataFrame is generated using the grouby() method...



--------

<p><small>Project based on the <a target="_blank" href="https://github.com/lhoupert/cookiecutter-science-project">cookiecutter science project template</a>.</small></p>
