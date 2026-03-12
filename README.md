# Netflix Data Analysis Project

## Overview
This project performs Exploratory Data Analysis (EDA) on a Netflix dataset to understand patterns in movies and TV shows available on the platform. The analysis includes data cleaning, handling missing values, column transformation, and visualization of different attributes like country distribution and content types.

The project is implemented using Python libraries commonly used in data science.

## Objectives
- Load and explore the Netflix dataset
- Perform data cleaning and preprocessing
- Handle missing values
- Rename and drop unnecessary columns
- Analyze data using pivot tables
- Perform exploratory data analysis
- Visualize trends using graphs

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
The dataset used in this project contains information about Netflix movies and TV shows including:
- Show ID
- Title
- Director
- Country
- Rating
- Type (Movie/TV Show)
- Description

## Steps Performed

### 1. Import Libraries
Libraries such as Pandas, NumPy, Matplotlib, and Seaborn were imported for data analysis and visualization.

### 2. Load Dataset
The dataset was loaded using Pandas.

```python
df = pd.read_csv('netflix1.csv')
