---
layout: post
title: Projects
date: 2017-03-22 12:00:00
cover: cover.jpg
categories: home
---

<br>
<img src="/images/gaussbock_examples.png" width="100%">

__Fast parallel-iterative cosmological parameter estimation with Bayesian nonparametrics__

Current efforts in cosmological parameter estimation often suffer from both the computational costs of approximating distributions in high-dimensional parameter spaces and the wide-spread need for model tuning. With these contemporary problems in mind, Gaussbock was developed as an easy-to-use tool for embarrassingly parallel high-dimensional parameter estimation with expensive likelihoods for the wider astronomy community. It is, however, a general-purpose posterior approximation tool suitable for many applications. In the above picture, you can see the evolution of the fist ten steps of the iterative fitting process on a 26-dimensional Dark Energy Survey Y1 approximation.

With a foundation in Bayesian nonparametrics, variational inference, estimation theory and parallel computing, Gaussbock builds on our recent research in iterative sampling methods and supports both multi-processing for local cluster computing and MPI for external clusters and supercomputers, without any effort on the user's side. We demonstrate the viability of our approach in our corresponding [paper](https://arxiv.org/abs/1905.09800).

Since Gaussbock is on [PyPI](https://pypi.org/project/gaussbock/), simply type `pip install gaussbock` in your terminal to install it. This project was developed for Python 3, and the installation process will automatically install any necessary dependencies. Documentation and a quickstart guide on how to use Gaussbock can be found in a public code repository [here](https://github.com/moews/gaussbock), as well as in the open-source code's docstrings.

<br>
