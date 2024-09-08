# Exploring-NYC-Public-School-Test-Result-Scores
Exploring NYC Public School Test Result Scores
This project analyzes standardized test performance data from New York City's public schools to uncover insights into school performance across the city. The primary focus is on identifying the schools with the best math scores, exploring performance differences across boroughs, and ranking the top-performing schools based on combined SAT scores.

Project Overview
The goal of this project is to analyze test results and answer key questions related to school performance:

Top Math Results: Identify the NYC public schools with the best math results. A school is considered to have the best math scores if its average math score is at least 80% of the maximum possible score of 800.

Top 10 Schools by SAT Performance: Determine the top 10 performing schools based on their combined SAT scores, identifying the overall best-performing schools across all subjects.

Borough with the Most Variation in SAT Performance: Analyze which NYC borough exhibits the largest variation (standard deviation) in combined SAT scores, providing insights into borough-wide performance disparities.

Tasks and Solutions
Best Math Results:

Schools with math scores that are at least 80% of the maximum possible score (640 out of 800) are considered top performers.
The results are saved in a pandas DataFrame called best_math_schools, which contains the columns "school_name" and "average_math", sorted by "average_math" in descending order.
Top 10 Performing Schools (SAT):

The top 10 performing schools based on combined SAT scores are identified.
The results are saved in a pandas DataFrame called top_10_schools, which includes the "school_name" and a new column named "total_SAT", sorted by "total_SAT" in descending order.
Borough with the Largest Standard Deviation in SAT Scores:

We determine which borough has the greatest standard deviation in total SAT scores, indicating the most variation in school performance.
The results are saved in a pandas DataFrame called largest_std_dev, which includes:
"borough": The name of the NYC borough with the largest standard deviation of "total_SAT".
"num_schools": The number of schools in that borough.
"average_SAT": The mean of "total_SAT" for the borough.
"std_SAT": The standard deviation of "total_SAT" for the borough.
All numeric values are rounded to two decimal places.
Skills and Tools Demonstrated
This project showcases proficiency in:

Data Analysis: Investigating school performance through standardized test data.
Pandas: Using Pandas for data manipulation, aggregation, and analysis.
Data Wrangling: Cleaning and transforming the dataset for effective analysis.
Statistical Analysis: Calculating metrics like mean, standard deviation, and identifying patterns across different boroughs.
How to Use This Repository
Dataset: The dataset containing NYC public school test results should be placed in the root directory of this repository.
Analysis: The analysis is implemented in a Jupyter Notebook, guiding you through each step to reproduce the results.
Output: Final results include DataFrames (best_math_schools, top_10_schools, and largest_std_dev) highlighting the top-performing schools and borough-specific insights.
Conclusion
This project provides insights into the performance of NYC public schools, identifying top performers and highlighting borough-specific differences in SAT results. The analysis demonstrates key data science skills, including data wrangling, analysis, and statistical evaluation using Python and Pandas.
