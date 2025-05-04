# Wastewater Quality Monitoring with Machine Learning

This project demonstrates the application of machine learning in environmental bioengineering, specifically for predicting wastewater quality indicators such as **COD (Chemical Oxygen Demand)**, **BOD (Biochemical Oxygen Demand)**, and **TSS (Total Suspended Solids)** based on common sensor data.

## Objective

To predict COD, BOD, and TSS values using machine learning models trained on historical/sensor-based input features like:

- Temperature (°C)
- pH
- Turbidity (NTU)
- Dissolved Oxygen (mg/L)
- Conductivity (µS/cm)

## Dataset

A synthetic dataset was generated to simulate real-world wastewater measurements. You’ll find it in `data/wastewater_quality_data.csv`.

## Machine Learning Techniques

- Data cleaning and exploration (pandas, seaborn)
- Regression modeling (Random Forest)
- Evaluation (R² score, Mean Squared Error)
- Feature importance analysis
- Visualizations: Actual vs. Predicted

---

## Results (COD Prediction Sample)

- **R² Score**: ~0.25
- **Top Features**: Turbidity, Conductivity, Temperature

---

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook
