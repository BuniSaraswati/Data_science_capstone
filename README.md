# SpaceX Falcon 9 First Stage Landing Prediction Capstone

## Overview

In this capstone project, the objective is to predict whether the Falcon 9 first stage will land successfully. SpaceX's ability to reuse the first stage significantly reduces launch costs, making their launches more competitive in the market. Predicting the success of the first stage landing can aid in estimating launch costs, providing valuable information for companies considering bidding against SpaceX for rocket launches.

## Learning Objectives

### Module 1: Data Collection and Wrangling

- Develop Python code to manipulate data in a Pandas data frame.
- Convert a JSON file into a Pandas data frame.
- Create a Jupyter notebook and make it shareable using GitHub.
- Utilize data science methodologies to define and formulate a real-world business problem.

### Module 2: Exploratory Data Analysis (EDA)

- Create scatter plots and bar charts by writing Python code to analyze data in a Pandas data frame.
- Write Python code to conduct exploratory data analysis by manipulating data in a Pandas data frame.
- Create and execute SQL queries to select and sort data.
- Utilize data visualization skills to visualize the data and extract meaningful patterns.

### Module 3: Interactive Dashboard and Map

- Build an interactive dashboard with pie charts and scatter plots using the Plotly Dash Python library.
- Calculate distances on an interactive map using Python code with the Folium library.
- Generate interactive maps, plot coordinates, and mark clusters with the Folium library.

### Module 4: Machine Learning for Prediction

- Split the data into training and testing datasets.
- Train different classification models.
- Optimize Hyperparameters using grid search.
- Utilize machine learning skills to build a predictive model.

## Modules Breakdown

### Module 1: Data Collection and Wrangling

- Collect data on Falcon 9 first-stage landings using RESTful API and web scraping.
- Convert the collected data into a Pandas data frame.
- Perform data wrangling to prepare the data for analysis.

### Module 2: Exploratory Data Analysis (EDA)

- Conduct exploratory data analysis using scatter plots, bar charts, and SQL queries.
- Visualize data to gain insights into Falcon 9 first-stage landings.
- Identify patterns and trends in the data.

### Module 3: Interactive Dashboard and Map

- Build an interactive dashboard with Plotly Dash to analyze launch records.
- Develop an interactive map using Folium to analyze the launch site proximity.
- Visualize data interactively to facilitate exploration.

### Module 4: Machine Learning for Prediction

- Split the dataset into training and testing data.
- Train classification models such as SVM, Classification Trees, and Logistic Regression.
- Optimize model performance through Hyperparameter grid search.
- Evaluate and compare models using test data to determine the most effective method.

## Repository Structure
- dataset/
  - dataset_part_1.csv                # Raw data collected from API and web scraping
  - spacex_web_scraped.csv             # Cleaned and preprocessed data for analysis
  - my_data1.db                        #  This dataset includes a record for each payload carried during a SpaceX mission into outer space.
- notebooks/
  - 01-API-data-collection.ipynb    # Jupyter notebook for data collection using API
  - 02-webscraping.ipynb            # Jupyter notebook for data collection using Beautifulsoup and data cleaning
  - 03-EDA-With_SQL.ipynb           # Jupyter notebook for using SQL queries on the dataset to extract meaningful insights.
  - 04-EDA_Folium.ipynb             # Jupyter notebook for Exploration of SpaceX mission data through interactive maps using Folium in Python.
  - 05-EDA-plotly.ipynb             # Jupyter notebook for Implementation of dynamic visualization features, including launch site selection, success pie chart based on site, payload range selection, and success payload scatter plot.
  - 06_machine_learning.ipynb   # Jupyter notebook for exploratory data analysis, established training labels through class column creation, standardized the data, and performed hyperparameter tuning for SVM, Classification Trees, and Logistic Regression to identify the best-performing method on test data.
 
