# Data Mining Project: Salary and Demographic Information with Experience  
**Osama Marie - 201911195**  
**Mays Qasem - 201910019**

## 1. Overview
This project focuses on analyzing a comprehensive dataset that includes salary and demographic information, along with years of experience. The aim of this data mining project is to explore the relationship between income and various socio-demographic factors. The dataset provides details such as age, gender, education, country, and race, offering a broad range of variables for analysis. Additionally, the inclusion of years of experience allows for a deeper understanding of how professional tenure impacts salary levels. This adds a dynamic aspect to the analysis, enabling insights into income disparities and earning potential across different demographic categories.

## 2. Dataset Information
The dataset consists of several columns that provide valuable information about individuals:
- **Id**: A unique identifier for each individual in the dataset (Note: this is not a key attribute for analysis but is mentioned as part of the dataset).
- **Age**: The chronological age of individuals in years.
- **Gender**: The gender identification of individuals.
- **Education level**: The highest level of education attained by the individuals.
- **Job title**: The current occupation or professional role of the individuals.
- **Years of experience**: The number of years individuals have worked in their respective fields.
- **Salary**: The income level or salary of the individuals.
- **Country**: The country of residence of the individuals.
- **Race**: The racial or ethnic background of individuals.

## 3. Tools Used
- **Python**: We used Python for data analysis and data mining tasks, including handling missing data, outliers, and performing exploratory analysis.

## 4. Column Analysis
- **Id**: Numeric (int) - A unique identifier for each record in the dataset.
- **Age**: Numeric (int) - The age of individuals.
- **Gender**: Nominal (chr) - The gender of individuals.
- **Education level**: Nominal (chr) - The highest level of education.
- **Job title**: Nominal (chr) - The job title or role.
- **Years of experience**: Numeric (int) - The number of years of work experience.
- **Salary**: Numeric (int) - The salary or income.
- **Country**: Nominal (chr) - The country of residence.
- **Race**: Nominal (chr) - The race or ethnicity of individuals.

## 5. Dataset Size
- **Number of attributes**: 9 attributes
- **Number of observations**: 6706 records

## 6. Attribute Types
- **Id**: Numeric (int) - Not considered a key attribute but included in the dataset.
- **Age**: Numeric (int)
- **Gender**: Nominal (chr)
- **Education level**: Nominal (chr)
- **Job title**: Nominal (chr)
- **Years of experience**: Numeric (int)
- **Salary**: Numeric (int)
- **Country**: Nominal (chr)
- **Race**: Nominal (chr)

## 7. Link to the Dataset
You can find the dataset on Kaggle:  
[Salary Dataset Based on Country and Race](https://www.kaggle.com/datasets/sudheerp2147234/salary-dataset-based-on-country-and-race)

## 8. Issues with the Dataset
Several issues were identified in the dataset, including:
- **Missing values**: Some columns have missing data.
- **Duplicated observations**: The dataset contains duplicate records.
- **Outliers**: There are outliers present, particularly in the age and salary columns.
- **Inconsistent values in categorical attributes**: Inconsistent or incorrect entries in certain categorical fields.

## 9. Problem Definition
To address the issues within the dataset:
- **Missing data**: Missing values in text fields were replaced with the most frequent values, as the amount of missing data did not justify deleting the rows.
- **Outliers**: For the `age` attribute, outliers were minimal, so they were removed. For other attributes, when the outliers were more significant, we replaced them with the mean value.
- **Inconsistent class attributes**: Incorrect values were replaced with appropriate ones.
- **Duplicate data**: Duplicate records were removed.
