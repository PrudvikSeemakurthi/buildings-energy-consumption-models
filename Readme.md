# Predicting Building Energy Consumption

## Brief One Line Summary
A machine learning project to predict building energy consumption using Linear Regression, Decision Tree, and Random Forest models.

## Overview
This project focuses on understanding and predicting how different building features and environmental factors affect energy consumption. By analyzing a dataset from Kaggle, we aimed to identify the most influential factors and build models that can forecast energy usage effectively. The ultimate goal is to help organizations optimize energy usage, reduce costs, and contribute to environmental sustainability.

## Problem Statement
Buildings consume a significant portion of global energy. However, the drivers of energy consumption vary across building types and conditions. The challenge is to predict a building’s energy consumption accurately and determine the key factors influencing it. 

## Dataset
- **Source**: Kaggle (Energy Consumption dataset)  
- **Files**: Train and Test CSV files  
- **Features**: Building characteristics (square footage, occupants, appliances, type) and environmental factors (temperature, climate conditions)  
- **Target**: Energy consumption (kWh)

## Tools and Technologies
- Python  
- Pandas & NumPy (data cleaning and preprocessing)  
- Matplotlib & Seaborn (data visualization)  
- Scikit-learn (machine learning models: Linear Regression, Decision Tree, Random Forest)  
- Jupyter Notebook  

## Methods
1. **Data Cleaning**  
   - Removed spaces from values and column names  
   - Replaced missing values (mean for numerical, dropped rows for categorical)  
   - Dropped duplicates  

2. **Exploratory Data Analysis (EDA)**  
   - Explored relationships between square footage, occupants, appliances, climate, and energy consumption  
   - Visualized energy consumption trends by building type and environmental conditions  

3. **Modeling**  
   - **Linear Regression**: Tested relationship between square footage and energy consumption  
   - **Decision Tree**: Captured feature importance and splits  
   - **Random Forest**: Ensemble method for high accuracy predictions  

## Key Insights
- Industrial buildings are the largest energy consumers, followed by commercial and residential.  
- Square footage shows a strong positive relationship with energy consumption.  
- Buildings with 81–100 occupants consume the most energy on average.  
- More appliances generally increase energy consumption, but usage frequency matters.  
- Temperatures between 31–35°C lead to higher energy usage due to cooling needs.  

## Dashboard / Model / Output
- **Linear Regression**: R² = 0.68  
- **Decision Tree**: R² = 0.816  
- **Random Forest**: R² = 0.981 (best performing model)  

Visualizations (EDA and model outputs) are included in the project files.  

