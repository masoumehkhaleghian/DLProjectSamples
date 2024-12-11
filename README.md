# DLProjectSamples

A comprehensive collection of deep learning projects demonstrating the implementation and explanation of Sequential and Functional APIs in TensorFlow/Keras. This repository includes practical examples, step-by-step guidance, and insights into designing and training neural networks effectively.

## Table of Contents
- [Overview](#overview)
- [Directory Structure](#directory-structure)
- [Getting Started](#getting-started)
- [Requirements](#requirements)
- [Project Highlights](#project-highlights)
  - [SequentialAPI.ipynb](#sequentialapiipynb)
  - [CrossFunctionalAPI.ipynb](#crossfunctionalapiipynb)
- [Models](#models)
- [Data](#data)

---

## Overview

This repository showcases the application of the two main types of Keras models: Sequential API and Functional API. The projects provide:
- Practical examples to solve real-world problems.
- Visualizations of model architectures.
- Explanations of model design choices.
- Insights into training and evaluation.

## Directory Structure
```
DLProjectSamples/
├── SequentialAPI.ipynb    # Implementation and examples using the Sequential API
├── CrossFunctionalAPI.ipynb  # Implementation and examples using the Functional API
├── Models/                 # Saved model architecture images
├── Data/                   # Datasets used in the examples
├── requirements.yml        # List of required libraries with versions
└── README.md               # Project description and documentation
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/DLProjectSamples.git
   ```
2. Navigate to the project directory:
   ```bash
   cd DLProjectSamples
   ```
3. Create a virtual environment and install dependencies:
   ```bash
   conda env create -f requirements.yml
   conda activate dl-env
   ```
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open `SequentialAPI.ipynb` or `CrossFunctionalAPI.ipynb` to explore the examples.

## Requirements

All required libraries and their versions are specified in the `requirements.yml` file. Ensure you have Conda installed to set up the environment easily.

## Project Highlights

### SequentialAPI.ipynb
This notebook focuses on the **Sequential API**, showcasing how to:
- Build simple and layered neural networks.
- Train models using `model.fit()`.
- Evaluate performance and visualize results.

### CrossFunctionalAPI.ipynb
This notebook dives into the **Functional API**, which allows for greater flexibility in model design, including:
- Creating complex architectures like multi-input or multi-output models.
- Designing residual connections and shared layers.
- Visualizing intricate model designs.

## Models

The `Models/` directory contains images of model architectures created during the projects, generated using TensorFlow's `plot_model` utility. These visualizations make it easy to understand the structure of each neural network.

## Data

The `Data/` directory includes datasets used for training and evaluation in the notebooks. Each dataset is accompanied by a brief description and preprocessing steps.

