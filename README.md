# Istanbul Shopping Malls Sales Analysis Dashboard
- The objective of this project is to monitor key sales metrics such as sales volume and analyze customer data in order to drive better business decision such as
  - Allows sales team and management team to track progress towards goals, identify top-performing products and recognize high-performing sales representatives
  - Enhances the ability to tailor sales strategies to meet customer needs, improve customer satisfaction and increase loyalty

## References:
**Python Version:** 3.10 <br />
**Packages:** numpy, pandas, datetime <br />
**Data Source:** [Customer Shopping Dataset - Retail Sales Data](https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset) <br />
**Data Preprocesing ipynb File:** [Kaggle_Customer_Shopping_Dataset_Data_Cleaning.ipynb](https://github.com/rnlow22/shopping_mall_sales_dashboard/blob/main/Kaggle_Customer_Shopping_Dataset_Data_Cleaning.ipynb) <br />
**Dashboard twbx File:** Only accessible during the demonstration meeting.

## Overview of the Dashboard:
This dashboard consists of 3 parameters and 4 main analysis sections:
### Parameters:
1. Date: The analysis displayed on the dashboard corresponds to the chosen date.
2. Date Type: The dashboard analysis is determined by the selected date type, including daily, weekly, monthly, and yearly.
3. No. of Periods: This parameter controls the display of past periods for trend chart analysis.

### Analysis Sections:
1. Key Performance Indicators
2. Charts
3. Map
4. Trend Charts

![image](https://github.com/rnlow22/shopping_mall_sales_dashboard/assets/30455582/34ab63ef-961f-4712-b8eb-12c4f0d1e8d3)


### Dashboard Functionality:
1. Analysis can be interactively filtered by clicking on any item within the chart.
![Screenshot 2024-05-29 at 6 57 55 PM](https://github.com/rnlow22/shopping_mall_sales_dashboard/assets/30455582/37758361-d0a3-44c3-9e1a-32e50d6e87f1)

2. Business users can tailor the number of past periods for trend chart analysis according to their needs.
![Screenshot 2024-05-29 at 7 44 31 PM](https://github.com/rnlow22/shopping_mall_sales_dashboard/assets/30455582/1d52ac11-1f54-4add-aba0-3ddaff3215f8)

3. Various trend charts analyzing different Key Performance Indicators can be accessed by selecting from the dropdown menu.
![Screenshot 2024-05-29 at 7 49 25 PM](https://github.com/rnlow22/shopping_mall_sales_dashboard/assets/30455582/151c38ac-74a6-497e-a717-f000ba64c790)

4. Month-on-Month Growth for Key Performance Indicators is displayed in a single view on the dashboard when selecting Date Type as "Monthly". This functionality extends to Day-on-Day, Week-on-Week, and Year-on-Year Growth as well.
![Screenshot 2024-05-29 at 7 51 09 PM](https://github.com/rnlow22/shopping_mall_sales_dashboard/assets/30455582/9b474a89-2e7c-4c78-91f6-803f6b757eab)

### BI Monthly Reporting for January 2023:
![image](https://github.com/rnlow22/shopping_mall_sales_dashboard/assets/30455582/63def021-41fb-4b26-a06b-27da0e0e2016)


1. January 2023 witnessed consistent sales volumes compared to historical data across all Key Performance Indicators, resulting in a total of 12,000 sales, contributing to TL 2.6 million.
2. The average expenditure per customer in January 2023 was TL 667, with a total customer count of 3.9k.
3. Female customers dominate the customer base, making up 60%. The age distribution is relatively balanced, with adults aged 25 to 64 comprising the majority, while customers over 65 represent only 9% of the total.
4. The top three categories by sales count are Clothing (34%), Cosmetics (17%), and Food & Beverage (15%). However, the top three categories by sales revenue are Clothing (45%), Shoes (26%), and Technology (23%).
5. Shoes and Technology achieve higher sales amounts despite not being in the top three for sales count, due to their high average sales amounts per item (TL 1,050 for Technology and TL 600 for Shoes).
6. The top three shopping malls 
