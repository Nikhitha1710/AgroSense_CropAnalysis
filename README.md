# Indian Crop Yield Analysis 🌾

A data analysis notebook exploring how soil and climate conditions influence crop suitability across India. Built as an extension of AgroSense, this project focuses on understanding the underlying factors behind crop recommendations rather than just generating predictions.

---
## Goal 🎯

The goal of this project is to analyse soil and climate data to understand the relationships between environmental conditions and crop growth using statistical methods and visualisation.

---
## Project Overview 🧩

### **This project focuses on analysing key agricultural features such as:**
- Soil Nutrients: nitrogen (N), phosphorus (P), potassium (K)
- Environmental Factors: pH, temperature, humidity, and rainfall.

The notebook applies statistical techniques and visual exploration to identify patterns, validate relationships, and understand how different crops respond to varying conditions.

---

## Analysis Breakdown 🏗️

### **1. Data Exploration Layer:**
- Loads and inspects the crop recommendation dataset
- Validates dataset structure and checks for missing values
- Generates summary statistics for all features

---

### **2. Visualization Layer:**
- Crop distribution analysis across 22 crop types
- NPK nutrient distribution using histograms
- Rainfall variability using box plots
- Temperature vs humidity scatter plots (grouped by crop type)
- Soil pH distribution using violin plots
- Correlation heatmap for feature relationships

---

### **3. Statistical Analysis Layer:**
- Pearson correlation → relationship between nutrients and rainfall
- Spearman correlation → non-linear relationship between temperature and pH
- Kruskal-Wallis test → rainfall differences across crops
- One-way ANOVA → nitrogen variation across crops

---

### **How the Analysis Works ⚙️**
1. Dataset is loaded and cleaned
2. Features are visualised to identify patterns
3. Statistical tests validate whether observed patterns are significant
4. Insights are derived to explain crop suitability

---

## Project Structure 🧩

```
Crop-Analysis/
├── Indian_Crop_Yield_Analysis.ipynb Main analysis notebook
├── crop_distribution.png Crop distribution plot
├── npk_distributions.png Nutrient histograms
├── npk_by_crop.png Nutrient comparison
├── rainfall_by_crop.png Rainfall boxplots
├── correlation_heatmap.png Feature correlation heatmap
├── temp_humidity_scatter.png Climate clustering
├── ph_violin.png Soil pH distribution

```

---

## Dataset 📊

**Indian Crop Recommendation Dataset**  
Source: Kaggle  

Features:
- Soil Nutrients: Nitrogen (N), Phosphorus (P), Potassium (K)
- Environmental Variables: temperature, humidity, rainfall, pH
- Target Variable: crop label  

Records: 2200 entries across 22 crop types  

---

## How to Run 🚀

### ☁️ On Kaggle (Recommended)
1. Open the dataset page: https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset  
2. Click **New Notebook**  
3. Upload `Indian_Crop_Yield_Analysis.ipynb`  
4. Run all cells  

---

### 💻 Run Locally

```
pip install pandas numpy scipy matplotlib jupyter
jupyter notebook Indian_Crop_Yield_Analysis.ipynb

```
## What this is

I used the Indian Crop Recommendation Dataset from Kaggle (2200 records, 22 crops) to run statistical analysis on soil nutrients, rainfall, temperature, humidity, and pH. The goal was to find patterns that explain why certain crops grow better in certain conditions.

## What is in the notebook

- NPK analysis: how nitrogen, phosphorus, and potassium are distributed across different crops
- Rainfall patterns: box plots showing how much water each crop actually needs
- SciPy stats: Pearson correlation, Spearman correlation, Kruskal-Wallis test, one-way ANOVA
- Correlation heatmap: which soil and climate features move together
- Temperature vs humidity scatter: how crop groups cluster by climate profile
- pH violin plots: soil acidity preferences by crop group

## Tools used

- Python 3
- pandas
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

## How to run it

On Kaggle (easiest):
1. Open the dataset page: kaggle.com/datasets/atharvaingle/crop-recommendation-dataset
2. Click New Notebook
3. Upload Indian_Crop_Yield_Analysis.ipynb
4. Run all cells

Locally:
pip install pandas numpy scipy matplotlib jupyter
jupyter notebook Indian_Crop_Yield_Analysis.ipynb

Change the file path in cell 2 to wherever you saved Crop_recommendation.csv..

## Related Project 🔗📁

This notebook connects to AgroSense, a full stack crop advisory system I built with a C++ data pipeline, Python ML engine, and interactive web dashboard for Indian farmers.

**Check it out:** [AgroSense](github.com/Nikhitha1710/AgroSense) 

---

## Built By 👩‍💻

Cheparthi Sri Nikhitha
- [LinkedIn](https://www.linkedin.com/in/cheparthi-sri-nikhitha-886b381b1)
- [Portfolio](https://nikhithaprofessionalportfolio.netlify.app/)
