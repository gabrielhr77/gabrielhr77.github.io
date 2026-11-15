---
title: "Gravitational Dynamics with Neural Networks"
excerpt: "Autoregressive Transformers, physical constraints and numerical integration for gravitational trajectory prediction."
collection: portfolio
permalink: /portfolio/gravitational-dynamics/
order: 1
category: "Machine Learning · Scientific Research"
image: "/images/traj_val404.png"
image_alt: "Three-body trajectory prediction compared with numerical reference paths"
github: "https://github.com/gabrielhr77/scientific_initiation"
technologies:
  - Python
  - PyTorch
  - Transformers
  - NumPy
---

# Gravitational Dynamics with Neural Networks

**Undergraduate Research | University of São Paulo (USP) | FAPESP support**

## The Problem

Predicting the evolution of gravitational systems is a challenging numerical task. Small prediction errors can grow as trajectories evolve, making multi-step forecasting and physical consistency important evaluation criteria.

## What I Built

- Numerical simulation workflows for gravitational two-body and three-body systems.
- Structured datasets of time-series trajectories for machine learning experiments.
- Autoregressive Transformer-based models implemented with **PyTorch**.
- Training and evaluation routines using prediction errors and physical-consistency measures.

## Evaluation

I compared predicted trajectories with numerical reference solutions and investigated how errors accumulate across autoregressive prediction horizons. The research also considered mechanical energy and momentum-related quantities.

![Reference and predicted three-body trajectories]({{ '/images/traj_val404.png' | relative_url }})

For additional plots, methodology and discussion, see the [full Research page]({{ '/research/' | relative_url }}).

## Technologies

Python, PyTorch, NumPy, Matplotlib, Transformers, Numerical Integration.

[Explore source code](https://github.com/gabrielhr77/scientific_initiation) · [Research details]({{ '/research/' | relative_url }})
