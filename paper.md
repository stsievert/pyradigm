---
title: 'Python class defining a machine learning dataset ensuring key-based correspondence and maintaining integrity'
tags:
  - neuroscience
  - machine-learning
  - object-oriented-programming
  - dataset
authors:
 - name: Pradeep Reddy Raamana
   orcid: 0000-0003-4662-0558
   affiliation: 1
affiliations:
 - name: Rotman Research Institute, Baycrest Health Sciences, Toronto, ON, Canada
   index: 1
date: 24 August 2017
bibliography: paper.bib
---

# Summary

A common problem for a machine learners is to keep track of source of the features extracted, and ensure integrity of the dataset. This is incredibly hard as the number of projects grow, or personnel changes are frequent (hence breaking the chain of hyper-local info about the dataset). This package provides a Python data structure to encapsulate a machine learning dataset with key info greatly suited for neuroimaging applications (or any other domain), where each sample needs to be uniquely identified with a subject ID (or something similar). Key-level correspondence across data, labels (1 or 2), classnames ('healthy', 'disease') and the related helps maintain data integrity, in addition to offering a way to easily trace back to the sources from where the features have been originally derived.

This data structure also helps ease the machine learning workflow by offering several well-knit methods and useful attributes specifically geared towards neuroscience research.

# References

 - Raamana, P.R., 2017, *neuropredict: easy, standardized and comprehensive predictive analysis for neuroimaging features*, GitHub. URL: https://github.com/raamana/neuropredict
