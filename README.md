# On-line Electric Feeder system into city-scale Multimodal Transit Networks

This repository contains a collection of Jupyter Notebook files that simulate and analyze different aspects of a transportation system. The project is organized into four main notebooks:

## 1. Road Network Construction (`01road_network.ipynb`)
This notebook builds and analyzes the road network. It focuses on:
- Constructing the road network infrastructure.
- Analyzing connectivity and structural properties.
- Visualizing the road layout.

## 2. Bus Network Development (`02bus_network.ipynb`)
This notebook generates and examines the bus network based on the road network. It includes:
- Creating bus routes.
- Integrating bus routes with the road network.
- Analyzing the performance of the bus network.

## 3. Demand Modeling (`03demand.ipynb`)
This notebook models transportation demand by simulating passenger flows or trip requests. It helps to:
- Simulate different levels of demand.
- Evaluate the impact on the transportation network.
- Provide data for simulation scenarios.

## 4. System Simulation (`04simulator.ipynb`)
This notebook integrates all components by:
- Combining the road network, bus network, and demand data.
- Running comprehensive simulations of the transportation system.
- Evaluating system performance and identifying potential bottlenecks.

## Project Overview

The goal of this project is to simulate and analyze a complete transportation network. By combining road infrastructure, bus network development, and demand modeling, the project provides insights into the performance of a public transportation system. The simulation results can help identify areas for improvement and assist in planning more efficient transportation networks.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab

### Required Python Packages

- nbformat
- nbconvert
- numpy
- pandas
- matplotlib
- networkx

You can install these packages using pip:

```bash
pip install nbformat nbconvert numpy pandas matplotlib networkx
