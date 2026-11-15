---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

# Machine Learning for Gravitational Dynamics

**Undergraduate Research | University of São Paulo (USP)**

**Research support:** São Paulo Research Foundation (FAPESP)

## Overview

This undergraduate research investigated the application of machine learning to gravitational dynamical systems, focusing on predicting the temporal evolution of two-body and three-body systems.

Gravitational dynamics presents a challenging problem for machine learning due to nonlinear interactions, sensitivity to initial conditions, and the accumulation of prediction errors over time.

The project combined numerical simulations, deep learning, and physics-informed training techniques to investigate the capabilities and limitations of neural networks in modeling gravitational systems.

## Research Objectives

The main objectives were:

- Predict future positions and velocities from previous system states.
- Investigate autoregressive Transformer architectures for trajectory prediction.
- Incorporate physical constraints into neural network training.
- Compare neural network predictions against numerical reference simulations.
- Evaluate trajectory accuracy and physical consistency over multiple prediction steps.

## Methodology

### Numerical Simulations

Reference trajectories were generated using numerical integration methods, including a fourth-order Yoshida integrator.

These simulations provided the reference data used for training, validation, and evaluation of the neural networks.

### Machine Learning Architecture

The project investigated autoregressive Transformer models implemented using PyTorch.

The models were trained to predict the evolution of gravitational systems from sequences of previous states.

Physics-informed loss functions were explored to incorporate physical properties into the learning process.

### Model Evaluation

Model performance was evaluated through:

- Position prediction errors.
- Autoregressive prediction horizons.
- Relative variation of total mechanical energy.
- Momentum-related consistency measures.
- Comparisons between predicted and reference trajectories.

## Technologies

**Programming:** Python

**Machine Learning:** PyTorch, Transformer Architectures

**Scientific Computing:** NumPy, Numerical Integration, Matplotlib

**Research Areas:** Machine Learning, Computational Physics, Scientific Computing

## Experimental Results

The following visualizations present selected results from three-body gravitational simulations.

Reference trajectories were generated numerically and compared with predictions produced by an autoregressive neural network over 100 consecutive prediction steps.

In the trajectory plots, solid lines represent reference trajectories, while dashed lines represent neural network predictions.

### Three-Body Trajectory Prediction — Validation 244

![Three-body trajectory prediction — validation 244]({{ '/images/traj_val244.png' | relative_url }})

*Validation example 244. The model maintained a normalized position error below 1% of the system scale for 44 prediction steps and below 10% throughout the 100-step horizon. The accompanying plots show the evolution of position error and relative energy variation.*

### Three-Body Trajectory Prediction — Validation 404

![Three-body trajectory prediction — validation 404]({{ '/images/traj_val404.png' | relative_url }})

*Validation example 404. The model maintained a normalized position error below 1% of the system scale for 82 prediction steps and below 10% throughout the 100-step horizon. The accompanying plots illustrate trajectory prediction accuracy and relative energy variation.*

### Additional Validation Examples

![Three-body validation examples]({{ '/images/grade.png' | relative_url }})

*Selected three-body configurations illustrating the diversity of trajectories and the variation in autoregressive prediction accuracy across different initial conditions.*

## Discussion

The experimental results illustrate how autoregressive neural networks can approximate the evolution of gravitational systems over multiple time steps.

Prediction accuracy varies across different initial conditions and dynamical configurations. Some trajectories remain close to the numerical reference throughout the evaluation horizon, while others exhibit increasing deviations.

The experiments also highlight the importance of evaluating physical consistency alongside trajectory prediction accuracy.

These examples are selected visualizations and should not be interpreted as aggregate performance statistics across the entire validation dataset.

## Source Code

The implementation of numerical simulations, dataset generation, neural network training, and evaluation is available on GitHub.

[View the Scientific Initiation Repository](https://github.com/gabrielhr77/scientific_initiation)
{: .btn .btn--primary }
