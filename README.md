
# Prosper Loan Dataset Exploration
## by Jennifer Orji

## Focus

This exploration is focused of financial services.

## Objectives 
<br></br>

1. Use Statistics and Visualization to gain in-depth understanding of the dataset.
<br></br>
2. Generate Univariate, Bivariate and Multivariate plots across selected variables.
<br></br>
3. Create at least 15 plots across univariate bivariate and multivariate exploration plots.
<br></br>
4. Bearing in mind the design principles,
create effective visualization that is comprehensive to an audience.

## Installation
> The following libraries were used in this project.
<br></br>
• Numpy
<br></br>
• Matplotlib
<br></br>
• Pandas
<br></br>
• Seaborn
<br></br>
• Datetime.



## Dataset

 The dataset contains information on customers who used a particular loan service. The dataset has 113,937 rows and 81 columns all containing different observations about different customers.
find the data dictionary [here](https://docs.google.com/spreadsheets/d/1PuUMCXOjAo92zPl1dgBXojGWkADo63h4ieFh7BH5jJk/edit?usp=drivesdk)
## Data Wrangling 

A subset of the dataset with 21 columns was created. The following issues were detected and rectified in the dataset.

1. Stated Monthly Income and Prosper Score was rounded to the nearest whole number.
<br></br>
2. Listing Number, Loan Status, Borrower State, Employment Status and Prosper Rating Alpha were converted to Categorical Datatype.
<br></br>
3. Loan Origination Date was converted to Datetime
<br></br>
4. Total Prosper Loan was dropped as it contained a 91,852 missing values.
<br></br>
5. Missing values in columns like Borrower State, Occupation, Prosper Rating Alpha, and Employment Status were replaced with either 0 or "Not Stated".




## Summary of Findings
The year with the highest count was 2013, Top 6 months with highest count in descending order are; January, October, December, February, November and August.
<br></br>
 Top five occupation with highest count in descending order are; Professionals, Computer Programmer, Executive, Teachers, and Administrative Assistants. 
 
 Top 7 states with highest count in descending order are; California, Texas, New York, Florida, Illinois, Georgia and Ohio. The loan term with highest count is 36 months or 3 years.
 

Loan Original Amount showed a multimodal distribution with peaks equivalent to groups of five.

 Monthly Loan payment also showed a multimodal distribution with the highest peak at 200 dollars.
 
A heatmap showed a strong positive relationship between monthly loan payment and loan original amount. all other variable showed a weak positive relationship.

 When compared to loan original amount, the following are states and occupation 
with highest count in descending order.
New Hampshire, Washington DC, Alaska, Maryland, Massachusetts. Pharmacy, Judge, Principal, Pilot, Executive.

 On further examination with monthly stated income, the aforementioned occupation were detected among the highest paying income.
 
  loan term and loan original amount seem to be positively related across the month. the higher the loan amount, the higher the loan term.
  
For easy visualization and understanding, 26 states and 18 occupations were selected, and 6 states with the hughest count in descending order. Occupations like Professionals, Psychologists, Professors, Doctors, Nurses, Analysts, Computer Programmers, Executives, Attorneys, Construction Workers, firemen and Mechanical Engineers took more loans in January and February compared to other months. Occupations like Principals,and Car Dealers took more in January and November. Chemical Engineers and Biologists took more in October and November. Social Workers took more loans in January, Judges took more loans in November and December and Pharmacists took more loans in November, December, January and August.



## Key Insights for Presentation

The goal of this research was to understand the distribution of loan amount across states, occupations and months. This is in a bid to understand the customers and determine when best to send advertorials on loans.
 For this presentation, we would be looking at plots that depicts how loan amount varies across loan term and month, how loan term varies across states and occupations in selected months.
First we would see the distribution of all the stated variables as univariate plots and see their relationship when compared to each other.

 
