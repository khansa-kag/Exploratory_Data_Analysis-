# Exploratory_Data_Analysis-
Performaing Data Analysis by using Python 
1.	Read Dataset and Explore the dataset by checking shape, columns, see the first/last 'n' rows using head/tail. (n= 5,15,30) (6) 
2.	Filter numeric columns and summarize their statistics and do the same for categorical columns(4)
3.	Utilize str.strip() to remove leading
4.	 and trailing spaces and str.replace() to correct specific character issues in the 'Conditions' column of the dataset.
5.	Solve following question by using Groupby(10)
•	What is the average enrollment for each status?
•	How many studies are there for each phase of the trial?
•	What is the average enrollment for studies grouped by gender?
•	What is the earliest start date for each study type? 
•	What is the distribution of statuses in the dataset?
6.	Solve following question by using qcut(10)
•	Enrollment Quantile Categories: How are trials distributed across four quantiles based on enrollment numbers?
•	Start Date Year Quantiles: What are the time periods represented by four quantiles of trial start years?
•	Completion Time Frame Categories: How do trial durations distribute across four quantiles from start to completion date?
•	Outcome Measures Count Quantiles: How are trials categorized into four quantiles based on the number of outcome measures?
•	Trial Update Frequency Quantiles: What does the distribution of trial update frequencies look like across four quantiles?

7.	Completion Time Frame Grouping: Apply the cut function to categorize the completion time frames of trials into distinct intervals. What are the characteristics of trials within each time frame group?
8.	Enrollment Distribution Analysis: Use Matplotlib's hist() function to create a histogram visualizing the distribution of the 'Enrollment' column in the dataset.
Log is used when yo have large number of values. If you pass the parameter True then values shows in exponentianl format. If false then it shows liner. 
