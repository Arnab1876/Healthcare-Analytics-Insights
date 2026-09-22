# 🏥 Healthcare Analytics & Insights

A healthcare data analytics project focused on exploring patient health indicators, identifying meaningful patterns, and generating data-driven insights using **Python, Pandas, Machine Learning, and Tableau**.

The project covers healthcare data preprocessing, feature engineering, exploratory data analysis, health-risk classification, and interactive visualization of COVID-19 trends across India.

---

## 📌 Project Overview

Healthcare datasets contain valuable information about patient characteristics, health indicators, disease outcomes, and population-level trends. However, raw healthcare data often requires cleaning, transformation, and structured analysis before meaningful insights can be obtained.

This project applies a step-by-step analytics workflow to healthcare datasets:

**Raw Healthcare Data → Data Cleaning → Feature Engineering → Exploratory Analysis → Machine Learning → Visualization → Insights**

The project includes patient-level health analysis as well as a Tableau-based COVID-19 analysis dashboard.

---

## 🎯 Objectives

- Clean and prepare healthcare datasets for analysis.
- Explore relationships between demographic and health-related variables.
- Create meaningful analytical features such as BMI and overweight indicators.
- Normalize categorical health-risk variables for easier analysis.
- Apply Machine Learning to classify the presence of heart disease.
- Identify important patterns and relationships within patient health data.
- Build an interactive Tableau dashboard to analyze COVID-19 trends across Indian states.
- Communicate healthcare insights through clear visualizations and data-driven analysis.

---

## 🛠️ Technologies Used

### Programming & Data Analysis
- Python
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn
- Tableau

### Machine Learning
- Scikit-learn

### Development Environment
- Jupyter Notebook
- Google Colab

---

# 📊 Project Components

## 1. Healthcare Data Analysis

The project begins with exploratory analysis of healthcare data to understand the structure, quality, and distribution of different patient health indicators.

The analysis includes:

- Understanding dataset dimensions and data types
- Checking missing and inconsistent values
- Exploring numerical and categorical variables
- Examining patient demographics
- Identifying patterns in health-related variables
- Using statistical summaries and visualizations to understand the dataset

---

## 2. BMI & Overweight Analysis

BMI is calculated using height and weight to create an additional health-related feature.

### BMI Formula

\[
BMI = \frac{Weight\ (kg)}{Height\ (m)^2}
\]

A new `bmi` feature is created from the available height and weight variables.

An `overweight` indicator is then generated to classify individuals based on their BMI.

This feature helps simplify the analysis of weight-related health conditions and allows BMI-related patterns to be compared with other health indicators.

---

## 3. Cholesterol & Glucose Data Normalization

Healthcare variables such as cholesterol and glucose are transformed into simplified binary indicators to make them easier to analyze.

### Transformation Logic

| Original Value | Normalized Value | Interpretation |
|---|---:|---|
| 1 | 0 | Good / Normal |
| >1 | 1 | Elevated / Risk |

This transformation is applied to the relevant cholesterol and glucose variables to create consistent binary health-risk indicators.

The normalized variables can then be used more effectively during exploratory analysis and Machine Learning.

---

## 4. ❤️ Heart Disease Prediction

Machine Learning is applied to healthcare data to classify whether a person is likely to have heart disease.

The analysis considers health-related variables such as:

- Age
- Gender
- Height
- Weight
- Blood pressure
- Cholesterol
- Glucose
- Smoking
- Alcohol consumption
- Physical activity

### Objective

The goal is to identify patterns within patient health data and build a classification model that can distinguish between individuals with and without heart disease.

The workflow includes:

**Data Preparation → Feature Engineering → Exploratory Analysis → Model Preparation → Classification → Evaluation**

The Machine Learning component demonstrates how healthcare data can be transformed into a structured classification problem.

> **Note:** This project is intended for educational and analytical purposes and is not designed to provide medical diagnosis or clinical recommendations.

---

# 📈 Exploratory Data Analysis

The project uses Python visualization libraries to explore relationships between different healthcare variables.

Examples of analysis include:

- Age and health-condition relationships
- BMI and overweight patterns
- Blood pressure analysis
- Cholesterol and glucose distributions
- Lifestyle factors such as smoking, alcohol consumption, and physical activity
- Relationships between health indicators and heart disease outcomes

Visualizations are used to make patterns and relationships easier to interpret.

---

# 🦠 5. COVID-19 Analysis of India — Tableau Dashboard

A separate Tableau analysis focuses on the spread of COVID-19 across India.

The dashboard provides an interactive view of:

- State/Union Territory-wise confirmed cases
- Cured patients
- Total deaths
- Maximum confirmed cases
- Trends in confirmed cases over time
- Geographic distribution of COVID-19 cases

### Dashboard Features

- 🗺️ State-wise COVID-19 map
- 📈 Confirmed-case trend analysis
- 📊 Top states by confirmed cases
- 📊 Top states by recovered patients
- 📊 Top states by deaths
- 🔎 Interactive visual analysis

The geographic visualization uses color intensity to represent differences in confirmed cases across Indian states, making regional patterns easier to identify.

---

# 🔄 Analytical Workflow

```text
Healthcare Dataset
        ↓
Data Understanding
        ↓
Data Cleaning & Validation
        ↓
Feature Engineering
        ↓
Exploratory Data Analysis
        ↓
Health Indicator Analysis
        ↓
Machine Learning Classification
        ↓
Model Evaluation
        ↓
Tableau Visualization
        ↓
Healthcare Insights


📂 Project Structure
HealthCare-Analytics-Projects/
│
├── Diabetes/
│   └── Diabetes Analysis Notebook
│
├── Heart Disease/
│   └── Heart Disease Prediction Notebook
│
├── COVID-19/
│   ├── COVID-19 Analysis
│   └── Tableau Dashboard
│
├── Dataset/
│   └── Healthcare Datasets
│
└── README.md

📌 Key Takeaways
The project demonstrates an end-to-end approach to working with healthcare data, and creating meaningful analytical features to identifying patterns and communicating findings through visualizations.
It also demonstrates how healthcare data can be used for both:
- Patient-level analytical problems, such as health-risk and heart-disease classification.
- Population-level analysis, such as understanding COVID-19 trends and regional differences across India.
