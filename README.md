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

| Git & GitHub | Version control and project sharing |

## Project Files

- `Analysis of Zomato's food delivery operations.ipynb` — Complete Jupyter Notebook containing the data preparation, analysis, and visualizations.
- `Zomato_Cleaned_Dataset.csv` — Cleaned dataset prepared for analysis.
- `Zomato_cleaned.csv` — Original dataset used as the source for the analysis.
