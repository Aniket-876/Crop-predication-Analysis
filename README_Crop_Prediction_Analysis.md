# Crop Prediction Analysis using Exploratory Data Analysis

## Project Description

This project focuses on performing Exploratory Data Analysis (EDA) on an Agricultural Crop Yield dataset to understand the major factors affecting crop yield. The dataset includes important agricultural features such as crop name, crop year, season, state, area, production, annual rainfall, fertilizer usage, pesticide usage, and yield.

The main objective of this project is to clean, analyze, and visualize agricultural data to identify crop production patterns, state-wise yield performance, seasonal trends, and relationships between rainfall, fertilizer, pesticide usage, area, production, and crop yield. This analysis helps in understanding agricultural productivity before applying machine learning models for crop prediction.

## Objective

- To analyze crop yield patterns using EDA
- To clean and prepare an unclean agricultural dataset
- To identify missing values, duplicate records, invalid values, and outliers
- To understand the relationship between crop yield and factors like rainfall, fertilizer, pesticide, season, state, and area
- To generate meaningful insights using visualizations and pivot tables

## Dataset Information

The dataset contains agricultural crop-related information with both categorical and numerical features.

### Main Columns

- Crop
- Crop Year
- Season
- State
- Area
- Production
- Annual Rainfall
- Fertilizer
- Pesticide
- Yield

## Tools and Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

### 1. Data Loading

The dataset was loaded into a Jupyter Notebook using Pandas.

### 2. Data Observation

Basic dataset understanding was performed using:

- Shape of dataset
- Data types
- Column names
- Summary statistics
- Unique value count
- Missing value count

### 3. Data Cleaning

Data cleaning steps included:

- Standardizing column names
- Cleaning categorical text values
- Handling missing values
- Removing duplicate records
- Checking and treating invalid negative values

### 4. Missing Value Treatment

- Numerical missing values were handled using median
- Categorical missing values were handled using mode

Median was used for numerical columns because agricultural data may contain outliers, and median is less affected by extreme values.

### 5. Duplicate Value Handling

Duplicate records were identified and removed to avoid biased analysis.

### 6. Invalid Value Treatment

Negative values in columns such as area, production, rainfall, fertilizer, pesticide, and yield were treated because these values are not logically valid in agricultural data.

### 7. Outlier Detection and Treatment

Outliers were detected using boxplots and treated using the IQR capping method.

Capping was used instead of removing records because agricultural data can naturally contain extreme values due to differences in crop type, state, season, and production scale.

### 8. Exploratory Data Analysis

EDA was performed using:

- Univariate Analysis
- Bivariate Analysis
- Multivariate Analysis
- Pivot Tables

## Analysis Performed

### Univariate Analysis

- Top crops by record count
- Season-wise record distribution
- Top states by record count
- Production distribution
- Annual rainfall distribution
- Yield distribution

### Bivariate Analysis

- Annual rainfall vs yield
- Area vs production
- Season vs yield
- Crop vs yield
- State vs yield
- Fertilizer vs yield

### Multivariate Analysis

- Correlation heatmap
- State, season, and yield comparison
- State vs season yield heatmap

### Pivot Table Analysis

- State-wise average yield
- Crop-wise average yield
- Season-wise average yield
- State vs season average yield

## Key Insights

- Crop yield is affected by multiple factors such as crop type, season, state, rainfall, fertilizer usage, pesticide usage, and cultivated area.
- Larger cultivated area generally contributes to higher production.
- Yield varies significantly across different crops, seasons, and states.
- Rainfall may influence yield, but it alone does not fully explain crop productivity.
- Fertilizer and pesticide usage can impact yield, but their effect depends on crop type, soil, rainfall, and farming conditions.
- Pivot tables help identify high-performing crops, states, and seasons.
- EDA is an important step before applying machine learning models for crop prediction.

## Final Conclusion

In this project, an unclean Agricultural Crop Yield dataset was analyzed using complete EDA steps. The dataset was cleaned by handling missing values, duplicate records, invalid values, and outliers. Different visualizations and pivot tables were used to understand crop yield patterns across crops, seasons, and states.

The analysis shows that crop yield depends on multiple agricultural and environmental factors. This project provides a strong foundation for building future crop prediction models or agricultural dashboards.

## Future Scope

- Build a machine learning model to predict crop yield
- Create a Power BI or Tableau dashboard for agricultural insights
- Add soil type, temperature, humidity, and irrigation data for better analysis
- Compare crop productivity across different regions
- Deploy the prediction model using Streamlit or Flask

## How to Run This Project

1. Clone this repository

```bash
git clone https://github.com/your-username/crop-prediction-analysis.git
```

2. Open the project folder

```bash
cd crop-prediction-analysis
```

3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Open Jupyter Notebook

```bash
jupyter notebook
```

5. Run the notebook file step by step.

## Repository Structure

```text
crop-prediction-analysis/
│
├── EDA FINAL CROP PREDICTION ANALYSIS.ipynb
├── dataset/
│   └── unclean_crop_yield.csv
├── README.md
└── images/
    └── visualizations.png
```

## Author

**Aniket Chaudhari**

## Project Type

Exploratory Data Analysis | Data Analytics | Agriculture Analytics | Crop Yield Analysis
