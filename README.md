# Project Overview

This repository contains the project that earned me my DataCamp Professional [certification](https://www.datacamp.com/certificate/DA0028934332278). In this project, I analyzed sales data from the company Pens and Printers.

Pens and Printers supplies high-quality office products, ranging from pens and notebooks to desk chairs and monitors, to large organizations. Although they do not manufacture their products, they specialize in selling items produced by other companies.

The company's focus is on providing tools that help customers enhance creativity and brainstorming. They recently launched a new line of office stationery and tested three different sales strategies: targeted emails, phone calls, and a combination of both.

**Email:** Customers in this group received an initial email when the product line launched, followed by another email three weeks later. This method required minimal effort from the sales team.

**Call:** Customers were contacted by a sales team member, with each call averaging around thirty minutes per customer.

**Email and Call:** Customers first received an email with product information and were subsequently called a week later. The initial email required little effort, while the follow-up call averaged ten minutes per customer.

![](product_sales.png)

The executive team sought an analysis of the effectiveness of these sales approaches for the new product line. They needed insights on:

- The number of customers reached by each approach.
- The overall and method-specific revenue distribution.
- Differences in revenue over time for each sales strategy.
- Recommendations on the most effective method, considering the time investment required from the sales team.
- Any additional insights into differences between customer groups that could inform future strategies.

### Data Validation and Cleaning

The dataset initially contained 15,000 rows and 8 columns. After validation and cleaning, the dataset was reduced to 13,926 rows. Key validation steps included:

- **Week:** No missing values; no cleaning required.  
- **Sales Method:** Corrected invalid entries and standardized values.  
- **Customer ID:** Verified uniqueness; no cleaning required.  
- **Revenue:** Cleaned 1,074 rows with missing values.  
- **Years as Customer:** Corrected outliers beyond 40 years.  
- **State and Other Columns:** Verified consistency; no cleaning required.

### Key Insights

#### 1. Distribution of Sales Methods  
- **Email:** Used for 49.7% of customers.  
- **Call:** Used for 34.3% of customers.  
- **Email + Call:** Used for 16% of customers.  

#### 2. Spread of Revenue  
- Overall revenue ranged between $32.54 and $107.33.  
- **Email + Call:** Revenue ranged between $155.77 and $191.12 (median: $184.74).  
- **Call:** Revenue ranged between $41.47 and $52.68.  
- **Email:** Revenue ranged between $87.88 and $105.17.

#### 3. Revenue Over Time  
- **Email** generated the highest revenue over time, followed closely by **Email + Call**.  
- Revenue peaked in the first year of customer engagement and gradually declined in subsequent years.  

#### 4. Items Sold  
The number of items sold closely mirrored the revenue trends across all methods, with **Email + Call** consistently yielding higher results.

### Recommendation

Based on the data, **Email + Call** is the most effective sales strategy, offering the highest median revenue despite being used for only 16% of customers. While it requires more effort, the return on investment makes it a valuable approach.

### Conclusion

This project demonstrates how a data-driven approach can help businesses optimize sales strategies and improve decision-making. The insights and recommendations provided are actionable steps for Pens and Printers to enhance their sales performance and customer engagement.


#### Dive into the project [Here](https://www.datacamp.com/datalab/w/5d2c407f-92c7-42e7-9f37-dd0a9b6f6df0/)
#### View the presentation slides for the executive team [Here](https://github.com/ahmedtanvir47/Product_Sales_Approach_Analysis/blob/main/Practical%20Exam%20Presentation.pdf)
