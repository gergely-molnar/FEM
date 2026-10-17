# 2D Finite Element Method – Python Implementation

## Introduction

This repository provides a fully functional two-dimensional finite element method (FEM) implementation for solving linear elastic mechanical problems under prescribed displacement (Dirichlet) and applied force (Neumann) boundary conditions.

The implementation is designed for educational purposes, offering a transparent and accessible introduction to the fundamental principles of the finite element method.

## Finite Element Implementation

The code is written in **Python** and provided as an interactive **Jupyter Notebook**.

The implementation includes:

- Two-dimensional linear elasticity under plane-strain conditions.
- Four-node quadrilateral finite elements.
- Numerical integration using Gaussian quadrature.
- Construction of element stiffness matrices and assembly of the global stiffness matrix.
- Implementation of Dirichlet and Neumann boundary conditions.
- Solution of the resulting system of linear equations.
- Calculation of displacement, strain, and stress fields.
- Visualization and interpretation of numerical results.

The implementation emphasizes the mathematical and numerical foundations of the finite element method, allowing students to examine and modify individual steps of the solution procedure.

## Interactive Notebook – JupyterLite

The notebook is made available through **JupyterLite**, an open-source environment that allows users to execute Python code directly in a web browser without installing additional software.

JupyterLite offers several advantages for educational use:

- **No installation required:** The computational environment runs directly in the browser.
- **No registration required:** Students can access and execute the notebook without creating an account.
- **Independent workspaces:** Each student works independently. Modifications do not affect the original repository or other users.
- **Local storage:** Changes are stored in the user's browser and can be retrieved in subsequent sessions, provided the browser data is preserved.
- **Downloadable notebooks:** Students can download their modified notebooks for further use or submission.

This allows students to explore, execute, and modify the finite element implementation independently while preserving the original version.

**JupyterLite documentation:** https://jupyterlite.readthedocs.io/en/stable/

## Educational Objectives

The primary objective is to provide students with a practical understanding of the finite element method by implementing its essential mathematical and numerical operations directly, rather than relying on commercial finite element software.

The notebook is intended to serve as a starting point for further developments, including alternative element formulations, constitutive models, and more complex mechanical problems.
