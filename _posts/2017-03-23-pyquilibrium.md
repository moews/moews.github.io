---
layout: post
title: Projects
date: 2017-03-23 12:00:00
cover: cover.jpg
categories: home
---

<br>
<img src="/images/pyquilibrium_example.png" width="100%">

__Pure-Python equilibrium model of galaxy evolution code with speedy *t*-*z* splining__

The equilibrium model is an analytic formalism to describe the evolution of a set of baryonic galaxy properties, specifically the star formation rate, gas fraction and metallicity. These steps are calculated based on the initial redshift and mass of the galactic dark matter halo. N-body simulations are limited to dark matter, which only interacts gravitationally and is thus comparatively fast to simulate. Analytic formalisms can be used to complete such simulations with baryonic properties.

After the incorporation of related work, this code provides the first pure-Python implementation of the formalism and played a crucial role in the development of our corresponding [paper](https://arxiv.org/abs/2012.05820) on the combination of analytic and machine learning models. The code includes largest-progenitor merger trees, and the relationship between cosmological age and redshift is splined outside the primary loop to avoid computing the redshift for each separate iteration.

The code for PyQuilibrium is available [here](https://github.com/moews/pyquilibrium) and was created for Python 3. It requires the final redshift and dark matter halo mass, as well as values for the Hubble constant and total matter density.

<br>
