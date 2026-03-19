# Traveling Salesman Problem – Multiple Approaches + Route Visualization

This project implements and compares several methods for solving the **classic Traveling Salesman Problem (TSP)** in a Jupyter notebook.

## Features

- Random city coordinate generation (reproducible via seed)
- Solves TSP using:
  - **Nearest Neighbor** (fast greedy heuristic)
  - **PuLP** + MTZ formulation (exact Mixed-Integer Linear Programming)
  - **Genetic Algorithm** (population-based metaheuristic)
- Visualizes the **actual traveled path** for each method:
  - Matplotlib plots with directional arrows, highlighted start point, city labels
  - Clear distance annotation on each route plot
- Final comparison bar chart of solution qualities

Tested and working on **macOS Apple Silicon** (M-series) using a conda environment named `opt`.

## Requirements

- Python 3.11–3.13
- conda (Miniconda or Anaconda recommended)

## Setup Instructions

1. **Create and activate the conda environment**

   ```bash
   conda create -n opt python=3.13 -y
   conda activate opt
