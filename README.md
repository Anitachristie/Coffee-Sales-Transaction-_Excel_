# Coffee Sales Transaction (Excel)
I worked on a coffee sales project using Excel to organize and analyze the data. I added new columns to better understand the information in the dataset, created pivot tables and charts, applied basic formulas, and developed a dashboard to visualize the information. This made it easier to track important metrics and support decision-making.

## Table of Content
- [Project Overview](project-overview)
- [Data Source](data-source)
- [Tools](tools)
- [Data Cleaning/Preparation](data-cleaning/preparation)
- [Exploratory Data Analysis](exploratory-data-analysis)
- [Data Analysis](data-analysis)
- [Result/Findings](result/findings)
- [Recommendation](recommendation)
- [Limitation](limitation)

---
## Project Overview
This project involves analyzing transactional data from the first half of 2023 (January to June) for a coffee shop in which I cleaned and analyzed the data using pivot tables, charts, and formulas. This aims to transform the data into an interactive dynamic dashboard for other franchise owners to track pattern, trends and make business recommendations. [Coffee Shop Sales.xlsx](https://github.com/user-attachments/files/17102576/Coffee.Shop.Sales.xlsx)

![Excel Dashboard docx](https://github.com/user-attachments/assets/eee4557e-624d-4f69-8100-8b1a6d646ca8)

---
## Data Source
The primary dataset used for this analysis is the " [Coffee Shop Sales Raw dataset.xlsx](https://github.com/user-attachments/files/17102686/Coffee.Shop.Sales.Raw.dataset.xlsx)" file, containing detailed information about each transaction, store and product purchased by the customers.

---
## Tools
- Microsoft Excel.

---
## Data Cleaning/Preparation
I used Excel for:
- Adding calculated column like
  - Revenue field based on the transaction quantity and unit price and formatted it into a currency field.
- Date and Time formating
  - Extracting the Month, Weekday and Hour from the transaction date and transaction time columns.
- Creating pivot tables and charts to represent key insights.
- Assembling all charts and filters/slicers into an interactive dashboard. 

---
## Exploratory Data Analysis
This involved exploring the data to answer key questions, such as:
- What is the revenue for each month?
- What were the number of transactions by day of week and hour of day?
- What were the number of transactions by product category?
- What were the top 15 transactions and revenue by product type?

---
## Data Analysis
This includes an interesting function worked with:

``` =TEXT(B2,"mmmm") ```

---
## Result/Findings
The analysis result are summarized as follows:
- In February, there was a decline of over $5,000 in revenue. However, from March to May, revenue experienced a notable surge, ranging between $20,000 to $35,000. Additionally, there was a slight increase in revenue in June, amounting to over $9,000.
- Transaction were highest around 10 AM on Fridays.
- While coffee records the highest number of transactions across product categories, brewed chai tea leads in terms of transactions by specific product type.

---
## Recommendation
Based on the analysis, I recommend the following actions:
- Since coffee generates the highest number of transactions across product categories, prioritize marketing efforts around coffee-related products. Consider offering special deals or new coffee flavors to attract more customers.
- As brewed chai tea leads in specific product transactions, create targeted promotions or campaigns to highlight this product. This could include seasonal promotions or collaborations with local influencers to increase visibility.
- Investigate the factors contributing to the revenue decline in February to identify and address potential issues. Additionally, examine the reasons behind the notable increase from March to May to replicate successful strategies in the future.
- Given that transactions are highest around 10 AM on Fridays, consider implementing promotional offers or marketing campaigns during this time to maximize revenue.

---
## Limitation
The dataset was found to be accurate and complete, with no duplicates or misspellings. I encountered no issues or obstacles during my analysis.
