---
layout: page17
title: Speakers
permalink: /ICML17/speakers/
name: 6
---

## David Sontag

#### Title: Deep Markov models

#### Abstract:
Gaussian state space models have been used for decades as generative
models of sequential data. They admit an intuitive probabilistic
interpretation, have a simple functional form, and enjoy widespread
adoption. We introduce a unified algorithm to efficiently learn a
broad class of linear and non-linear state space models, including
variants where the emission and transition distributions are modeled
by deep neural networks. Our learning algorithm simultaneously learns
a compiled inference network and the generative model, leveraging a
structured variational approximation parameterized by recurrent neural
networks to mimic the posterior distribution. We apply the learning
algorithm to both synthetic and real-world datasets, demonstrating its
scalability and versatility. We find that using the structured
approximation to the posterior results in models with significantly
higher held-out likelihood.

Joint work with Rahul Krishnan and Uri Shalit.

## Ryan Adams

#### Title: Building Probabilistic Structure into Massively Parameterized Models

#### Abstract:
Scientific applications of machine learning typically involve the identification of interpretable structure from high-dimensional observations.  It is often challenging, however, to balance the flexibility required for high dimensional problems against the parsimonious structure that helps us model physical reality.  I view this challenge through the lens of semiparametric modeling, in which a massively-parameterized function approximator is coupled to a compact and interpretable probabilistic model.  Of particular interest in this vein is the merging of deep neural networks with graphical models containing latent variables, which enables each component to play to its strengths.  I will discuss several different classes of such models, and various applications, in areas such as astronomy, chemistry, neuroscience, and sports analytics.

