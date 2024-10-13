# Customers Churn Analysis

## Project Overview
This project aims to conduct a churn analysis of the company's customers and identify the key factors contributing to it. By understanding the patterns and behaviors associated with customer churn, the company can enhance its retention strategies and improve overall business performance.

## Data Source
The data was obtained from the Kaggle repository website, and it contains the following columns:
- Customer ID
- Card Categories
- Customer Education Level
- Customer Age
- Customer Marital Status
- Customer Annual Income
- Attrition Flag
- Gender

Click on the link to interact with the [Analysis Dashboard](https://app.powerbi.com/groups/me/reports/c80474ed-5907-458c-b0d0-1f2647c17e79/ReportSection9e6310ee895b50850aac?experience=power-bi&clientSideAuth=0)

## Tools Used

1) Microsoft Excel: Utilized for data cleaning and transformations.

2) Power Query Editor: Utilized for further data cleaning and transformation.

3) Power BI: Used for visualizing insights from the data through interactive dashboards.

## Data Cleaning and Transformation

- I began by selecting all data using Ctrl+A and then converted the range into a table with Ctrl+T. This facilitated easier navigation and analysis of the dataset.

- Next, I checked for and removed inconsistent and duplicate entries across all columns using Excel's "Remove Duplicates" feature, ensuring that unique values were included in the analysis.

- I applied Excel's "TRIM" function to eliminate unnecessary spaces in the data. I also corrected typographical errors using the "Find and Replace" function in Excel and Power Query.

- Rows with inconsistent or inaccurate entries were removed to enhance data quality.

- In Power Query Editor, I utilized the "Conditional Column" function to categorize customer ages into specific brackets. Additionally, I grouped customers' Annual Incomes into bins using the same feature.

- Lastly, I standardized the headers by transforming the first row of each column into clearly titled and properly capitalized headers for improved clarity.

## Exploratory Data Analysis (EDA)
During the Exploratory Data Analysis (EDA) process, I focused on the following key business questions which guided my analysis:

1) What is the total number of customers?
2) What percentage of customers show an Attrition flag?
3) What percentage of customers show an Attrition flag in each category?
4) How many customers use each Card category?
5) What is the Gender distribution of customers?
6) What are the Marital Statuses of customers?
7) What Educational levels do customers hold?
8) What is the Age distribution of customers?
9) What is the Annual Income distribution among customers?

## Data Analysis

- Attrition Flag: The company's database holds 10,127 customers, 8,500 of whom are Existing customers and 1,627 Attrited.

- Age Group Distribution: The leading age groups among customers are 41-50 years, 51-60 years, and 31-40 years, with a total of 4,652 (45.94%), 2,673 (26.39%), and 2,132 (21.05%) customers, respectively. In these groups, 779, 448, and 310 customers have Attrited, respectively.

- Gender Distribution: 5,358 (52.91%) of customers are Female, while 4,769 (47.09%) are Male. Of these, 930 Females and 697 Males fall into the Attrited category.

- Card Category: The Blue Card has the highest patronage, with a total of 9,436 customers, of which 1,519 have Attrited. The Silver, Gold, and Platinum cards have patronages of 555, 116, and 20 customers, respectively, with 82, 21, and 5 customers Attrited, respectively.

- Education Status Distribution: 3,128 customers are Graduates, and 2,013 are High School leavers, with 487 and 306 of the customers belonging to the Attrited category, respectively. The Education Status of 1,519 customers is Unknown, with 256 Attrited. Additionally, there are 1,487 Uneducated customers, 1,013 College leavers, 516 Post Graduates, and 356 Doctorates, with 237, 154, 92, and 95 Attrited in each group, respectively.

- Income Distribution: 3,561 customers have an Annual Income below $40k, while 1,790 customers earn between $40k and $60k, with 612 and 271 Attrited, respectively. Additionally, 1,402 customers earn $60k-$80k annually, 1,535 earn $80k-$120k, and 727 earn over $120k, with 242, 189, 187, and 126 customers Attrited, respectively.

- Marital Status: 4,687 customers are Married, 3,943 are Single, and 748 are Divorced. 709, 668, and 121 of these customers have Attrited, respectively.

## Recommendations 

1) Focus on the age groups 41-50 years and 51-60 years, which have the highest attrition rates (779 and 448, respectively). Develop tailored retention strategies, such as personalized communication, loyalty programs, or exclusive offers that address the specific needs and preferences of these age demographics.

2) With a higher number of Female customers (5,358) and a significant attrition rate (930), implement initiatives aimed at increasing engagement among female customers. Consider targeted marketing campaigns, feedback surveys, or events that cater specifically to women, enhancing their overall experience with the brand. Also, extend the same strategy to the Male customers to increase overall sales.  

3) Review the benefits offered across all Card categories, with priority attention given to the Silver, Gold, and Platinum cards, to ensure they provide compelling value. Also, offering exclusive incentives for cardholders could help reduce customer attrition.

4) Given that a significant number of Attrited customers belong to the Uneducated and High School leaver categories, consider launching educational outreach programs. Offering resources or partnerships with educational institutions could improve customer loyalty and attract a broader audience.

5) With a notable number of customers in Lower Income brackets (below $40k and $40k-$60k) experiencing high attrition, create income-sensitive promotions. Tailor products and services with affordable pricing or financing options to accommodate these segments.

## Conclusion 
This project has provided insights into the company's business performance, with a focus on customer attrition. By focusing on the insights from the analysis and the recommendations, the business can enhance customer retention, improve satisfaction, and increase it's revenue.
