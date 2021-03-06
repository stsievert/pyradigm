# Pyradigm: PYthon based data structure to improve Dataset's InteGrity in Machine learning workflows
----

[![travis](https://travis-ci.org/raamana/pyradigm.svg?branch=master)](https://travis-ci.org/raamana/pyradigm.svg?branch=master)
[![Code Health](https://landscape.io/github/raamana/pyradigm/master/landscape.svg?style=flat)](https://landscape.io/github/raamana/pyradigm/master)
[![PyPI version](https://badge.fury.io/py/pyradigm.svg)](https://badge.fury.io/py/pyradigm)
[![codecov](https://codecov.io/gh/raamana/pyradigm/branch/master/graph/badge.svg)](https://codecov.io/gh/raamana/pyradigm)

A common problem for a machine learners is to keep track of source of the features extracted, and ensure integrity of the dataset. This is incredibly hard as the number of projects grow, or personnel changes are frequent (hence breaking the chain of hyper-local info about the dataset). This package provides a Python data structure to encapsulate a machine learning dataset with key info greatly suited for neuroimaging applications (or any other domain), where each sample needs to be uniquely identified with a subject ID (or something similar). Key-level correspondence across data, labels (1 or 2), classnames ('healthy', 'disease') and the related helps maintain data integrity, in addition to offering a way to easily trace back to the sources from where the features have been originally derived.

Thanks for checking out. Your feedback will be appreciated.

## Installation

`pip install pyradigm`

## Usage

This [Pyradigm Example](PyradigmExample.ipynb) notebook illustrates the usage.

## Requirements

 * Packages: `numpy`
 * Python versions: I plan to support all the popular versions soon. Only 2.7 is tested for support at the moment.

## Support on Beerpay
Hey dude! Help me out for a couple of :beers:!

[![Beerpay](https://beerpay.io/raamana/pyradigm/badge.svg?style=beer-square)](https://beerpay.io/raamana/pyradigm)  [![Beerpay](https://beerpay.io/raamana/pyradigm/make-wish.svg?style=flat-square)](https://beerpay.io/raamana/pyradigm?focus=wish)
