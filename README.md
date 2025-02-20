# Uber-Data-Analysis

Overview
This project analyzes an Uber dataset using Python, focusing on data preprocessing, exploration, and visualization. The dataset is cleaned, processed, and visualized using Pandas, NumPy, Matplotlib, and Seaborn.

****Data Preprocessing******
Loaded the dataset using pandas.read_csv()
Checked dataset shape and information
Filled missing values in the PURPOSE column with "NOT"
Converted START_DATE and END_DATE to datetime format
Created new columns:
DATE: Extracted date from START_DATE
TIME: Extracted hour from START_DATE
DAY_NIGHT: Categorized TIME into Morning, Afternoon, Evening, and Night
Dropped null values

****Data Visualization*****
Count plots for CATEGORY, PURPOSE, and DAY_NIGHT
Line plot to visualize monthly trends in miles traveled
Bar plot to analyze Uber rides per weekday
Box plot and distribution plot to explore mileage patterns

****How to Run*****
Clone the repository
Install required libraries: pip install pandas, numpy, matplotlib, seaborn
Run the Python script to analyze and visualize the dataset

