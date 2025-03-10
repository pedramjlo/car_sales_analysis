# Introduction
This is my personal data analysis project. I downloaded the dataset from <a href='https://www.kaggle.com/datasets/syedanwarafridi/vehicle-sales-data' >Kaggle</a>. 
this is not an offical real-world project, but solely for the purpose of self-teaching data analysis and practicing my Python skills.


# Techonologies
- Interactive Python Notebook (Jupyter Notebook)
- Pandas
- Plotly for visualisations


# The Pipeline
The initial raw dataset is opened up and read by DataLoader class, column names and respective values are normalised and cleaned using DataCleaner class. DataExploration handles 
query-writing like exploration within the cleaned data, and finally DataCorrelation class engages with finding out correlation between existing independent variables.

1- Checked for data values' types 
2- Normalised values like Brand, Color, Transmission type, US states names
3- Identified the top 10 selling/least profitable cars, brands, states with the highest/lower generated revenue
4- Identified the correlation between multiple variables like the correlation between;
  - selling price and total revenue by state
  - revenue and number of vehicles sold
  - selling price and odometer (distance a car travelled)
  - revenue and car condition
    
