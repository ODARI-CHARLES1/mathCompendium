# Elementary Algebra Notebook

## Overview

This notebook is designed to provide a structured introduction to elementary algebra concepts. It focuses on building a strong foundation in mathematical reasoning, symbolic manipulation, and problem-solving techniques that are essential for engineering, data science, and applied mathematics.

The content is implemented using Python-based tools such as `SymPy`, `NumPy`, and `Matplotlib` to support symbolic computation and visualization.

---

## Objectives

* Understand and manipulate algebraic expressions
* Solve linear and quadratic equations
* Work with functions and graphing
* Apply algebra to engineering problems
* Build computational thinking using Python

---

## Topics Covered

### 1. Basic Algebraic Expressions

* Variables and constants
* Simplification of expressions
* Substitution

### 2. Linear Equations

* Solving single-variable equations
* Applications in real-world systems
* Graphing linear functions

### 3. Simultaneous Equations

* Substitution method
* Elimination method
* Matrix representation (intro)

### 4. Quadratic Equations

* Factorization method
* Quadratic formula
* Nature of roots

### 5. Functions

* Function notation
* Domain and range
* Basic transformations

### 6. Inequalities

* Linear inequalities
* Graphical representation
* Interval notation

### 7. Polynomials

* Addition and multiplication
* Factor theorem (intro)
* Roots and coefficients

---

## Tools Used

* Python 3.x
* SymPy (symbolic algebra)
* NumPy (numerical computation)
* Matplotlib (graphing)

---

## Example Usage

```python
from sympy import symbols, Eq, solve

x = symbols('x')
equation = Eq(2*x + 3, 11)
solution = solve(equation, x)

print(solution)
```

---

## Applications in Engineering

* Circuit analysis (Ohm’s Law, KVL, KCL)
* Signal processing basics
* Control systems modeling
* Data fitting and regression
* System optimization

---

## Learning Outcome

By the end of this notebook, you should be able to:

* Translate real-world problems into algebraic form
* Solve equations analytically and computationally
* Visualize mathematical relationships
* Apply algebra in engineering contexts

---

## Future Extensions

* Matrices and linear algebra
* Differential equations
* Laplace transforms
* Fourier analysis

---

## Author

Created for structured learning in engineering mathematics and computational problem-solving.
