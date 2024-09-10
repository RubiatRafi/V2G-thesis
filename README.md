Optimal Scheduling of V2G Technology and EV Availability Prediction using Machine Learning
This repository contains the implementation and analysis of Vehicle-to-Grid (V2G) technology in Bangladesh. The primary goal is to optimize energy scheduling and predict the availability of Electric Vehicles (EVs) using machine learning techniques.

Key Features:
Optimization of V2G Scheduling: Uses Pyomo and the GLPK solver to minimize grid demand fluctuations by optimizing EV charge and discharge times.
EV Availability Prediction: Machine learning models, including Random Forest and Gradient Boosting, are trained on real-world data to predict the availability of EVs for grid interaction.
Economic and Environmental Impact: The study explores the financial benefits of V2G technology, including revenue from energy transactions and contributions to grid stability while addressing environmental concerns like reducing greenhouse gas emissions.
Tools and Technologies:
Pyomo: For formulating and solving the optimization problem.
Machine Learning: Random Forest and Gradient Boosting models for predicting EV availability.
Data Sources: Historical energy usage data from Dhaka Power Distribution Company (DPDC) and UK National Travel Survey data for EV behavior.
How to Run:
Clone the repository.
Install the required Python packages: pip install -r requirements.txt
Run the optimization model using the script: python optimize_v2g.py
Use the predict_availability.py script to train and test the machine learning models for EV availability.
Results:
Simulations show promising results in optimizing grid efficiency and generating profits while maintaining minimal battery degradation. Predictive models achieve over 90% accuracy in forecasting EV availability, contributing to more reliable V2G scheduling.
