# Project Report: Predicting Building Energy Consumption

This report presents the key findings, visuals, and model outputs from our project.

---

## Findings from Data Exploration
- **Industrial buildings** consume the most energy, followed by **Commercial** and then **Residential**.  
- **Square footage** has a strong positive correlation with energy use.  
- Buildings with **81–100 occupants** consume the highest energy on average.  
- **More appliances** lead to more energy usage, but frequency of use also matters.  
- Energy use spikes between **31–35°C** due to cooling needs.  
 

---

## Model Outputs

### Linear Regression
- **R² = 0.68**  
- Square footage explains ~68% of energy consumption variance.  


---

### Decision Tree
- **R² = 0.816**  
- Square footage most important, followed by building type and occupants.  

---

### Random Forest
- **R² = 0.981** (best-performing model)  
- Square footage is the strongest feature, with occupants and building type contributing.  

---

## Summary
- **Square footage** is the dominant predictor of energy consumption.  
- **Random Forest** provided the most accurate results.  
- Results align with real-world expectations and can help organizations improve energy efficiency.  
