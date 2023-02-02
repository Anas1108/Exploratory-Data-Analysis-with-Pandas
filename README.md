# Exploratory Data Analysis with Pandas

## Introduction
This project is focused on performing Exploratory Data Analysis (EDA) on a dataset using Pandas. The goal of EDA is to get insights about the data, identify patterns and relationships, and prepare the data for further analysis or modeling.

## Dataset
The dataset used for this project is the [Adult Census Income dataset](https://archive.ics.uci.edu/ml/datasets/Adult). This dataset contains information about various features of individuals such as age, workclass, education, marital status, native-country, etc. and the target feature is the salary (above or below 50k).

## Questions to be Answered
1. How many men and women (sex feature) are represented in this dataset?
2. What is the average age (age feature) of women?
3. What is the proportion of German citizens (native-country feature)?
4. What are mean value and standard deviation of the age of those who receive more than 50K per year (salary feature) and those who receive less than 50K per year?
5. Is it true that people who receive more than 50k have at least high school education? (education - Bachelors, Prof-school, Assoc-acdm, Assoc-voc, Masters or Doctorate feature).
6. Among whom the proportion of those who earn a lot(>50K) is more: among married or single men (marital-status feature)? Consider married those who have a marital-status starting with Married (Married-civ-spouse, Married-spouse-absent or Married-AF-spouse), the rest are considered bachelors.
7. What is the maximum number of hours a person works per week (hours-per-week feature)? How many people work such a number of hours and what is the percentage of those who earn a lot among them?
8. Count the average time of work (hours-per-week) for those who earn a little and a lot (salary) for each country (native-country).

## Conclusion
By performing Exploratory Data Analysis on the Adult Census Income dataset using Pandas, we can get insights about the data and answer the questions mentioned above. The results of the EDA can be used to understand the relationships between the features and the target feature, salary.
