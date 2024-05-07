# Project Title: Exploratory Data Analysis in SQL

**Data set** (https://www.kaggle.com/datasets/swaptr/layoffs-2022)

## Introduction
In today's dynamic economic landscape, payoffs represent a significant aspect of workforce dysnamics across various industries and regions. This project aims to look into a dataset titled layoffs, containing information on the number of people laid off across the world and within different companies and industries. The dataset consists of Tech layoff from COVID 2019 that is 11th March to April 2024. Through data cleaning and exploratory data analysis (EDA), I seek to gain valuable insights into the trends and patterns associated with layoffs.

## Objectives
1. Exploratory Data Analysis
   * After data cleaning process see (https://github.com/FaridahMut/Data-Cleaning-in-SQL) next step is to do EDA using SQL
   * Used different functions to get totals, order etc.
  
# Research questions
1. What is the overall trend of layoffs worldworld over the 3 years?
2. How do layoff vary across different companies and industries?
3. Which are the top companies,e.g., top 5, in each year with the highest layoffs?
4. Are there any seasonal patterns in layoffs?

## Outcomes from the EDA
1. The number of layoffs in 2020 are 80,998, these drop in 2021 however spike in 2022 to 160,322. However, year 2023 has only four months of data and has a total of 125,677 layoffs. We can conclude from this observation that 2023 will have the highest number of layoffs compared to the other years in the dataset.
2. The company with the **highest** layoffs is **Amazon** and the **lowest** layoffs is **Monese**. The **industry** with the **highest** layoffs is **consumer industry** and the **lowest** layoffs is **manufacturing industry**.
3. The top five companies with the layoffs in each year are;
   | |2020|2021|2022|2023|
   |----|----|----|----|----|
   |1|Uber|Bytedance|Meta|Google|
   |2|Booking.com|Katerra|Amazon|Microsoft|
   |3|Groupon|Zillow|Cisco|Ericsson|
   |4|Swiggy|Instacart|Peloton|Amazon &Salesforce|
   |5|Airbnb|WhiteHat Jr|Carvan &Phillips|Dell|

   In 2022, Carvana nad Phillips tied at number 5 and in 2023 Amazon and Salesforce tied at number 4.
   
4.There is a seasonal trend of laying off people as seen in the last three months,i.e., Oct-Dec, in the years 2021 and 2022.
