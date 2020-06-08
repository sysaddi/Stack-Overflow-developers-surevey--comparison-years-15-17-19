# Stack Overflow developers surevey  comparison years 15,17,19
 
 Data Source: 
For this analysis of the Stack Overflow Developers Survey (comparison of the years 2015, 2017, 2019) the data.
provided by Stack Overflow was used. I changed the name of the files to 'survey_results_publicXX' for a more 
clear overview. 
- https://insights.stackoverflow.com/survey/
(Download Full Data Set (CSV) for 2019, 2017, 2015)



Files in the repository: 
- Readme (contains important information for this repository) 
- Jupiter notebooked used (this is the final version. Steps for data analysis in between were deleted to create a more clear picture.)


The following pyton libaries were used:
- Numpy 
- Pandas
- Matplotlib
- Seaborn


Motivation: 
The aim of this comparison was to identify trends on a country base between the 3 used (Between countries and over time).
Since the new Survey 2020 was just published but the raw data was not publicly available the 2019 data was used as 
reference for the most recent data. 

It would be nice to see a further comparison including the year 2020. This could be also helpful to understand how the 
way of data gathering changed. 


Results: 
It was found that the way of data gathering changed strongly over time. This had a strong effect on the data quality. 

Salary: US is leading and for all countries it's clear that the Salary increased between 2017 to 2019. 
Coding Experience: Values increased over time for all countries but not in the same rate like the salary did. 
The idea of using a time span over 4 years was to account for promotions that are not directly reflected by 
one more increment of experience. But the spike (Question 1) of Salary in 2019 was probably to high to be
explained only by experience. A further in depth statistical analysis could be helpful but important 
features like the Job title are missing in the data set(s). 

Job Satisfaction is for all countries surprisingly even. In comparison for almost all countries 
(outlier = Brazil) the job satisfaction increased in 2019 compared to 2017. 
Therefore, this looks like the developers are happy with there companies and salaries. 

Ideas for further investigation: 
See Jupiter Notebook

Special thanks to Stack Overflow to provide this data. 

