# Project Visuals: Predicting Building Energy Consumption

This file contains the key visualizations used in our project to analyze and predict building energy consumption.

---

## 1. Energy Consumption by Building Type
This graph shows the average energy consumption across **Residential, Commercial, and Industrial** buildings. Industrial buildings use the most energy due to heavy machinery and large-scale operations.

![Energy Consumption by Building Type](visuals/energy_by_building_type.png)

---

## 2. Energy Consumption vs. Square Footage
This scatter plot highlights the positive correlation between building size and energy usage. As **square footage increases**, energy consumption generally rises.
<img width="653" height="406" alt="Screenshot 2025-09-06 at 4 04 04 PM" src="https://github.com/user-attachments/assets/86de2ecd-ce11-4fb2-82dc-8a8f5ce567b3" />




---

## 3. Energy Consumption by Number of Occupants
This bar chart illustrates how the number of occupants impacts energy consumption. Buildings with **81–100 occupants** consume the most energy on average.

![Energy Consumption by Occupants](visuals/energy_by_occupants.png)

---

## 4. Energy Consumption vs. Number of Appliances
This line plot shows that more appliances typically lead to higher energy usage. However, the effect also depends on **how frequently the appliances are used**.

![Energy Consumption vs. Appliances](visuals/energy_vs_appliances.png)

---

## 5. Energy Consumption across Temperature Ranges
This box plot demonstrates that energy usage stays fairly consistent across most temperature ranges, but **spikes between 31–35°C** due to higher cooling demands.

![Energy Consumption vs. Temperature](visuals/energy_vs_temperature.png)

---

## 6. Feature Importance (Random Forest)
This bar chart from the Random Forest model identifies which features contribute most to predicting energy consumption. **Square footage** is by far the most important predictor.

![Feature Importance](visuals/feature_importance.png)

---

## 7. Model Comparison (R² Scores)
This bar chart compares the performance of three models. Random Forest outperformed both Linear Regression and Decision Tree with an **R² score of 0.981**.

![Model Comparison](visuals/model_comparison.png)
