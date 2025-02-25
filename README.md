# Python-Main-Project
A dataset from ABC company, consisting of 458 rows and 9 columns. The company requires a comprehensive report detailing information about their employees across various teams. The tasks include preprocessing the dataset, analyzing the data, and presenting your findings graphically.

the dataset : https://docs.google.com/spreadsheets/d/1VP9BE_eI2yl6uUHSm4mGiiwjRdoqCqnkcIjsv5Q2ex4/edit?usp=share_link

* Preprocessing:
Correct the data in the "height" column by replacing it with random numbers between 150 and 180. Ensure data consistency and integrity before proceeding with analysis.

* Analysis Tasks:
1. Determine the distribution of employees across each team and calculate the percentage split relative to the total number of employees.
2. Segregate employees based on their positions within the company.
3. Identify the predominant age group among employees.
4. Discover which team and position have the highest salary expenditure.
5. Investigate if there's any correlation between age and salary, and represent it visually.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------

* Preprocessing Steps
  
The following preprocessing steps were performed:

1. Handling Missing values : Missing values in the 'College' column were handled by filling them with the mode (most frequent value).Missing values in the 'Salary' column were handled by filling them with the median.

2. Checking for outliers : Outliers in the 'salary' column were identified using the interquartile range (IQR) method.

3. Encoding Categorical Data : Convert 'College' column to categorical data type.

4. Correct the data 'Height' column by replacing it with random numbers between 150 and 180.
