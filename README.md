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

* Analysis Insights
     
1. Team Distribution : The data shows that there are 30 Teams in total, with each team having a similar number of employees.

2. Top Teams by Count : The top 5 teams by count are:

      * New orleans Pelicans (19 employees)
      * Memphis Grizzlies (18 employees)
      * Utah Jazz (16 employees)
      * New York Knicks (16 employees)
      * Milwaukee Bucks (16 employees)
      
3. Team Percentage Distribution : The percentage distribution of teams shows that most teams have around 3.27% of the total employees, indicating a relatively even distribution.

4. No Dominant Team : There isn't a single dominant team with a significantly higher number of employees. The distribution is relatively uniform across teams.

5. Position Distribution : The data shows that the most common positions in the company are:

      * SG : 102 employees
      * PF: 100 employees
      * PG : 92 employees
      * SF : 85 employees
      * C : 79 employees

6. Predominant Age group : The pie chart and the output clearly show that the predominant age group among employees is (20.0, 30.0], accounting for approximately 75.5% of the total employees.

7. Team Salary Expenditure : The data shows the total salary expenditure for each team. The team with the highest salary expenditure are: Cleveland Cavaliers: $106,988,689

8. Position Salary Expenditure : The data shows the total salary expenditure for each position. The team with the Highest salary expenditure are : C : $466377332.0

9. Correlation Coefficient :The correlation coefficient between Age and Salary is approximately 0.21. This indicates a  weak positive correlation as age increases, salary also tends to increase, but the relationship is not very strong.



   * Graphs
   
 (i). Box plot of salaries : A box plot of salaries shows the distribution of salaries and identifies outliers.

 (ii). Bar plot : A Bar plot to Determine the distribution of employees across each team and Segregate employees based on their positions within the company.

 (iii). Pie plot : A pie plot to identify the predominant age group among Employees.

 (iv). Histogram : A histogram to Discover which team and position have the highest salary expenditure.

 (v). Scatter plot : A scatter plot to Investigate if there's any correlation between age and salary.
