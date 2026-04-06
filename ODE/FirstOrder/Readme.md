# First Order Ordinary Differential Equations

## Overview

This section covers first-order ordinary differential equations (ODEs) and their solutions.

## General Form

The general form of a linear first-order ODE is:

$$y' + p(x)y = q(x)$$

Where:
- $y = y(x)$ is the unknown function
- $p(x)$ and $q(x)$ are given functions of $x$

## Solution Methods

### Integrating Factor Method

The solution is given by:

$$y(x) = \frac{1}{\mu(x)}\left[\int \mu(x)q(x)\,dx + C\right]$$

where $\mu(x) = e^{\int p(x)\,dx}$ is the integrating factor.

### Examples in Notebook

1. **Solving $y' + xy = x^2y$** - A linear first-order ODE with variable coefficients

2. **Solving $y' + xy = 0$** - Homogeneous linear first-order ODE

## Requirements

- numpy
- pandas
- sympy
- scipy
- matplotlib

Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Open `FirstOrder.ipynb` in Jupyter to explore the examples and methods for solving first-order ODEs.