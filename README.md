# Kickstarting with Excel

## Overview of Project

### Purpose
Based on a dataset of information about Kickstarter campaigns collected from 21 countries between 2009 and 2017, analyze campaign outcomes based on the launch date of the campaign and by the targeted campaign funding goal and display the results graphically. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Delivered a pivot table and line chart to show trends in Kickstarter goal success, failure, or cancellation per month of the year.


### Analysis of Outcomes Based on Goals
Delivered a table showing Kickstarter campaign outcomes (Successful, Failed, Canceled) per a set of ranges of funding targets. Showed the count and percentage of each the specified campaign outcomes within the  set of ranges of funding targets. Additionally, displayed the information graphically in a line chart


### Challenges and Difficulties Encountered
For the 2nd analysis - Outcomes Based on Goals, the use of COUNTIFS formulas in multiple cells raises a risk of data entry error as each formula entered requires some manual data entry which could lead to typing errors if not fastidiously checked for errors.  


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Campaigns launched in early May have the greatest rate of successful vs failed outcomes
Campaigns launched in December have the highest rate of failed outcomes.  

- What can you conclude about the Outcomes based on Goals?
Campaigns with funding goals of less than $5K have the greatest chance of success, butbecause the number of campaigns with funding goals >= 15K in the dataset is small, the resulting analysis of this set of campaigns may be less accurate

- What are some limitations of this dataset?
The goal funding amounts are not translated into a single currency 

There are several data points that are outliers that haven't been investigated or eliminated


- What are some other possible tables and/or graphs that we could create?
It would be useful to create tables and/or graphs to analyze:
Relation of number of backers to outcome
Relation of average donation size to outcome
Relation of length of campaign to outcome
