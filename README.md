# Earthquake_Prediction

Earthquake Prediction Program README

This program is designed to read earthquake data from a CSV file, preprocess the data, create a Basemap plot to visualize affected areas, and split the data into training and testing sets for earthquake magnitude and depth prediction. Below is a guide on how to use this program.
Prerequisites

Dataset: https://www.kaggle.com/datasets/usgs/earthquake-database

Before running the program, you need to have the following Python libraries installed:

    numpy
    pandas
    matplotlib
    mpl_toolkits.basemap
    scikit-learn

You can install the required packages using pip:

bash

pip install basemap

Usage

    Clone or download the CSV dataset from the provided dataset link: USGS Earthquake Database.

    Save the downloaded dataset as database.csv in the same directory as your Python script.

    Run the Python script provided in your project.

python

python your_script_name.py

Program Flow

The program performs the following steps:

    Reads the earthquake data from the CSV file database.csv.

    Selects relevant columns from the dataset, including earthquake magnitude, date-time, latitude, longitude, depth, and other attributes.

    Converts the date-time to a Unix timestamp and creates separate DataFrames for features (X) and targets (y).

    Generates a Basemap plot to visualize affected areas on a world map. The most frequently earthquaked places are highlighted in red, while others are shown in blue.

    Splits the data into training and testing sets for machine learning model development.

    Prints the shapes of the training and testing data splits.

Output

The program will display a Basemap plot showing affected earthquake areas and print the shapes of the training and testing data splits, providing information about the dimensions of the data used for modeling.
Important Notes

    Ensure that you have the necessary Python packages installed as mentioned in the prerequisites section.

    The program uses the Basemap library for geographical visualization, which may require additional setup and configuration, depending on your Python environment.

    The dataset file database.csv should be in the same directory as your Python script for the program to read it successfully.

    Customize the script as needed for your specific analysis or modeling tasks.

Dataset Source

The dataset used in this program can be found at the following link:

Kaggle-Earthquake Database

This program was created by Jai Prakash.R You can contact the author at jaiprakash292033@gmail.com. for any inquiries or feedback.

Feel free to modify, improve, and expand upon this program to meet your specific needs or explore different earthquake prediction approaches.
