# Supply Chain Optimization with Time Series on Agricultural Commodities
# Overview

Welcome to the repository for my supply chain optimization project focusing on agricultural commodities. This project aims to leverage time series analysis and optimization techniques to enhance the efficiency of the agricultural supply chain.

# Table of Contents

Introduction
Objective
Data
Exploratory Data Analysis (EDA)
Data Preprocessing
Feature Engineering
Time Series Analysis
Optimization Model
Results
Conclusion
Introduction
The agricultural sector faces numerous challenges related to supply chain management, and this project aims to address them through a data-driven approach. By combining time series analysis and optimization techniques, we seek to optimize various aspects of the agricultural supply chain.

# Objective

The primary objective of this project is to optimize the agricultural supply chain by forecasting demand, identifying optimal inventory levels, and streamlining logistics and distribution processes.

# Data

This dataset delivers an extensive and current assortment of futures related to soft commodities. Futures are financial contracts obligating the buyer to purchase, and the seller to sell, a specified amount of a particular commodity at a predetermined price on a set date in the future.

# Exploratory Data Analysis (EDA)

Implemented STL Decomposition, Correlation matrix, bar plots, scatter plots etc to analyze and study various characteristics in the data.

# Data Preprocessing

Did outlier detection and removal through IQR. Scaled the data with MinMax for LSTM and applied necesssary transformations.

# Feature Engineering

Performed feature selection and coefficient importance with LASSO and Random Forest to analyze most crucial features

# Time Series Analysis

Explain the time series analysis techniques applied to forecast demand for agricultural commodities. Discuss the chosen models, their architectures, and the training process.

# Models used
Utlized the power of ARIMA, SARIMAX AND LSTM models for the best accuracy and forecasting prices for the future periods, as well as performed supply chain analysis and demand projection with the same.

# Results
Commodities Random Length Lumber followed by Coffee, Cotton and orange juice, sugar excelled in projecting the highest demand. For price forecasting, LSTM and SARIMAX proved as the most accurate model

# Conclusion

1. Demand Forecasting: The time series analysis performed on historical consumption patterns of agricultural commodities has provided valuable insights into demand patterns. Leveraging models like SARIMAX and LSTM, we achieved accurate demand forecasts, crucial for effective supply chain planning.

2. Feature Engineering: In-depth feature engineering allowed us to extract meaningful information from the dataset. Features such as population growth, economic indicators, and historical consumption patterns were integrated to enhance the predictive capabilities of our models.

3. Supply Chain Analysis: From analyzing correlations between each features for the commodities, to applying STL Decomposition for gaining insights into the trends, seasonal and residual components and forecasting its future costs by using LSTM , the model contributes to a more efficient and cost-effective supply chain.

4. Demand Projection: The incorporation of demand projection through LSTM, and feature scaling for the next future periods through appropriate hyperparameter tuning and various model parameters, ensures the robustness and stability of our models.This is crucial for reliable predictions and optimization results, especially when dealing with dynamic agricultural markets. The most demand is being projected by Random Length Lumber, followed by Coffee, Cotton Sugar and Orange Juice

5. Future Work: While this project has achieved significant milestones, there are opportunities for future enhancements. Exploring additional features, experimenting with different deep learning architectures, and refining the optimization model can further improve the overall performance of the supply chain.

In summary, the synergy of time series analysis and optimization models presented in this project equips stakeholders in the agricultural sector with powerful tools to make informed decisions, minimize costs, and enhance the overall efficiency of the supply chain.

# Usage Environment Setup:

Ensure the required dependencies are installed using requirements.txt. Python version: 3.x 

# Future Work 
Future iterations of the project may involve:

Feature engineering for improved model performance. Hyperparameter tuning for optimizing algorithms. Integration of external data factors like economic indicators, waether fluctuations etc that contribute to the agricultural chain, data sources for enhanced predictive capabilities.

# Acknowledgments 

This project is developed as part of [Msc Data Science] course at NMIMS University.

Feel free to adjust the sections, add more details, or modify as needed to fit your specific project details and preferences
