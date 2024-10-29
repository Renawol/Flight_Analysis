# Indian Airlines Prices Data Cleaning and Analysis

<p align="center">
<img src="https://imgur.com/1Ddm2hM.jpg" style="height: 75%; width:75%;"/></center></p>


In this proyect we use Python data cleaning and analysis tools in a [**Jupyter Notebook**](https://github.com/Renawol/Flight_Analysis/blob/main/flight_project.ipynb). 
The data was taken of [this Kaggle dataset](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)

## Used Libraries

- pandas
- numpy
- matplotlib
- seaborn
- plotly

## Data context

This dataset was scrapped from the 'Ease my trip' website by the user [SHUBHAM BATHWAL](https://www.kaggle.com/shubhambathwal). 
It consists in two csv files: **bussiness and economy**. Both of them contain information on various flights from different airlines, including origin and destination cities, departure and arrival times, and prices.
The difference between the files is that *bussiness* contains the bussiness class flights and *economy* the economy class files

Our goal will be to **export** one or more **datasets** resulting from the **merging of the previous two**, where the **information is clean and organized**. 
Moreover, we will answer some of the next questions.

## Table of contents:
- Merging the DataFrames
- General Study
- Analysis
  - Does price vary with airlines?
  - Does ticket price change based on the departure time and arrival time?
  - How the price changes with change in Source and Destination? (*)
  - Which is the price difference between classes?
  - How are the number of stops and duration related to the price?

> **Note: The final part of this section is a map of the cities we are working with, which may not display correctly in the GitHub preview.* 

## Achievements
After data cleaning we exported the following files:
- flight_data_cleaned.csv: Flights data cleaned
- All the images of the graphs generated
- As a potential customer of one of these airlines, we have learned which ones are most convenient for us in each situation.
