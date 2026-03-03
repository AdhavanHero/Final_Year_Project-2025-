# Water Quality Potability Prediction 💧

This repository contains a Jupyter Notebook dedicated to predicting water potability (whether water is safe for human consumption) using machine learning techniques based on various water quality metrics.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Details](#dataset-details)
- [Workflow](#workflow)
- [Setup & Installation](#setup--installation)
- [Model Output](#model-output)

## Project Overview
Access to safe drinking water is a fundamental human right. This machine learning project evaluates chemical and physical properties of water to automate the classification of its potability.

## Dataset Details
The dataset used in this project evaluates water quality across various bodies. Key features analyzed include:
* **ph:** pH level of the water (0 to 14).
* **Hardness:** Capacity of water to precipitate soap (mg/L).
* **Solids:** Total dissolved solids (ppm).
* **Chloramines:** Amount of Chloramines (ppm).
* **Sulfate:** Amount of Sulfates dissolved (mg/L).
* **Conductivity:** Electrical conductivity of water (μS/cm).
* **Organic_carbon:** Amount of organic carbon (ppm).
* **Trihalomethanes:** Amount of Trihalomethanes (μg/L).
* **Turbidity:** Measure of light-emitting property of water (NTU).
* **Potability:** Target variable (1: Potable, 0: Not Potable).

## Workflow
1.  **Data Loading & Initial Exploration:** Using `pandas` to understand the dataset structure and basic statistics.
2.  **Data Preprocessing:** Handling missing values and ensuring data quality.
3.  **Exploratory Data Analysis (EDA):** Utilizing `seaborn` and `matplotlib` to visualize correlations, feature distributions, and outliers.
4.  **Modeling:** Training a Support Vector Machine (SVM) model.
5.  **Export:** Saving the trained SVM model using `joblib` (`Rand.pkl`) for future deployment.

## Setup & Installation

To run this project locally, ensure you have Python installed, and then install the required libraries.

```bash

# Install required dependencies
pip install pandas seaborn matplotlib scikit-learn joblib
