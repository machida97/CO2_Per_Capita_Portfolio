# CO₂ Emissions Analysis – Per Capita Focus

This project explores **global CO₂ emissions per capita**, analyzing the drivers of per-person emissions and building predictive models to understand key factors influencing them. The project includes both **exploratory data analysis (EDA)** and **modelling**.

---

## 📂 Project Structure
```text
CO2_Per_Capita_Portfolio/ │ ├─ README.md # Project overview and instructions ├─ data/ │ └─ dataset_cleaned.csv # Cleaned dataset for analysis ├─ notebooks/      ├─ CO2_Emissions_EDA_Per_Capita.ipynb # Exploratory Data Analysis      └─ CO2_Per_Capita_Modeling.ipynb # Modelling and feature importance
```

---

## 📊 Data Source

The dataset is compiled from publicly available sources on global CO₂ emissions, energy consumption, and greenhouse gases. Key sources include:

- [Our World in Data – CO₂ and Greenhouse Gas Emissions](https://ourworldindata.org/co2-and-other-greenhouse-gas-emissions)  

The data has been cleaned and processed to focus on **per-capita metrics**.

---

## 🔑 Key Highlights

- **EDA Findings:**  
  CO₂ per capita varies widely across countries; higher per-capita emissions correlate strongly with energy consumption per person.  

- **Modelling Approach:**  
  Applied linear regression, Ridge, and tree-based methods (Random Forest, Gradient Boosting).  

- **Feature Importance:**  
  Energy per capita is the **dominant predictor**. GDP, population, and sectoral breakdowns add little predictive value once energy use per person is included.  

- **Simplified Model:**  
  A single-feature linear model using only **energy per capita** explains the majority of variance in per-capita CO₂, offering clarity and interpretability.  

---

## 🚀 Next Steps

- Explore regional models (e.g., OECD vs non-OECD).  
- Incorporate **energy mix** (renewables vs fossil fuels) for deeper policy insights.  
- Run **scenario analysis** to project emissions under different energy-use pathways.  

---





