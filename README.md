# [PYTHON] Cohort Analysis: How to Analyze User Retention

## I. Introduction
### 1. About Cohort Analysis
### What is cohort and cohort analysis? 
- A **cohort** is a group of users who share a common characteristic, and cohort analysis is a tool to measure their engagement over time.
- **Cohort analysis** helps to differentiate between actual improvements in user engagement and those that may be driven by growth, while vanity indicators do not provide the same level of insight.
### Three major types of Cohort
- **Time cohorts**: customers who signed up for a product or service during a particular time frame.
- **Behavior cohorts**: customers who purchased a product or subscribed to a service in the past.
- **Size cohorts**: refer to the various sizes of customers who purchase the company’s products or services.
### Which type of cohort is for this project?
- I will focus on performing Cohort Analysis based on Time (**Time cohorts**).
### 2. Business Questions
- Using Python to analyze data from KPMG transaction dataset to make a cohort to evaluate user engagement from their first transaction.
## II. Data Visualization with Python
- **MoM Retention Rate for Customer Transaction Data**
  
![image](https://github.com/heilongtian/Cohort-Analysis/assets/126595334/df7fd7e9-e10c-4bb9-ba65-d71ca694fe05)

## III. Insights
- Customers who register and place their first order in July 2017 have a high retention rate (up to 48.1%) after 5 months of operation.
- Customers who register and place their first order in April 2017 have a stable and relatively high retention rate: 45.1% (4th month), 42.1% (5th month) ), and 42.7% (7th month).
- Customers who register and place their first order in May 2021 also have a fairly high and stable retention rate: 40.4%, 39%, and 41.3% in the 2nd, 3rd and 4th-month activities.
- Looking at the above insights, we can see that customers who start ordering from mid-year 4,5,6,7,8 tend to order stable, and relatively higher than the rest months of the year.
- Customers who place orders at the beginning of January and February only show stability, nothing special.
- KPMG's year-to-date retention rate is quite good, all 30% or more (except 1st month at 25.5%).
- 
## IV. Recommendations
- There should be attractive preferential policies for customers in the first months of the year to increase the order rate (retention) over the months.
- The Mid-year months have higher retention rates than other months -> need to dive into why (with relevant data, and visualization of other data) to apply to other months of the year.
