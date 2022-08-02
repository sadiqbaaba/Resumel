# Nigeria-COVID-19-Data-Analysis-Using-Python
Data Scientist Microdegree Capstone Project

PROJECT OVERVIEW

Coronavirus disease (COVID-19) is an infectious disease caused by a newly discovered coronavirus, 
and it has affected major parts of the world.
Nigeria, a West-African country, has also been affected by
the COVID-19 pandemic after recording its first case on 27th February 2020. 
Nigeria is a country with 37 states - Federal Capital Territory included- and a fast-growing 
economic environment with about 200 million citizens. COVID-19 has affected several country activities as
the country steadily progressed from its first case 
to shutting down major airports, state-wide lockdown, curfews, and reviving its economy. 
In this project, you will employ data science & analytics skills to collect data,
explore the data, perform analysis, create visualizations, and generate insights.

STEPS
Task 1 - Data Collection

NCDC Website scrap

B - John Hopkins Data Repository

Here you will obtain data from the John Hopkins repository. Your task here involves saving the data from the GitHub repo link to DataFrame for further analysis. Find the links below.
•	Global Daily Confirmed Cases - Click Here
•	Global Daily Recovered Cases - Click Here
•	Global Daily Death Cases - Click Here

C - External Data
•	Save the external data to a DataFrame
•	External Data includes but not limited to: covid_external.csv, Budget data.csv, RealGDP.csv

Task 2 - View the data

Obtain basic information about the data using the head() and info() method.

Task 3 - Data Cleaning and Preparation

A. Clean the scraped data

B. Get a Pandas DataFrame for Daily Confirmed Cases in Nigeria. Columns are Date and Cases

C. Get a Pandas DataFrame for Daily Recovered Cases in Nigeria. Columns are Date and Cases

D - Get a Pandas DataFrame for Daily Death Cases in Nigeria. Columns are Date and Cases

Task 4 - Analysis

Perform some analyses on the datasets. You are welcome to communicate findings in charts and summary. 
We have included a few TODOs to help with your analysis. However, do not let this limit your approach, feel free to include more, and be sure to support your findings with chart and summary

 A - Generate a plot that shows the Top 10 states in terms of Confirmed Covid cases by Laboratory test

B - Generate a plot that shows the Top 10 states in terms of Discharged Covid cases. Hint - Sort the values

 D - Plot the top 10 Death cases

E - Generate a line plot for the total daily confirmed, recovered and death cases in Nigeria

 F -

•	Determine the daily infection rate, you can use the Pandas diff method to find the derivate of the total cases.
•	Generate a line plot for the above

G -

•	Calculate maximum infection rate for a day (Number of new cases)
•	Find the date

 H - Determine the relationship between the external dataset and the NCDC COVID-19 dataset. Here you will generate a line plot of top 10 confirmed cases and the overall community vulnerability index on the same axis. From the graph, explain your observation. 

Steps

•	Combine the two dataset together on a common column(states)
•	Create a new dataframe for plotting. This DataFrame will contain top 10 states in terms of confirmed cases i.e sort by confirmed cases. Hint: Check out Pandas nlargest function. This tutorial can help out 
•	Plot both variable on the same axis. Check out this tutorial

I - Determine the relationship between the external dataset and the NCDC COVID-19 dataset.

•	Here you will generate a regression plot between two variables to visualize the linear relationships - Confirmed Cases and Population Density. Hint: Check out Seaborn Regression Plot.
•	Provide a summary of your observation

 J -

•	Provide more analyses by extending TODO G & H. Meaning, determine relationships between more features.
•	Provide a detailed summary of your findings. 
•	Note that you can have as many as possible.

L -

Determine the effect of the Pandemic on the economy. To do this, you will compare the Real GDP value Pre-COVID-19 with Real GDP in 2020 (COVID-19 Period, especially Q2 2020) 

Steps

•	From the Real GDP Data, generate a barplot using the GDP values for each year & quarters. For example: On x-axis you will have year 2017 and the bars will be values of each quarters(Q1-Q4). You expected to have subplots of each quarters on one graph. 
Hint: Use Pandas.melt to create your plot DataFrame 
•	Set your quarter legend to lower left.
•	Using axhline, draw a horizontal line through the graph at the value of Q2 2020.
•	Write out your observation

SUGGESTIONS FOR FUTURE WORK

•	Using data on when the first cases were recorded in the states would also help to improve the current results.
•	Given the data provided, test centers should have also been included.
