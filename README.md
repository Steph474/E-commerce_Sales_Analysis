# E-commerce_Sales_Analysis

### Project Overview
This Data Analysis Project aims to provide insight into the sales performance of a Fintech based in Lagos, in the 2nd and 3rd quarters in the year 2021. By analysing various aspects of the sales data, we seek to identify trends, make data driven recommendations and gain a deeper understanding of the company's perormance

### Data Source
The dataset used for this analysis is the "Service Provider New Version.xlsx" file
[Service Provider New Version class.xlsx](https://github.com/user-attachments/files/17993078/Service.Provider.New.Version.class.xlsx)

[Download here](https://github.com/user-attachments/files/17993078/Service.Provider.New.Version.class.xlsx)

### Tools
- Excel - Data cleaning
  - [Download here](https://microsoft.com)
- MySQL - Data Analysis
- PowerBI - Data Visualization

### Data Cleaning
In the preparation of the dataset for analysis, we performed the following tasks:
1. Removal of duplicates
2. Handled missing vales with XLOOKUP
3. Change values to the appropriate format

### Exploratory Data Analysis
The data was explpored to answer key questions such as
- What was the monthly sales trend?
- What were the top performing categories?
- What were the peak sales period?
- Is there any room for diversification?

### Data Analysis
```MySQL
SELECT payment_date, amount
FROM service_provider_table
WHERE category = 'betting'
```

### Dashboard
![Screenshot (2)](https://github.com/user-attachments/assets/f535ecfc-629f-4e5e-a216-d58f40a26589)

### Result/Findings

### Recommendations
