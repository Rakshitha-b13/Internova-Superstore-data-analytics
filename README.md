\# InternNova Superstore Data Analytics



\## 1. Project Overview



This project is an end-to-end data analytics project using the Superstore sales dataset. The project focuses on data preparation, exploratory data analysis, visualization, and interactive Power BI dashboard development to understand sales and profit performance.



\## 2. Problem Statement



Businesses need to understand their sales and profit performance across categories, regions, time periods, and products. This project analyzes Superstore sales data to identify important trends, high-performing areas, low-performing areas, and opportunities for improving business performance.



\## 3. Objectives



\- Prepare and clean the Superstore dataset.

\- Perform exploratory data analysis.

\- Analyze sales, profit, quantity, and discount relationships.

\- Create meaningful data visualizations.

\- Develop an interactive Power BI dashboard.

\- Identify business insights and provide data-driven recommendations.

\- Practice Git and GitHub workflow.



\## 4. Dataset Description



The Superstore dataset contains 9,994 records and 21 columns.



Important columns include:



\- Order ID

\- Order Date

\- Ship Date

\- Ship Mode

\- Customer ID

\- Customer Name

\- Segment

\- Country

\- City

\- State

\- Postal Code

\- Region

\- Product ID

\- Category

\- Sub-Category

\- Product Name

\- Sales

\- Quantity

\- Discount

\- Profit



\## 5. Tools Used



\- Python

\- Google Colab

\- Pandas

\- Matplotlib

\- Power BI Desktop

\- Git

\- GitHub



\## 6. Data Cleaning and Preparation



The dataset was loaded using Pandas with Latin-1 encoding. The dataset was checked for missing values and duplicate records.



No missing values were found and no duplicate rows were identified.



The Order Date and Ship Date columns were converted from object format to datetime format. The cleaned dataset was then exported as `Superstore\_Cleaned.csv`.



\## 7. Exploratory Data Analysis



Descriptive statistics were calculated for Sales, Quantity, Discount, and Profit.



Correlation analysis was performed to understand relationships between numerical variables.



The analysis showed a moderate positive relationship between Sales and Profit, while Discount had a negative relationship with Profit.



Outliers were identified using the IQR method for Sales, Quantity, and Profit. These observations were retained because they may represent genuine business transactions.



Sales and profit were also analyzed by category, region, year, and sub-category.



\## 8. Data Visualizations



The project includes the following visualizations:



1\. Total Sales by Category

2\. Total Sales by Year

3\. Sales Distribution by Category

4\. Total Profit by Region

5\. Sales vs Profit



These visualizations were created to identify sales trends, category performance, regional performance, and the relationship between sales and profit.



\## 9. Power BI Dashboard



An interactive Power BI dashboard was created containing:



\- Total Sales KPI

\- Total Profit KPI

\- Total Orders KPI

\- Sales by Category

\- Sales by Year

\- Profit by Region

\- Sales by Segment

\- Profit by Category

\- Region slicer

\- Category slicer



The dashboard provides an interactive view of important sales and profit metrics.



\## 10. Key Business Insights



1\. Technology is the highest-performing category, generating approximately $836K in sales and $145K in profit.



2\. Furniture generates approximately $742K in sales but only about $18K in profit, indicating comparatively low profitability.



3\. The West region has the highest sales and profit, with approximately $725K in sales and $108K in profit.



4\. Sales increased from approximately $484K in 2014 to $733K in 2017, while profit increased from approximately $50K to $93K.



5\. Tables are a major loss-making sub-category, generating approximately $207K in sales but around $17.7K in negative profit.



\## 11. Business Recommendations



1\. Review pricing, discount levels, and costs for Furniture products, especially Tables, to improve profitability.



2\. Focus on expanding successful Technology products and improve sales opportunities in the South region while maintaining the strong performance of the West region.



\## 12. Conclusion



The project demonstrates an end-to-end data analytics workflow using Python, Pandas, Matplotlib, Power BI, Git, and GitHub. The analysis identified important sales and profit trends, high-performing categories and regions, and areas requiring improvement. The interactive Power BI dashboard provides a clear and effective way to explore the business data and support data-driven decision-making.

