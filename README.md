# Predictive-Maintenance-Generator
Predictive maintenance analysis of generator systems using Python

# Predictive Maintenance Analysis of Generator Systems

## Overview
This project analyzes generator operational data using Python to identify key indicators of system failure. The goal is to support predictive maintenance strategies and improve system reliability.

## Dataset
The dataset contains 200 records with the following parameters:
- Load (kW)
- Temperature (°C)
- Vibration
- Downtime (0 = Normal, 1 = Failure)

## Key Findings
- Temperature above 85°C consistently leads to system failure
- Vibration above 7 significantly increases failure risk
- Vibration is the strongest predictor of downtime (correlation = 0.69)
- Load has minimal impact on system failure

## Techniques Used
- Data Cleaning and Analysis (Pandas)
- Data Visualization (Matplotlib, Seaborn)
- Correlation Analysis
- Threshold-Based Fault Detection

## Conclusion
The project demonstrates how data-driven techniques can be used to predict equipment failure and improve maintenance strategies in industrial systems.

## 🧠 Author
Godwin Ehiaguna Imafidon
