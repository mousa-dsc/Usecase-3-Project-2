# Usecase- Project-2
The purpose of this project is to apply the Exploratory Data Analysis (EDA) skills we learned as part of the Data Science and Machine Learning Bootcamp offered by Tuwaiq.

**Lead Instructor**: Eng. Esraa Madhi, Data scientist | AI Educator

**Teaching Assistant**: Refal Alboqami, Data scientist

**Teaching Assistant**: Yasser Almubaddil, Data scientist


The purpose of Exploratory Data Analysis (EDA) is to formulate an understanding of a dataset, listen to what the data has to say, and have a feel of what it represents to tackle business problems through extracting insights.

The goal is to understand the data structure which would help in finding potential variables to develop Machine Learning models, look for data quality issues and fix them, while also looking for more questions that would benefit us.

## Datasets Provided:
- There are 3 datasets that has been given to us to do an EDA and problem statements to answer them through our data.
- We will explain our work through the use of each dataset

### Dataset 1- Times Higher Education:
- Data Profiling:	
- Data Cleaning:
- Did the data answered our questions?

### Dataset 2- Center World University Ranking:
- Data Profiling:
  - Descriptive Analysis
    World Rank University CWUR
    2000 Rows
    9 columns
    Data consists of a mix of Strings, integers, and floats types
    Null values* are present, 1562 Rows affected
- Reliability:
  - Yes source is reliable and data was collected from the data source itself: World University Rankings 2024 | Global 2000 List | CWUR
- Timeliness:
  - The data provided  in kaggle is up to date but just about a year ago, which is 2023.
- Consistency:
  - Yes, data is consistent with the data source.
- Relevance: 
  - sample selections: Yes, the data provided is relevant to the objective questions because the questions ask about global ranking and the data source considered      to be world wide ranking.
  - Relevance: 
    Variable selections: We will not remove any of the columns because we need all column  to answer our objective questions.
- Uniqueness: the data contains no duplicated rows,The rank columns can have duplicate values in the possibility 2 universities achieved the same rank, therefore       we will not consider it an issue.
- Completeness: There are zero null values but we null values with dashes.
- Accuracy : We checked the accuracy and we found some data types are string while they are representing a number (int), so we changed them. 
- Data Cleaning: rank type is stirng so we convrted to int with out any string .from (1Top 0.1%) to (1), and in University Name from (Stanford University
  Education: A+; Employability: A+; Faculty: A+; Research: A+) to (Stanford University) 
- Did the data answered our questions? yes
  
### Dataset 3- Shngahai Ranking:
#### Data Profiling:
- Descriptive Analysis:
  - Shanghai Academic Ranking of World Universities (ARWU)
  - 1000 Rows
	- 6 columns
  - Data consists of a mix of Strings and floats types
  - No Null values

- Data quality checks:
Data quality checks involve the process of ensuring that the data is accurate, complete, consistent, relevant, and reliable.
Here are typical steps involved in checking data quality:

1. Reliability:
the data that was provided in Kaggle is reliable and was collected from the original source which is “Shunghai Ranking”. 
This is considered a reliable source because they have been providing university ranking since 2003.

3. Timeliness:
The dataset is from 2022, and due to no available extraction or collection source to get the most recent release, we will have to continue with the 2022 version to answer our problem statements.

4. Consistency:
The data seems to be consistent from the get go, no further modifications seem to be required in this regard.

5. Relevance:
The dataset is not relevant to most of our problem statements, however, it can answer a few of the questions.
columns are not useful to us that will be dropped:
1.	LOGO: images
2.	University Details: URL’s

Note: If we add a location column, it can answer more questions for us, which is what we did in an attempt to cover as much data as possible.

5. Uniqueness:
The data contains no duplicated rows. The rank columns can have duplicate values in the possibility 2 universities achieved the same rank, therefore we will not consider it an issue.

6. Completeness:
The dataset has no null values and all cells are filled.

7. Check Accuracy:
The data requires changes when it comes to data types, some columns need to be changed into an integer.

#### Data Cleaning:



#### Did the data answered our questions?

### What is the best to use for further analysis?



### Team Members:
- Raghad
- Salman
- Mousa
- Mohammed
- Hatoon Aloqaily

