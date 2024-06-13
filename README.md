# Play_Store_App_Analysis_Using_OpenAI

This project demonstrates data analysis on two datasets: playstore_apps.csv and playstore_reviews.csv. The analysis is performed using a combination of Pandas for data manipulation and LangChain's agent toolkits for natural language querying of the data.

The project involves loading, cleaning, and analyzing two datasets related to Google Play Store apps and their reviews. The primary goals are to understand the structure of the data, handle missing values, remove duplicates, and perform some specific data manipulations. The analysis is driven by natural language queries using the LangChain framework.

## Datasets
playstore_apps.csv: Contains information about various apps available on the Google Play Store.
playstore_reviews.csv: Contains user reviews for the apps listed in the playstore_apps.csv dataset.

## Setup
Clone the repository.
Install the required libraries.
Set up the necessary API key for OpenAI.

## Usage

### Analyzing the Apps Dataset

Load the dataset (playstore_apps.csv) and perform various operations using natural language queries.

Display the top 5 records of the dataframe: Shows the first 5 records to understand the structure and content of the dataset.
Shape of the dataset: Provides the dimensions (rows and columns) of the dataset.
Count missing values in each column: Identifies the number of missing values in each column.
Count duplicate rows: Identifies the number of duplicate rows.
Remove specific columns: Removes the 'Last Updated', 'Current Ver', 'Android Ver', and 'Size' columns.
Remove duplicate rows: Removes any duplicate rows from the dataframe.
Fill missing values: Fills missing values in various columns with appropriate values (mean or specified strings).
Remove rows with specific conditions: Removes rows where the 'Category' column has a value of '1.9'.
Count occurrences of unique values: Counts the occurrences of each unique value in the 'Type' column.
Remove rows with specific conditions: Removes rows where the 'App' column starts with '?'.

### Analyzing the Reviews Dataset

Load the dataset (playstore_reviews.csv) and perform various operations using natural language queries.

Display the top 5 records of the dataframe: Shows the first 5 records to understand the structure and content of the dataset.
Shape of the dataset: Provides the dimensions (rows and columns) of the dataset.
Count missing values in each column: Identifies the number of missing values in each column.
Count duplicate rows: Identifies the number of duplicate rows.
Drop rows with missing values: Removes rows that contain any missing values.
Remove duplicate rows: Removes any duplicate rows from the dataframe.

## Requirements

pandas

openai

langchain

## Project Structure

playstore_apps.csv: The dataset containing information about Google Play Store apps.
playstore_reviews.csv: The dataset containing reviews for the apps.
code.ipynb: The main script that performs data analysis using LangChain agents.

## Acknowledgements
The datasets used in this project are publicly available and can be found on various data repository websites.
LangChain and OpenAI are used for natural language processing and querying of the data.
