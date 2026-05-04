# Qutrit ZX Spider Fusion Project
This repository contains the code for my final project on qutrit ZX-calculus simplification using Z-spider fusion. The project implements qutrit ZX graph representations using the NetworkX Python library and applies the qutrit Z-spider fusion rule to circuit-derived graph examples.

## Problem Statement
The goal of this project is to test whether qutrit ZX-calculus rewrite rules, specifically Z-spider fusion, produces meaningful diagrammatic reductions for small qutrit circuit families. The project focuses on graph-level reductions such as Z-spider counts, node counts, and edge counts. It also discusses the limitation that diagrammatic reductions do not always directly imply circuit-level resource reductions.

## Main File
The main entry point for the project is: main_results.ipynb. 

Run this notebook from top to bottom to reproduce the main results discussed in the report.

## Repository Contents
- Construction of qutrit ZX graph using NetworkX
- n qutrit QFT(metrics +validation checks)
- Non engtanlging Hamiltonian Trotterization (metrics + convergence check)
- Entangling Hamiltonian Trotterization (metrics + convergence check)
- Redundancy / Negative Control Checks

## Reproducing Results 
To reproduce the main results from the report: 
1. Download this repository
2. Install dependencies using: pip install -r requirements.txt
3. Open the notebook: main_results.ipynb
4. Run all cells from top to bottom in Jupyter Notebook or JupyterLab.

## Data Provenances 
No external datasets are used in this project. All graphs, numerical examples, tables, and plots are generated directly from the code in the notebook.

## Validation Checks
Validation checks are included directly in main_results.ipynb, including graph-structure checks, numerical validation of the Z-spider fusion rule, Trotter convergence checks, and control tests. 
