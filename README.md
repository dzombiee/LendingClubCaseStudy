# Lending Club Case Study
> This project involves applying Exploratory Data Analysis (EDA) techniques to assist a consumer finance company specializing in lending loans to customers. The primary goal is to identify indicators and patterns that predict loan default, helping the company make informed lending decisions to minimize financial losses. By understanding the driving factors behind loan defaults, the company aims to reduce credit loss, optimize lending strategies, and improve overall decision-making in loan approvals.


## Table of Contents
* [General Info](#general-information)
* [Packages Used](#packages-used)
* [Conclusions](#conclusions)

## General Information
**Background:** This project centers around a consumer finance company specializing in urban lending, striving to balance business growth and minimize financial losses due to loan defaults. 

**Business Problem:** The core challenge is to identify loan applicants likely to default, thereby enabling the company to make more informed lending decisions. The primary goal is to reduce credit loss and optimize lending strategies.

**Dataset:** The project utilizes historical data on past loan applicants, including their repayment outcomes. This dataset provides valuable insights into applicant profiles and their loan repayment behavior, serving as the foundation for exploratory data analysis (EDA) and risk analytics.

## Packages Used
- matplotlib
- seaborn
- pandas
- numpy

## Conclusions
* emp_length more than 10 years and annual_inc above 60k
* int_rate between 20%-24% and annual_inc above 60k
* emp_length more than 10 years and loan_amnt greater than 14k
* verified loan and loan_amnt above 16k
* term as 60 months and loan_amnt more than between 14k-16k
* grade is F and loan_amnt greater than 15k
