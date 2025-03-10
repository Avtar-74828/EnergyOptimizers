# 🌍🔋 **Energy Optimizers** 🚀  

### **Optimizing HVAC Energy Efficiency Using Data Science & Machine Learning**  
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)  
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)](https://pandas.pydata.org/)  
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Random%20Forest%20%7C%20XGBoost-green)](https://scikit-learn.org/)  

---

## **Overview**
**Energy Optimizers** is a data-driven project focused on optimizing **HVAC (Heating, Ventilation, and Air Conditioning) energy consumption** in buildings.  
This project analyzes HVAC efficiency, predicts **Peak Demand Reduction**, and enhances **energy-saving strategies** using statistical methods and machine learning.

---

## **Features**
✔ **Data Preprocessing & Feature Engineering** (Energy Savings %, External Temperature, Building Occupancy)  
✔ **Exploratory Data Analysis (EDA)** (Histograms, Correlation Heatmaps, Boxplots)  
✔ **Statistical Tests** (T-Test, ANOVA) to compare HVAC performance  
✔ **Regression Analysis** to assess the impact of automation on energy efficiency  
✔ **Machine Learning Models (Random Forest, XGBoost)** for predictive analysis  
✔ **Actionable Insights** to improve HVAC efficiency in real-world scenarios  

---

## **Project Structure**
```
EnergyOptimizers/
│── data/                     # Contains the HVAC dataset
│── notebooks/                 # Jupyter Notebooks for analysis
│   │── Group6_EnergyOptimizers.ipynb
│── models/                    # Trained Machine Learning models (if applicable)
│── scripts/                   # Python scripts for processing data & training models
│── README.md                   # Project Documentation
│── requirements.txt            # Required Python libraries
│── LICENSE                     # License information (if applicable)
```

---

## **Installation & Setup**
Follow these steps to set up the project on your local machine.

### **1. Clone the Repository**
```bash
git clone https://github.com/Avtar-74828/EnergyOptimizers.git
cd EnergyOptimizers
```

### **2. Create a Virtual Environment**
#### **For macOS/Linux**
```bash
python -m venv env
source env/bin/activate
```
#### **For Windows**
```bash
python -m venv env
env\Scripts\activate
```

### **3.  Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4. Run Jupyter Notebook**
```bash
jupyter notebook
```

---

## **Data Description**
The dataset includes **pre and post-automation HVAC energy consumption**, **external weather conditions**, and **building occupancy rates**.

| Feature Name                 | Description |
|------------------------------|------------|
| `Pre_Automation_Energy_kWh`  | Energy consumed before automation (kWh) |
| `Post_Automation_Energy_kWh` | Energy consumed after automation (kWh) |
| `HVAC_System_Type`           | Type of HVAC system (Traditional, Upgraded, Smart Automated) |
| `Automation_Efficiency_%`    | Efficiency improvement due to automation (%) |
| `Peak_Demand_Reduction_MW`   | Reduction in peak energy demand (MW) |
| `External_Temperature_C`     | Outside temperature (°C) |
| `Building_Occupancy_%`       | Building occupancy percentage (%) |
| `Energy_Savings_%`           | Percentage of energy saved after automation |

---

## **Key Findings**
**Smart Automated HVAC systems achieve higher Peak Demand Reduction** compared to Traditional HVAC systems.  
**Regression analysis confirms that higher automation efficiency leads to better energy savings.**  
**Feature engineering enhances model performance by including weather & occupancy data.**  
**Machine Learning models (Random Forest & XGBoost) predict Peak Demand Reduction with high accuracy.**  
