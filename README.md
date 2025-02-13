# EquilibriumPoint 
<p align="center"> <img src="https://assets.papelpop.com/wp-content/uploads/2019/02/Movie-in-the-Park-%E2%80%9CZootopia%E2%80%9D.jpg" alt="Equilibrium Point Cover" width="400"> </p>


## Table of Contents

1. [Introduction](#introduction)  
2. [Requirements](#requirements)  
3. [Installation](#installation)  
4. [How to Use](#how-to-use)  
5. [Concepts and Methodology](#concepts-and-methodology)  
6. [Examples](#examples)  
7. [Contributors](#contributors)  

## Introduction

**EquilibriumPoint** is a project developed in **Jupyter Notebook** that aims to introduce the concept of finding equilibrium points in **linear systems**. The approach adopted emphasizes the crucial role of **eigenvalues** and **eigenvectors** in analyzing and solving dynamic equilibrium problems in these systems.

Linear systems, often described by differential equations or matrix equations, can be represented by matrices whose eigenvalues provide essential information about the **stability** and behavior of their solutions over time. By analyzing eigenvalues, it is possible to identify equilibrium points and understand how the system responds to different initial conditions and external disturbances.

This project explores the relationship between the eigenvalues of matrices associated with linear systems and the concept of equilibrium stability. It provides an **intuitive** and **computational** approach to solving these types of problems in dynamic systems.

Two example applications of this concept are developed to illustrate the algorithm's implementation and usage.

## Requirements

To run the project, you need the following dependencies:

- **Python 3.x**  
- **Jupyter Notebook**  
- **NumPy**  
- **Matplotlib**  

### Installing Dependencies

You can install the required packages using pip:

```bash
pip install numpy matplotlib jupyter
```

## Installation

### Clone the Repository

```bash
git clone https://github.com/lfelipediniz/EquilibriumPoint.git
```

```bash
cd EquilibriumPoint
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the **`equilibrio_sistemas_lineares.ipynb`** file in your browser to begin.

## How to Use

1. **Open the Notebook:**  
   Load the `equilibrio_sistemas_lineares.ipynb` file in Jupyter Notebook.

2. **Run the Cells:**  
   Execute each cell in sequence to follow the explanation, code, and visualizations.

3. **Experiment with Parameters:**  
   Modify the example matrices and parameters to explore different equilibrium points and system behaviors.

## Concepts and Methodology




### Linear Systems and Equilibrium Points

A **linear system** can be described by the matrix equation:

$$
\dot{x} = Ax
$$

**Where**

$$
x \text{ — State vector}
$$

$$
A \text{ — System matrix}
$$

$$
\dot{x} \text{ — Derivative of } x \text{ with respect to time}
$$


The **equilibrium points** occur when:

$$
\dot{x} = 0
$$

This implies:

$$
Ax = 0
$$

### Eigenvalues and Stability

The **eigenvalues** of the system matrix \( A \) determine the stability of the equilibrium point:

- **Stable Equilibrium:** All eigenvalues have negative real parts.  
- **Unstable Equilibrium:** At least one eigenvalue has a positive real part.  
- **Saddle Point:** A mix of positive and negative eigenvalues.

### Methodology

1. **Compute Eigenvalues and Eigenvectors:**  
   Use NumPy to find the eigenvalues and eigenvectors of the system matrix.

2. **Analyze Stability:**  
   Check the real parts of the eigenvalues to determine equilibrium stability.

3. **Visualize Dynamics:**  
   Plot the trajectories of the system to visualize how the system behaves over time.

## Examples

The project includes two examples demonstrating the concept of equilibrium points in linear systems:

1. **Example 1:**  
   Analysis of a simple 2x2 matrix system.

2. **Example 2:**  
   Dynamic equilibrium analysis with perturbations and visualizations.

These examples illustrate how to compute eigenvalues, analyze stability, and visualize system behavior.

## Contributors

- **Luiz Felipe Diniz Costa** - 13782032  
- **João Pedro Alves Notari Godoy** - 14582076  
- **Cauê Paiva Lira** - 14675416  

---

**Happy computing! 📊🔍**

This project was developed as part of the **Linear Algebra and Applications** course. For more information about the course, visit: [Linear Algebra and Applications - USP](https://uspdigital.usp.br/jupiterweb/obterDisciplina?sgldis=SME0142&codcur=55041&codhab=0)

A video presentation of this project is available on YouTube: [Watch the Presentation](https://www.youtube.com/watch?v=ClzYnKqldqw)

---

