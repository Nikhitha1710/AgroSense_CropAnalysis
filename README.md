# Indian Crop Yield Analysis 🌾

A data analysis notebook exploring what soil and climate conditions suit different crops across India. Built as an extension of my AgroSense project. I wanted to understand the *why* behind the crop recommendations, not just build the system that makes them.

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

## Built By 🙋‍♀️😄

Cheparthi Sri Nikhitha
- [LinkedIn](https://www.linkedin.com/in/cheparthi-sri-nikhitha-886b381b1)
- [Portfolio](https://nikhithaprofessionalportfolio.netlify.app/)
