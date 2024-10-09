# Customers Churn Analysis
The aim of this project is to conduct a churn analysis on the company's customers and identify the key factors contributing to it. By understanding the patterns and behaviors associated with customer churn, the company can enhance its retention strategies and improve overall business performance.

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

2) Power Query Editor: Utilized for advanced data cleaning and transformation.

3) Power BI: Used for visualizing insights from the data through interactive dashboards.

## Data Cleaning and Transformation

- I began by selecting all data using Ctrl+A and then converted the range into a table with Ctrl+T. This facilitated easier navigation and analysis of the dataset.

- Next, I checked for and removed inconsistent and duplicate entries across all columns using Excel's "Remove Duplicates" feature, ensuring that only unique values were included in the analysis.

- I applied the "TRIM" function in Excel to eliminate unnecessary data space. I also corrected typographical errors using the "Find and Replace" function in Excel and Power Query.

- Rows with inconsistent or inaccurate entries were removed to enhance data quality.

- In Power Query Editor, I utilized the "Conditional Column" function to categorize customer ages into specific brackets. Additionally, I grouped customers' Annual Incomes into bins using the same feature.

- Lastly, I standardized the headers by transforming the first row of each column into clearly titled and properly capitalized headers for improved clarity.

## Exploratory Data Analysis (EDA)
During the EDA process, I focused on several key business questions that guided my analysis:

1) What is the total number of customers?
2) What percentage of customers show an attrition flag in each?
3) What percentage of customers show an attrition flag in each category?
4) How many customers use each card category?
5) What is the distribution of customer gender?
6) What are the marital statuses of the customers?
7) What educational levels do the customers hold?
8) What is the age distribution of our customers?
9) What is the annual income distribution among our customers?

## Data Analysis

- Attribution Flag: The company's database holds a total of 10,127 customers, with 8,500 being existing customers and 1,627 classified as Attrited.

- Age Group Distribution: The leading age groups among customers are 41-50 years, 51-60 years, and 31-40 years, with a total of 4,652 (45.94%), 2,673 (26.39%), and 2,132 (21.05%) customers, respectively. In these groups, 779, 448, and 310 customers have attrited in each category

- Gender Distribution: 5,358 (52.91%) of customers are Female, while 4,769 (47.09%) are Male. Of these, 930 females and 697 males fall into the attrited category.

- Card Category: The Blue card has the highest patronage, with a total of 9,436 customers, of which 1,519 have attrited. The Silver, Gold, and Platinum cards have patronages of 555, 116, and 20 customers, respectively, with 82, 21, and 5 customers attrited from each category.

- Education Status Distribution: 3,128 customers are Graduates, and 2,013 are High School leavers, with 487 and 306 of them belonging to the attrited category, respectively. The Education status of 1,519 customers is Unknown, with 256 attrited. Additionally, there are 1,487 Uneducated customers, 1,013 College leavers, 516 Post Graduates, and 356 Doctorates, with 237, 154, 92, and 95 attrited in each group, respectively.

- Income Distribution: 3,561 customers have an annual income below $40k, while 1,790 customers earn between $40k and $60k, with 612 and 271 attrited, respectively. Additionally, 1,402 customers earn $60k-$80k annually, 1,535 earn $80k-$120k, and 727 earn over $120k, with 242, 189, 187, and 126 customers attrited in each respective category.

- Marital Status: 4,687 customers are Married, 3,943 are Single, and 748 are Divorced. Among them, 709 married customers, 668 single customers, and 121 divorced customers have attrited.

## Recommendations 

1) Focus on the age groups 41-50 years and 51-60 years, which have the highest attrition rates (779 and 448, respectively). Develop tailored retention strategies, such as personalized communication, loyalty programs, or exclusive offers that address the specific needs and preferences of these age demographics.

2) With a higher number of female customers (5,358) and a significant attrition rate (930), implement initiatives aimed at increasing engagement among female customers. Consider targeted marketing campaigns, feedback surveys, or events that cater specifically to women, enhancing their overall experience with the brand.

3) Review the benefits offered across all card categories, with priority attention given to the Silver, Gold, and Platinum cards, to ensure they provide compelling value. Also, offering exclusive incentives for cardholders might help reduce customer attrition.

4) Given that a significant number of attracted customers belong to the Uneducated and High School leaver categories, consider launching educational outreach programs. Offering resources or partnerships with educational institutions could improve customer loyalty and attract a broader audience.

5) With a notable number of customers in lower income brackets (below $40k and $40k-$60k) experiencing high attrition, create income-sensitive promotions. Tailor products and services with affordable pricing or financing options to accommodate these segments.

## Conclusion 
This project has provided insights into the company's business performance, with focus on customers attrition.
By focusing on the recommendation, the business can enhance customer retention, improve satisfaction, and potentially grow its customer base.
