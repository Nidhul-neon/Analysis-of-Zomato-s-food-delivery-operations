# Analysis of Zomato's Food Delivery Operations

A Python-based data analytics project focused on understanding food delivery operations and the factors associated with delivery time.

## Project Overview

This project analyzes Zomato food delivery data to understand variations in delivery time and explore the operational and environmental factors associated with it.

The analysis considers factors such as road traffic conditions, weather conditions, order types, delivery distance, and delivery locations. Python-based data analysis and visualization techniques are used to clean, prepare, analyze, and interpret the dataset.

## Project Objectives

The key objectives of this project are:

- To analyze the overall delivery time of food orders.
- To examine the relationship between road traffic conditions and delivery time.
- To study how weather conditions are associated with delivery time.
- To analyze delivery time across different types of orders.
- To examine the relationship between delivery distance and delivery time.
- To explore how delivery locations are associated with variations in delivery time.
- To identify the key factors that are most closely associated with food delivery time.

## Dataset Description

The project uses a Zomato food delivery dataset containing information related to food orders, delivery operations, environmental conditions, delivery locations, and delivery duration.

The original dataset contains:

- **38,964 records**
- **22 columns**
- Numerical and categorical variables
- Date and time-related variables
- Delivery location coordinates
- Delivery distance and delivery duration information

### Key Data Categories

| Category | Description |
|---|---|
| Delivery Information | Delivery duration, delivery personnel information, and vehicle-related details |
| Location Information | Restaurant and delivery location coordinates, city classification, and delivery distance |
| Environmental Factors | Weather conditions and road traffic density |
| Order Information | Order type and delivery-related information |
| Operational Information | Vehicle condition and multiple deliveries |
| Time Information | Order date and pickup time |

## Data Cleaning and Preprocessing

The dataset was prepared for analysis through a series of data cleaning and preprocessing steps.

The preprocessing included:

- Checking and handling missing values
- Removing unnecessary identifier columns
- Converting date and time columns to appropriate formats
- Standardizing inconsistent categorical values
- Investigating duplicate records
- Detecting potential outliers using the IQR method
- Investigating identified outliers before deciding on treatment
- Creating the `Pickup_Hour` feature from pickup time
- Performing a final data quality check

After preprocessing, the cleaned dataset contains:

- **38,964 records**
- **18 variables**
- **0 missing values**

## Exploratory Data Analysis (EDA)

The exploratory analysis was conducted using univariate, bivariate, and multivariate approaches to identify patterns and relationships associated with food delivery time.

### Univariate Analysis

The analysis examined the distribution and characteristics of individual variables, including:

- Overall delivery-time distribution
- Delivery-speed distribution
- Order-type distribution
- Descriptive statistics of delivery time

### Bivariate Analysis

Relationships between delivery time and individual operational or environmental factors were analyzed, including:

- Road traffic density
- Weather conditions
- Order type
- Delivery distance
- City classification
- Number of multiple deliveries

Statistical summaries, groupby analysis, correlation analysis, and appropriate visualizations were used to examine these relationships.

### Multivariate Analysis

Multiple factors were analyzed together to identify stronger patterns associated with delivery time.

This included:

- Correlation analysis of numerical variables
- Traffic conditions and multiple deliveries
- Geographic regions and average delivery time

### Visualizations

The project includes a variety of visualizations created using Matplotlib, Seaborn, and Plotly, including:

- Histograms
- Bar charts
- Count plots
- Pie charts
- Box plots
- Scatter plots
- Line charts
- Violin plots
- Heatmaps
- Interactive Plotly visualizations

The analysis contains **16 visualization instances** covering different aspects of food delivery operations.


## Tools and Technologies

| Tool / Library | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas | Data manipulation and transformation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Plotly | Interactive visualization |
| Jupyter Notebook | Interactive analysis and documentation |


## Project Files

- `Analysis of Zomato's food delivery operations.ipynb` — Complete Jupyter Notebook containing the data preparation, analysis, and visualizations.
- `Zomato_Cleaned_Dataset.csv` — Cleaned dataset prepared for analysis.
- `Zomato_cleaned.csv` — Original dataset used as the source for the analysis.
