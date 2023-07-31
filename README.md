# SIADS-Capstone
This repository contains part of the deliverables for the SIADS-Capstone project of MADS program, at University of Michigan. The project is focused on implementing an AI-driven demand forecasting solution for product lines of small to medium size companies.

## How to run the code
Before starting, make sure that all the Python libraries listed in the "requirements.txt" file are installed in the machine where the code will run.
1. Store the data files (CSV) in a folder called "Data", which resides in the same directory as the Python scripts.
There are in total 5 CSV files expected to be in the "Data" folder: "item_categories.csv", "items.csv", "shops.csv", "sales_train.csv", "test.csv".
All these CSV files can be downloaded from the following link: https://www.kaggle.com/competitions/competitive-data-science-predict-future-sales/data

2. Run the Python script (Jupyter Notebook) called "Part1-DataPreparation.ipynb". This will perform all required data pre-processing, feature engineering, and will output two pickles containing two dataframes with data ready to be analyzed. Before continuing, make sure that both pickle files are stored in the same directory as the Python scripts. 

3. Run the Python script (Jupyter Notebook) called "Part2-ModelTraining.ipynb". This is reading the ready for analysis data (the aforementioned two pickle files), and provides forecasts of demand. 
