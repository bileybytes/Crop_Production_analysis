# Crop Production Data Analysis

## Introduction

The agriculture business domain, as a vital part of the overall supply chain, is expected to evolve significantly in the coming years through developments, particularly in the realm of the Future Internet. This analysis presents a novel Business-to-Business collaboration platform from the agri-food sector perspective, aiming to facilitate effective and flexible collaboration among numerous stakeholders from associated business domains. The dataset provides extensive information on crop production in India over several years. The ultimate goal of this analysis is to predict crop production and extract important insights, highlighting key indicators and metrics that influence crop production.

## Data Overview

- **Dataset Name**: Crop Production data.csv
- **Number of Rows**: 246,091
- **Number of Columns**: 7
- **Missing Values**: Present in the 'Production' column
- **Column Data Types**:
  - Object: 4 columns
  - Integer: 1 column
  - Float: 2 columns

## Analysis Process

1. **Data Inspection**:
   - Checked the shape of the dataset.
   - Identified null values and verified data types.

2. **Data Preprocessing**:
   - Filled the null values in numerical columns with mean values.
   - Created two new columns: 'Category of Area' and 'Production Category'.

3. **Data Analysis**:
   - Conducted Univariate, Bivariate, and Multivariate Analysis.

## Exploratory Data Analysis (EDA)

- **Tools and Libraries**:
  - **Pandas** and **NumPy**: For data manipulation and mathematical calculations.
  - **Seaborn** and **Matplotlib**: For creating graphs and charts.

- **Visualization Techniques**:
  - Multiple graphs and charts, including bar plots, histograms, scatter plots, and more, were created to explore and visualize the data.

## Note

All operations and analyses were conducted in Python using Jupyter Notebook.
