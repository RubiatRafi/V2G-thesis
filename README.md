# Optimal Scheduling of V2G Technology and EV Availability Prediction using ML

This project explores the use of Vehicle-to-Grid (V2G) technology in Bangladesh, aiming to optimize the energy scheduling of Electric Vehicles (EVs) and predict their availability using machine learning techniques.


## Features
1. Optimization of V2G Scheduling: Uses Pyomo and the GLPK solver to minimize grid demand fluctuations by optimizing EV charge and discharge times.
2. EV Availability Prediction: Machine learning models, including Random Forest and Gradient Boosting, are trained on real-world data to predict the availability of EVs for grid interaction.
3. Economic and Environmental Impact: The study explores the financial benefits of V2G technology, including revenue from energy transactions and contributions to grid stability while addressing environmental concerns like reducing greenhouse gas emissions.

## Tools and Technologies
1. Pyomo: For formulating and solving the optimization problem.
2. Machine Learning: Random Forest and Gradient Boosting models for predicting EV availability.
3. Data Sources: Historical energy usage data from Dhaka Power Distribution Company (DPDC) and UK National Travel Survey data for EV behavior.

## How to Run
1. Clone this Repository
   ```bash
   git clone https://github.com/RubiatRafi/V2G-Thesis.git
2. Install dependencies
   ```bash
   pip install -r requirements.txt
3. Run Optimization Model
   ```bash
   python optimize_v2g.py
4. Train and test machine learning models for predicting EV availability
   ```bash
    python predict_availability.py

## Results
1. Optimization Results: Significant potential for optimizing grid efficiency and generating profits while maintaining battery health.
2. Prediction Accuracy: Machine learning models achieve over 90% accuracy in predicting EV availability, ensuring reliable V2G scheduling.
