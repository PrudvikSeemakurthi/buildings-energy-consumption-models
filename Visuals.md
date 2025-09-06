# Project Visuals: Predicting Building Energy Consumption

This file contains the key visualizations used in our project to analyze and predict building energy consumption.

---

## 1. Energy Consumption by Building Type
This graph shows the average energy consumption across **Residential, Commercial, and Industrial** buildings. Industrial buildings use the most energy due to heavy machinery and large-scale operations.

<img width="380" height="236" alt="image" src="https://github.com/user-attachments/assets/9b262b1b-1c35-4dbb-9890-5ef5d0882144" />

---

## 2. Energy Consumption vs. Square Footage
This scatter plot highlights the positive correlation between building size and energy usage. As **square footage increases**, energy consumption generally rises.

<img width="653" height="406" alt="Screenshot 2025-09-06 at 4 04 04 PM" src="https://github.com/user-attachments/assets/86de2ecd-ce11-4fb2-82dc-8a8f5ce567b3" />


---

## 3. Energy Consumption by Number of Occupants
This bar chart illustrates how the number of occupants impacts energy consumption. Buildings with **81–100 occupants** consume the most energy on average.

<img width="405" height="251" alt="image" src="https://github.com/user-attachments/assets/c3223cd6-7112-4e55-97eb-fe55ac5e35c2" />

---

## 4. Energy Consumption vs. Number of Appliances
This line plot shows that more appliances typically lead to higher energy usage. However, the effect also depends on **how frequently the appliances are used**.

<img width="405" height="201" alt="image" src="https://github.com/user-attachments/assets/f4dcb9ba-83e5-4a6b-96f1-d296f1c2b86b" />


---

## 5. Energy Consumption across Temperature Ranges
This box plot demonstrates that energy usage stays fairly consistent across most temperature ranges, but **spikes between 31–35°C** due to higher cooling demands.

<img width="404" height="251" alt="image" src="https://github.com/user-attachments/assets/2c9d5eda-ccb2-450a-9fad-04e09b423f55" />


---

# Machine Learning Models

## Linear Regression Model
The regression line shows how square footage alone predicts energy consumption.  
- For every additional square foot, energy use increases by ~0.05 kWh.  
- The residuals are fairly evenly distributed, showing a reasonable fit

<img width="337" height="285" alt="image" src="https://github.com/user-attachments/assets/f1a81463-4211-4831-90a8-c535c7437b7a" />


<img width="246" height="147" alt="image" src="https://github.com/user-attachments/assets/9b48d3b5-6409-4c57-87ea-352e7e2788c0" />

## Random Forest
The Random Forest model highlights **square footage** as the most important predictor of energy consumption, far outweighing other features.  
- **Number of Occupants** and **Building Type** follow as secondary factors.  
- Features like **appliances used** and **average temperature** contribute but have smaller effects.  

<img width="354" height="188" alt="image" src="https://github.com/user-attachments/assets/af3f7c0c-905f-4f4d-ad2f-799e2d078f5a" />

## Decision Tree
The Decision Tree model also identifies **square footage** as the dominant factor in predicting energy consumption.  
- **Building type** (especially Industrial and Residential) plays a secondary role.  
- **Number of Occupants** and **Appliances Used** contribute moderately.  
- Environmental factors like **average temperature** and **day of week** have very limited impact.  

<img width="329" height="186" alt="image" src="https://github.com/user-attachments/assets/a8178c37-a13d-4419-a785-4524336f8544" />



