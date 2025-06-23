# 🌱 Carbon Stock Prediction using Ensemble Learning and Remote Sensing (Synthetic Data)

## 📘 Overview

This project demonstrates how ensemble machine learning models (Random Forest and Gradient Boosting) can be used to predict aboveground carbon stock based on synthetic remote sensing and topographic features.

---

## 📂 Dataset

The dataset contains **1,000 synthetic samples** with the following features:

- **Red**: Simulated red reflectance
- **NIR**: Near-infrared reflectance
- **SWIR**: Shortwave infrared reflectance
- **Elevation**: Altitude in meters
- **Slope**: Terrain slope in degrees
- **NDVI**: Normalized Difference Vegetation Index
- **EVI**: Enhanced Vegetation Index  
- **Carbon_Stock**: Simulated aboveground biomass carbon (tons per hectare)

📄 Download the dataset:  
[synthetic_carbon_stock_dataset.xlsx](./synthetic_carbon_stock_dataset.xlsx)

---

## 🔍 Objective

Predict the amount of aboveground carbon stock (in tons/ha) using ensemble regression models trained on multispectral and environmental variables.

---

## ⚙️ Technologies Used

- **Python 3**
- **scikit-learn** for ML modeling
- **NumPy**, **Pandas** for data manipulation
- **Matplotlib** for visualization

---

## 🚀 How to Run

1. Clone this repository or download the code.
2. Install required libraries:
   ```bash
   pip install numpy pandas scikit-learn matplotlib
