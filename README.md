# Project-1-An-Analysis-on-Data-Analyst-Jobs
## Table of Contents

1. [Installation](#Installation)
2. [Project Motivation](#Project-Motivation)
3. [File Description](#File-Description)
4. [Results](#Results)
5. [Acknowledgements](#Acknowledgements)

## Installation
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. 

## Project Motivation
For this project, I was interestested in using the 2253 job listings scraped from glassdoor to do an analysis on Data Analyst Jobs. The scraped data was found on Kaggle. Here are the research questions that will be covered in this project:
1. Which industries/sectors/states have higher demand for data analyst?
2. What salaries can data analysts expect?
   * Min & Max Salary Distribution
   * Average Salary by "State"
   * Average Salary by "Type of Ownership"
3. What features have more impact on the average salary?

## File Description
The csv file is downloaded from Kaggle, which is originally scraped from glassdoor. The jupyter notebook file contains codes of data preprocessing, data visualizations and a model prediciton of the average salary of data analyst.

## Results
* There are more job opportunities in industries like IT, Staffing & Outsourcing and Health Care Services & Hospitals, or in sectors like IT, Business Services and Finance. The top 3 states that are demanding higher number of data analysts are California, Texas and New York.
* If you are planning to be a data analyst, expect a minimum salary range of 24K to 113K, or a maximum salary range of 38K to 190K. If you are in California, expect a larger range of salary distribution than any other states.  
* The independent variables chose for the model are 'Job Title', 'Rating', 'Location', 'Headquarters', 'Size', 'Type of ownership', 'Sector', 'State', 'Max Revenue'. However, none of these are significant enough to predict the average salary. If we could find some more data sets,the r-squared value could be improved by adding more features that are more significant.  
      
## Acknowledgements
Must give credit to Kaggle and Glassdoor for the data. You can find other descriptive information at the Kaggle link available [here](https://www.kaggle.com/andrewmvd/data-analyst-jobs). I also referrenced some codes learned from Udacity Data Science Nanodegree for the part where we define a function to find the optimal linear model and coefficient weights of the model. 

