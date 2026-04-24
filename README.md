# Air Pollution and Health Impact Analysis

## Project Overview

This project investigates the relationship between air pollution (**PM2.5 concentration**) and life expectancy using country-level data from two independent public sources.

The analysis combines data cleaning, exploratory data analysis, statistical testing, predictive modeling, and model validation using Python.

---

## Objectives

* Combine air pollution and health datasets
* Explore relationships between pollution and life expectancy
* Quantify associations using statistical methods
* Build predictive models
* Compare model performance using validation techniques

---

## Data Sources

### 1. Air Pollution Data

Source: Our World in Data
PM2.5 dataset: https://ourworldindata.org/grapher/pm25-air-pollution

### 2. Health Data

Source: World Bank
Life expectancy dataset: https://data.worldbank.org/indicator/SP.DYN.LE00.IN

---

## Methods Used

### Data Preparation

* Data cleaning
* Missing value inspection
* Wide-to-long reshaping
* Dataset merging by country and year

### Exploratory Data Analysis

* Scatter plots
* Histograms
* Boxplots
* Time trend analysis

### Statistical Analysis

* Pearson correlation
* Hypothesis testing

### Predictive Modeling

* Simple Linear Regression
* Multiple Linear Regression
* Random Forest Regression

### Validation

* Train/Test Split
* Cross-Validation
* Overfitting analysis

---

## Key Findings

* Higher PM2.5 levels are associated with lower life expectancy.
* Pearson correlation shows a statistically significant negative relationship.
* Multiple Linear Regression provides modest but stable predictive performance.
* Random Forest achieved high training performance but overfit and generalized poorly.
* Simpler models were more reliable for this dataset than more complex models.
* Results reflect association, not causation; confounding variables such as income and healthcare access may partially explain the observed relationship.

---

## Technologies Used

* Python
* pandas
* numpy
* matplotlib
* scipy
* scikit-learn
* Jupyter Notebook

---

## Repository Structure

```text
Air_Pollution_Health_Impact/
│── data/
│── notebooks/
│   └── air_pollution_health_impact_project.ipynb
│── README.md
│── requirements.txt
```

---

## How to Run

1. Clone the repository
2. Navigate to the project folder
3. Install dependencies
4. Open the notebook

```bash
git clone <your-repo-link>
cd Air_Pollution_Health_Impact
pip install -r requirements.txt
jupyter notebook notebooks/air_pollution_health_impact_project.ipynb
```

---

## Final Note

This project was developed as a final exam project for a SoftUni's Data Science with Python course.