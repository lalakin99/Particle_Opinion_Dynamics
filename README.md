# Particle and Opinion Dynamics 
## Network Dynamics and Learning Project 2

## 📜 Project Overview
This repository contains my work for the second individual project in the "Network Dynamics and Learning" course at Politecnico di Torino (2023/2024). This project explores **random walk dynamics**, **opinion dynamics**, and the behavior of open and closed networks.

The main focus areas include:
1. Simulating a particle's movement in a network based on transition rates.
2. Studying French-DeGroot opinion dynamics and convergence to consensus.
3. Investigating particle dynamics in open and closed networks under proportional and fixed-rate assumptions.

---

## 🔍 Problem Breakdown

### **Problem 1: Single Particle Dynamics**
- **Objective**: Simulate the movement of a single particle in a closed network based on a given transition rate matrix and answer key questions:
  - Average return time to a node.
  - Hitting time between nodes.
  - Comparison of simulated and theoretical results.

### **Problem 2: Many Particle Dynamics**
- **Objective**: Simulate particle dynamics from two perspectives:
  - **Particle perspective**: Track individual particles.
  - **Node perspective**: Track the number of particles in each node over time.

### **Problem 3: Open Network Dynamics**
- **Objective**: Simulate particle flow in an open network under:
  - Proportional rates.
  - Fixed rates.
  
---

## 📂 Repository Contents
- **`HW2_Report.pdf`**: Full report with problem descriptions, methods, and results.
- **`HW2_LalAkin.ipynb`**: Jupyter Notebook with Python code for all simulations and visualizations.
  - Transition matrices and parameters used for simulations.

---

## 🛠️ Tools and Techniques
- **Python**:
  - `NumPy`, `SciPy`, `NetworkX`: For matrix operations and graph simulations.
  - `Matplotlib`: For visualizing particle movements and opinion dynamics.
  - `Pandas`: For handling simulation data.
- **Jupyter Notebook**: For presenting code, results, and analysis interactively.

---

## 📊 Results Summary
### Problem 1
- **Return Time**: Simulated vs theoretical average return time comparisons.
- **Hitting Time**: Analysis of discrepancies between simulated and theoretical values.

### Problem 2
- **Particle Perspective**: Average time for 100 particles to return to the starting node.
- **Node Perspective**: Distribution of particles across nodes and comparison with stationary distribution.

### Problem 3
- **Proportional Rates**:
  - Evolution of particles in nodes (visualized as a time series).
- **Fixed Rates**:
  - Steady-state behavior.
