SpaceX Falcon 9 Landing Prediction Project

This repository contains the code and notebooks used for the SpaceX Falcon 9 Landing Prediction project. The project is part of a data science capstone, aiming to predict the landing outcome of Falcon 9 rockets using various machine learning models.

Project Structure


DataCollection_API.ipynb: Jupyter notebook demonstrating how to collect data using the SpaceX API. This notebook fetches data on Falcon 9 launches.

DataCollection_Scraping.ipynb: Jupyter notebook for web scraping data from Wikipedia. The notebook extracts additional launch data not available via the API.

SpaceX_Data_Wrangling.ipynb: This notebook handles the data wrangling process, including cleaning, transforming, and preparing the data for further analysis.

SpaceX_EDA_SQL.ipynb: Jupyter notebook where exploratory data analysis (EDA) is performed using SQL queries. The data is analyzed to uncover patterns and insights.

SpaceXEDA_Visualisation.ipynb: This notebook visualizes the data using various Python libraries, helping to identify trends and relationships in the dataset.

SpaceX_Interactive_Map.ipynb: This notebook creates an interactive map using Folium to visualize the launch sites and landing outcomes of Falcon 9 rockets.

SpaceX_Predictive_Analysis.ipynb: The core notebook of the project, where predictive models are built to forecast the landing outcome of Falcon 9 rockets. Multiple machine learning algorithms are employed, including Logistic Regression, Support Vector Machine, Decision Tree, and K-Nearest Neighbors.

spacex_dash_app.py: Python script for the Dash web application that provides an interactive dashboard to visualize and interact with the Falcon 9 launch data.

spacex_launch_dash.csv: The dataset used throughout the project, containing detailed information on SpaceX launches.

Predictive Model Performance
The accuracy scores for the models are as follows:

Logistic Regression: 83.33%
Support Vector Machine: 83.33%
Decision Tree: 83.33%
K-Nearest Neighbors: 77.78%
