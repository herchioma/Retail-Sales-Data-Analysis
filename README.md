# Retail Sales Data Analysis  
**April 2019 Sales Data – Exploratory Analysis and Insights**

This project conducts an in-depth exploratory data analysis (EDA) on real-world retail sales data to uncover trends, clean anomalies, and prepare the dataset for further insights or machine learning applications. It was developed as part of a data science assignment to practice key preprocessing and analytical skills.

## Table of Contents
- [Project Overview](#project-overview)  
- [Objectives](#objectives)  
- [Key Features](#key-features)  
- [Problem Statement](#problem-statement)  
- [Dataset](#dataset)  
- [Tech Stack](#tech-stack)  
- [Approach](#approach)  
- [Results](#results)  
- [Future Improvements](#future-improvements)  
- [Usage](#usage)  
- [Contributions](#contributions)  
- [References](#references)  

## Project Overview

Retail businesses rely heavily on data to understand customer purchasing patterns, optimize inventory, and make informed decisions. This project analyzes one month of transactional sales data to assess data quality, identify sales trends, and set the groundwork for predictive modeling or business intelligence tasks.

## Objectives

- Clean and preprocess raw sales data for structured analysis  
- Handle missing values, convert datatypes, and remove invalid records  
- Identify key sales trends like popular products, top-performing cities, and peak hours  
- Prepare the dataset for future machine learning applications (e.g., sales prediction)

## Key Features

-  **Data Cleaning & Preprocessing**:  
  Handled missing values, invalid entries, and formatting inconsistencies.

-  **Descriptive Analysis**:  
  Summary statistics and initial insights into sales distribution, order volumes, and pricing.

-  **Time-based Patterns**:  
  Explored how sales vary across different hours and dates to reveal peak shopping times.

-  **Geographic Insights**:  
  Analyzed cities with the highest sales, uncovering location-based performance.

## Problem Statement

Retail companies generate thousands of transactions daily, but raw data is often messy or incomplete. Before meaningful analysis or machine learning can begin, this data must be cleaned, explored, and understood.

This project answers:
- Which products sold the most and when?
- Which cities generated the most revenue?
- What time of day do people tend to buy more?

## Dataset

**Source**: [GitHub - Keith Galli’s Pandas Sales Dataset](https://github.com/KeithGalli/Pandas-Data-Science-Tasks/tree/master/SalesAnalysis/Sales_Data)

**Data Format**: `.csv`  
**Month**: April 2019  
**Key Columns**:
- `Order ID`  
- `Product`  
- `Quantity Ordered`  
- `Price Each`  
- `Order Date`  
- `Purchase Address`

## Tech Stack

**Languages**: Python  
**Libraries**:
- pandas  
- numpy  
- matplotlib  
- seaborn  

## Approach

###  Data Preprocessing
- Removed rows with missing values  
- Converted `Order Date` column to datetime format  
- Extracted useful features (e.g., `Hour`, `City`)  
- Ensured appropriate data types across all columns

###  Exploratory Data Analysis (EDA)
- Identified top-selling products and their sales volumes  
- Discovered peak hours for sales activity  
- Visualized revenue across different cities  
- Calculated total and average sales performance

## Results

- **Most Sold Product**: Identified based on `Quantity Ordered`  
- **Top City by Revenue**: Derived using billing address parsing  
- **Peak Sales Hours**: Around 11 AM and 7 PM, suggesting morning and post-work shopping peaks  
- **High Revenue Correlation**: Between product price and quantity sold

## Future Improvements

- Extend analysis to include data from multiple months  
- Add promotional event data to understand spikes  
- Use machine learning models to forecast future sales  
- Build dashboards (e.g., with Power BI or Tableau) for real-time monitoring

## Usage

To run the notebook:
1. Clone the repository  
2. Install required packages: `pip install pandas matplotlib seaborn`  
3. Run the notebook in Jupyter or JupyterLab

## Contributions

This project was completed by **Chioma Asikaogu** as part of a data science learning journey.

## References

- Dataset: [Sales April 2019 CSV](https://github.com/KeithGalli/Pandas-Data-Science-Tasks)  
- Pandas & Python Documentation  
