# Heatmap-Generation
# Data Science Project: Heatmap Generation from Simulated Thermal Data

<img src="https://raw.githubusercontent.com/Rajivjha003/Heatmap-Generation/main/HeatmapImg.png" alt="Heatmap">

## Table of Contents
1. About The Project
2. Getting Started
3. Usage
4. Project Structure
5. Acknowledgments

## About The Project
This project aims to analyze and visualize simulated thermal data. It utilizes Python with NumPy for data generation and Matplotlib for heatmap visualization. The key functionalities include generating random thermal data, normalizing for consistent color mapping, and creating an interactive heatmap with customizable colormaps and optional contour lines for hot areas.

## Getting Started
To get a local copy up and running, follow these steps:

### Prerequisites
- Python 3.7 or later
- pip

### Installation
1. Clone the repo

2. Install required packages

## Usage
To use the project, follow these steps:

```python
# Set the grid size in main.py
grid_size = (100, 100)

# Generate random thermal data
thermal_data = np.random.uniform(low=0, high=100, size=grid_size)

# Generate and display the heatmap
generate_heatmap(thermal_data, cmap='viridis', show_contour=True)

# 📁 Project Structure

The project structure is organized as follows:

- 📂 **project-root/**
  - 📂 **data/**
    - 📄 generated_data
    - 📄 Heatmap-generator.ipynb
  - 📂 **screenshots/**
    - 📄 heatmap.png
  - 📄 requirements.txt
  - 📄 README.md
  - 📄 ...

