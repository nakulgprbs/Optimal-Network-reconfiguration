# Optimal-Network-reconfiguration

# IEEE 33-Bus Network Reconfiguration with Two-Stage Firefly Algorithm and SNG Visualization

Welcome! 🎉  
This project is a **MATLAB implementation** for optimizing the configuration of the **IEEE 33-bus distribution network**.  
It uses a **two-stage Firefly Algorithm (FA)** and features a clear visualization of the network’s **Simplified Network Graph (SNG)**.  

The main goal is to **reduce power losses** and **improve voltage profiles** by finding the best combination of open and closed switches, while keeping the network radial.



## 📌 About the Project
This tool helps **power engineers and researchers** find the best switch settings for the IEEE 33-bus distribution system.  

Process:  
1. **Simplified Network Graph (SNG):** Quickly finds promising solutions.  
2. **Detailed Network Model:** Refines those solutions for the best results.  

All results—power loss, voltage profiles, and switch settings—are clearly displayed with visualizations of the network and optimization progress.



## ✨ Features
- **Two-Stage Firefly Algorithm**
  - Stage 1: Rough optimization on simplified SNG.  
  - Stage 2: Refined optimization on full network.  

- **SNG Visualization**
  - Plots simplified network showing key nodes, edges, and path labels.  

- **IEEE 33-Bus Data Built-In**  
  - Standard bus, branch, and tie-switch data included.  

- **Radiality Enforcement**  
  - Ensures all solutions remain radial (no loops).  

- **Performance Reporting**  
  - Shows power loss, minimum voltage, and loss reduction before/after optimization.  

- **Voltage Profile Plots**  
  - Compares base and optimized cases visually.  



## 🚀 Getting Started

### Prerequisites
- MATLAB

### How It Works
1. **Load Data** – Load bus, branch, and switch data.  
2. **Build & Plot SNG** – Create simplified network graph.  
3. **Stage 1 Optimization** – Run Firefly Algorithm on SNG.  
4. **Stage 2 Optimization** – Refine solution on full network.  
5. **Results** – Print optimized switches, power losses, and plot voltage profiles.  


