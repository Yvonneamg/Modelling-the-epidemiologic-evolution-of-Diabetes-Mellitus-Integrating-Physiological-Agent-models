# Modeling the Epidemiologic Evolution of Diabetes Mellitus  
## Integrating Physiological and Agent-Based Models

This repository contains a hybrid computational framework for modeling the long-term progression of Type 2 Diabetes Mellitus by combining:

- A physiological glucose–insulin dynamical system based on the De Gaetano model
- Behavioral dynamics derived from NHANES epidemiological data
- Heterogeneous population simulation
- Agent-based extensions for long-term disease evolution

The project explores how aging, diet, physical activity, insulin sensitivity and beta-cell decline interact over time to influence diabetes progression at both the individual and population levels.

---

# Project Objectives

- Reproduce and validate the De Gaetano physiological diabetes model
- Simulate glucose–insulin dynamics using ODE systems
- Integrate age-dependent behavioral changes from NHANES data
- Generate heterogeneous synthetic populations
- Study the impact of dietary and physical activity trajectories
- Build a scalable simulation framework using JAX and Diffrax

---

# Main Features

## Physiological Model
The model includes:
- Glucose dynamics
- Insulin secretion
- Beta-cell mass evolution
- Peripheral insulin sensitivity
- Hepatic insulin sensitivity
- Renal glucose elimination

## Behavioral Modeling
Behavioral trajectories are estimated from NHANES data:
- Physical activity (MVPA)
- Daily calorie intake
- Age-dependent behavioral trends
- Stochastic behavioral variation

## Population Simulation
- Multivariate Gaussian initialization
- Heterogeneous agent generation
- Longitudinal simulation across lifespan
- Population-level trajectory analysis

---

# Technologies Used

- Python
- JAX
- Diffrax
- NumPyro
- NumPy
- SciPy
- Pandas
- Matplotlib
- NHANES datasets

---

# Key Components

## 1. De Gaetano Physiological Model
Implements the system of differential equations governing:
- Glucose regulation
- Insulin dynamics
- Beta-cell decline
- Insulin sensitivity changes

## 2. NHANES Data Processing
Processes:
- Demographics
- Glucose and insulin measurements
- Physical activity data
- Dietary intake data

## 3. Behavioral Trajectory Modeling
Fits age-dependent models for:
- MVPA trends
- Calorie intake trends
- Behavioral variability

## 4. Population Simulation
Creates synthetic populations using:
- Empirical NHANES initialization
- Multivariate sampling
- Vectorized JAX simulation

---

# Example Outputs

The notebooks generates:
- Physiological validation plots
- Renal glucose elimination curves
- Dietary intervention simulations
- Age-binned glucose and insulin statistics
- Behavioral trend visualizations
- Population trajectory simulations

---

# Installation

Install required libraries:

```python
pip install jax jaxlib diffrax numpyro pyreadstat scipy matplotlib pandas
```

---

# Running the Notebook

Open the notebook in Google Colab or Jupyter:

# Data Source

NHANES datasets were used for epidemiological calibration and behavioral modeling.

Source:
- National Health and Nutrition Examination Survey (NHANES)

---

# Research Context

This work was developed as part of a master's research project focused on:
- Computational epidemiology
- Physiological modeling
- Diabetes progression
- Population-level simulation

---

# Author

**Yvonne Amugaga**  
MSc Applied Mathematics  
Óbuda University
