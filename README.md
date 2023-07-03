# GameTheory_NLP

This repository contains code for analyzing YouTube data using Python and various libraries such as pandas, seaborn, and matplotlib. The code processes a dataset (`Alldata.csv`) and performs several data analysis tasks.

## Requirements

To run the code in this repository, you need to have the following installed:

- Python (version 3.7 or higher)
- pandas
- seaborn
- matplotlib
- nltk
- scikit-learn

You can install the required Python libraries using pip:
pip install pandas seaborn matplotlib nltk scikit-learn


## Analysis Results

The code performs the following analysis tasks:

- Plots the number of videos published per year.
- Plots the number of videos published per month for each year from 2009 to 2023.
- Plots the average number of views per month.
- Plots the average number of views per month for the years 2012 to 2022.
- Calculates the correlation matrix for various attributes (year, month, day, view count, like count, comment count, duration) and visualizes it using a heatmap.
- Plots the average like count per year.
- Removes videos that don't have scripts and performs data cleaning on the "Game Category" column.
- Preprocesses the text data using tokenization, lemmatization, and removal of stopwords.
- Performs feature extraction using the bag-of-words model.

## Alldata.csv
This data was collected from Youtube API and youtube-transcript-api
