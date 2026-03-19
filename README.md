# Traveling Salesman Problem – Multi-Approach Comparison

This repository contains a Jupyter notebook that solves the classic **Traveling Salesman Problem (TSP)** using several different methods and compares their results visually.

## Features

- Generates **random city coordinates** (reproducible with seed)
- Solves TSP with:
  - Nearest Neighbor (greedy heuristic)
  - PuLP + MTZ formulation (exact MILP using GLPK or HiGHS solver)
  - Genetic Algorithm (evolutionary heuristic)
- Visualizes:
  - City locations (scatter plot)
  - Solution quality comparison (bar chart)
- Works on macOS Apple Silicon (M1/M2/M3/M4) with conda environment

## Requirements

- Python 3.11–3.13
- conda (Miniconda or Anaconda recommended)

## Setup

1. **Create and activate the conda environment**

```bash
conda env create -n opt python=3.13
conda activate opt
