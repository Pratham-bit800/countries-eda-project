# 🌍 Global Countries Socio-Economic Analysis

## About This Project

This is a beginner-level exploratory data analysis (EDA) project built using Python and Pandas.

The goal of this project was to practice data exploration, filtering, sorting, and basic feature engineering using a real-world dataset of 194 countries.

Through this project, I focused on understanding how to structure a proper data analysis notebook and extract meaningful insights from raw data.

---

## Project Objective

To explore global country-level data and answer key questions related to:

- Population distribution
- Democracy scores
- Political leadership data
- Regional classification
- Country naming patterns

Additionally, I implemented a simple feature engineering step to strengthen my understanding of data transformation.

---

## Dataset Information

- 194 countries
- Multiple socio-economic and governance indicators
- Includes:
  - Population
  - Capital city
  - Political leader
  - Democracy score
  - Continent and region
  - Land area

Original dataset file:
Countries.csv

---

## 🔎 Analysis Performed

### 1️. Demographic Analysis
- Identified the country with the highest population
- Identified the country with the lowest population
- Found the second highest populated country and its political leader
- Determined the highest populated country in Africa

### 2️. Political & Governance Analysis
- Top 5 countries based on democracy score
- Count of countries with unknown political leaders
- Countries containing the word "Republic" in their name

### 3️. Regional Analysis
- Total number of regions
- Number of countries in Eastern Europe

### 4️. Feature Engineering
Created a new column:

population_density = population / land_area

This helped me understand how to create derived metrics from existing data.

---

## Processed Dataset

After creating the new `population_density` column, I saved a new dataset:

Countries_with_population_density.csv

This ensures:
- The original dataset remains unchanged
- Feature engineering steps are preserved
- The processed dataset can be reused later

---

## 🛠 Tools Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## What I Learned

- How to explore and inspect datasets
- How to filter and sort data using Pandas
- How to work with missing values
- How to perform basic string operations
- How to structure an EDA notebook professionally
- How to create new features from existing columns
- How to save processed datasets

---

## Future Improvements

As this is a beginner project, I plan to improve it by:

- Adding deeper correlation analysis
- Performing continent-wise aggregated comparisons
- Creating visualizations
- Building predictive models using demographic data

---

## 👨‍💻 Author

Pratham Sindkar
Year: 2026
