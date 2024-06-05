# **Comprehensive Assessment - Exploratory Data Analysis on ABC Company Dataset**

The dataset containing employee attributes was analyzed based on given queries, and insights were drawn. Appropriate visualizations were generated.

# Table Of Contents
  
  - Problem Statement
  - About the Dataset
  - Python libraries used
  - Project Work flow
  - Data Preprocessing
  - Sample Visualizations
  - Insights Gained

  
## Problem Statement

<p>As a culminating project, you'll be working with a dataset from ABC company, consisting of 458 rows and 9 columns. The company requires a comprehensive report detailing information about their employees across various teams. Your tasks include preprocessing the dataset, analyzing the data, and presenting your findings graphically. Here's a breakdown of what you need to do:</p>
<p>Preprocessing:
Correct the data in the "Height" column by replacing it with random numbers between 150 and 180. Ensure data consistency and integrity before proceeding with analysis. (1 mark)</p>
<p>Analysis Tasks:<br>
1. Determine the distribution of employees across each team and calculate the percentage split relative to the total number of employees. (2 marks)<br>
2. Segregate employees based on their positions within the company. (2 marks)<br>
3. Identify the predominant age group among employees. (2 marks)<br>
4. Discover which team and position have the highest salary expenditure. (2 marks)<br>
5. Investigate if there's any correlation between age and salary, and represent it visually. (2 marks)</p>
<p>Graphical Representation:
For each of the five analysis tasks, create appropriate visualizations to present your findings effectively. (5x2 = 10 marks)

Data Story:
Provide insights gained from the analysis, highlighting key trends, patterns, and correlations within the dataset. (3 marks)</p>


understanding the factors that influence Airbnb prices in New York City, or identifying patterns of all variables and Our analysis provides useful information for travelers and hosts in the city and also provides some best insights for Airbnb business.


## **About the Dataset**

### Dataset Information
* Number of rows/instances: 458
* Number of columns/attributes: 9

*   The Data includes both categorical and numeric values, providing a diverse range of information about the employees.

*   link to dataset : https://docs.google.com/spreadsheets/d/1VP9BE_eI2yl6uUHSm4mGiiwjRdoqCqnkcIjsv5Q2ex4/edit?usp=share_link

*   Categorical data: Name, Team, Position, College

*   Numerical data: Number, Age, Height, Weight, Salary


##  Python Libraries Used

* Pandas

* NumPy
  
* Seaborn

* Matplotlib.Pyplot


## Project Work flow

1. Importing Libraries

2. Loading the Dataset

3. Exploring/Inspecting Dataset

3. Data Cleaning

4. Performing Analysis Tasks 

5. Data Visualization

6. Deriving Insights


## Data Preprocessing

The imported data frame was inspected for null and inconsistent values and following conclusions were drawn.
- Column 'Height' which is expected to contain numerical data has inconsistent values.
- Colums 'Salary' and 'College' have missing values.

Decided to handle these data integrity issues as specified below:
- The data in the "Height" column is replaced with random numbers between 150 and 180.
- Missing values in 'Salary' are filled with average salary of employees of respective teams.
- Missing values in 'College' are filled with value 'Unknown'

## Sample Visualizations

![demo_plot](https://github.com/abhi-ram-krishna/EDA-Employee-Dataset/assets/42677472/3f04d0d0-f990-4640-8b88-96d54cea9bcc)
![d1](https://github.com/abhi-ram-krishna/EDA-Employee-Dataset/assets/42677472/b4529e4f-1ab1-44fd-a94a-6aa524f2b398)
![d2](https://github.com/abhi-ram-krishna/EDA-Employee-Dataset/assets/42677472/5517e8aa-3a37-49f8-aa7d-907cdff23445)

## Insights Gained
Insights of tasks are provided in the notebook file along with the tasks. Kindly check the file.
