# 🧮 CSE330: Numerical Methods

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/Library-NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

> **Overview:** This repository hosts the laboratory implementations for the CSE330 Numerical Methods course. It focuses on algorithmic approaches to solving mathematical problems, including root finding, interpolation, numerical differentiation, and integration, implemented in Python.

---

## 📑 Table of Contents

* [🛠️ Tech Stack](#-tech-stack)
* [📂 Lab Summaries](#-lab-summaries)
    * [Lab 1: Introduction & Error Analysis](#lab-1-introduction--error-analysis)
    * [Lab 2: Roots of Equations](#lab-2-roots-of-equations)
    * [Lab 3: Linear Algebra & Matrices](#lab-3-linear-algebra--matrices)
    * [Lab 4: Interpolation Methods](#lab-4-interpolation-methods)
    * [Lab 5: Numerical Differentiation](#lab-5-numerical-differentiation)
    * [Lab 6: Numerical Integration](#lab-6-numerical-integration)
    * [Lab 7: Ordinary Differential Equations](#lab-7-ordinary-differential-equations)
* [📈 Key Algorithms](#-key-algorithms)
* [🚀 Getting Started](#-getting-started)

---

## 🛠️ Tech Stack

The core technologies used for these numerical simulations:

| Library | Purpose |
| :--- | :--- |
| **NumPy** | High-performance array manipulations and mathematical functions. |
| **Matplotlib** | Visualizing functions, error rates, and convergence graphs. |
| **Pandas** | Tabulating results and error analysis frames. |
| **SciPy** | Advanced scientific computing tools (optional reference). |

---

## 📂 Lab Summaries

### Lab 1: Introduction & Error Analysis
**Focus:** Understanding floating-point arithmetic and numerical errors.
* **Topics:**
    * Binary representation of numbers.
    * Absolute, Relative, and Round-off errors.
    * Machine Epsilon ($\epsilon$).

### Lab 2: Roots of Equations
**Focus:** Iterative methods to find roots of non-linear equations.
* **Methods:**
    * **Bisection Method:** Bracketing method for guaranteed convergence.
    * **Newton-Raphson Method:** Fast convergence using derivatives.
    * **False Position (Regula Falsi):** Improvement on Bisection.

### Lab 3: Linear Algebra & Matrices
**Focus:** Solving systems of linear equations ($Ax = B$).
* **Methods:**
    * **Gaussian Elimination:** Row reduction techniques.
    * **LU Decomposition:** Factorizing matrices into Lower and Upper parts.
    * **Gaussian Seidel:** Iterative method for solving linear systems.

### Lab 4: Interpolation Methods
**Focus:** Constructing new data points within the range of a discrete set of known data points.
* **Methods:**
    * **Lagrange Interpolation:** Polynomial fitting using basis polynomials.
    * **Newton’s Divided Difference:** Efficient recursive method for polynomial construction.

### Lab 5: Numerical Differentiation
**Focus:** Approximating derivatives using finite difference formulas.
* **Formulas:**
    * **Forward Difference:** $f'(x) \approx \frac{f(x+h) - f(x)}{h}$
    * **Backward Difference:** Uses previous points.
    * **Central Difference:** Most accurate ($O(h^2)$).
    * **Richardson Extrapolation:** Improving accuracy by combining estimates.

### Lab 6: Numerical Integration
**Focus:** Computing definite integrals numerically.
* **Methods:**
    * **Trapezoidal Rule:** Linear approximation under the curve.
    * **Simpson’s 1/3 Rule:** Quadratic approximation (Parabolic arcs).

### Lab 7: Ordinary Differential Equations
**Focus:** Solving ODEs to simulate dynamic systems.
* **Methods:**
    * **Euler’s Method:** Basic explicit method.
    * **Midpoint Method:** Improved slope estimation.
    * **Runge-Kutta (RK4):** The industry standard for high accuracy.

---

## 📈 Key Algorithms

Here is a quick reference to the complexity and convergence of methods covered:

| Algorithm | Type | Convergence / Order |
| :--- | :--- | :--- |
| **Bisection** | Root Finding | Linear (Slow but Safe) |
| **Newton-Raphson** | Root Finding | Quadratic (Fast) |
| **Gaussian Elimination** | Linear Algebra | $O(n^3)$ |
| **Simpson's 1/3** | Integration | $O(h^4)$ |
| **Runge-Kutta 4** | ODE Solving | $O(h^4)$ |

---

## 🚀 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/shafin027/CSE330_Numerical-Methods.git](https://github.com/shafin027/CSE330_Numerical-Methods.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install numpy matplotlib pandas
    ```
3.  **Run Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

---

<div align="center">

**CSE330 Numerical Methods** | Maintained by [Shafin027](https://github.com/shafin027)

</div>
