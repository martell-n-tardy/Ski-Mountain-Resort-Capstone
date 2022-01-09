![](https://github.com/martell-n-tardy/Ski-Mountain-Resort-Capstone/blob/master/images/WhitefishResort.png)
# Ski Mountain Resort Capstone
An end-to-end project completed for Whitefish Mountain Resort, located at Big Mountain in northwestern Montana. 

The goal of this project was to develop a pricing model for ski resort tickets in Big Mountain's market segment. The deliverable is a predictive model intended to provide guidance for Big Mountain's pricing and future facility investment plans by exploring machine learning models and statistical analysis related to opportunity sizing, targeting, and optimization. 

More information on Whitefish Mountain Resort (a.k.a Big Mountain) can be found here: https://skiwhitefish.com/

## Contents
* **raw_data:** A folder containing the original unedited version of the dataset used for this project in CSV format.
* **data:** A folder containing three files of transformed data saved along the data analysis process to modeling.
* **images:** A folder containing two images. The image "silverton_mountain_info.png" was used for... and the image "Whitefish Resort.png" was used as a banner for this Read Me file. 
* **models:** A folder containing captured models from the modeling stage of this project.
* **Step Two - Data Wrangling:** A folder containing the data wrangling and cleaning code work for this project. This work was completed in Python using a Jupyter notebook.
* **Step Three - Exploratory Data Analysis:** A folder containing the EDA code work for this project. This work was completed in Python using a Jupyter notebook.
* **Step Four - Preprocessing and Training:** A folder containing the preprocessing and training code work for this project. Work completed in Python using a Jupyter notebook.
* **Step Five - Modeling:** A folder containing the modeling code work for this project. Work completed in Python using a Jupyter notebook.
* **Guided Capstone Project Report:** A PDF document detailing the end-to-end analysis and methodology of this projet.
* 
# Project Overview

## Background
Big Mountain suspected it may not be maximizing its returns, relative to its position in the market. They also didn't have a strong sense of what facilities matter most to visitors, particularly which ones vistors are most likely to pay more for. As a result, they made public their situation and asked for insight from any inidustry experts or data scientist who were interested. This project is my response to their business problem.

## Problem Statement
How can "Big Mountain" Resort develop a data-driven business strategy that takes into consideration market segment, various facility values, and current operating costs to deliver the best ticket price while allowing changes that will either cut costs without undermining the ticket price or support an even higher ticket price?

## Tools and Editors
Jupyter Notebook and Anaconda Prompt

## Libraries
NumPy, Pandas, Matplotlib, Seaborn, and Sklearn

## Project Includes
* Problem Identification
* Data Wrangling
  - Handling of missing and NA values
  - Removing duplicate rows
* Exploratory Data Analysis (EDA)
  - exploring co-relation between variables
* Pre-processing, Training Data Development
* Model Development and Selection
  - Linear regression and performance metrics
    - Improve explained variance
    - Reduce Mean Absolute Error
  - KMeans clustering and scatter plots 
    - co-relation coefficients 
    - model performance metrics
* Final Model Selection
Linear Regression model performance was compared to the performance of the Random Forest Regression model. The result was the Random Forest model had a lower cross-validation mean absolute error by almost a $1. It also exhibited less variability and its performance on the test set produced a performance consistent with its cross-validation results. Therefore, the Random Forest Regression model was the model used moving forward for in this project.

Interested in what was the final suggestions for Whitefish Resort?? See Step Five - Modeling for in-depth details or check out the Slide Deck to get a quick overview.
