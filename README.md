# Istanbul Shopping Malls Sales Analysis Dashboard
- The objective of this project is to monitor key sales metrics such as sales volume and analyze customer data to inform better business decisions. Specifically, it aims to:
  - Enable the sales and management teams to track progress towards goals, identify top-performing products, and recognize high-performing sales representatives
  - Enhance the ability to tailor sales strategies to meet customer needs based on demographic data, thereby improving customer satisfaction and increasing loyalty

## References:
**Python Version:** 3.10 <br />
**Packages:** numpy, pandas, datetime <br />
**Data Source:** [Customer Shopping Dataset - Retail Sales Data](https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset) <br />
**Data Preprocesing ipynb File:** [Kaggle_Customer_Shopping_Dataset_Data_Cleaning.ipynb](https://github.com/rnlow22/shopping_mall_sales_dashboard/blob/main/Kaggle_Customer_Shopping_Dataset_Data_Cleaning.ipynb) <br />
**Dashboard twbx File:** Only accessible during the demonstration meeting.

## Content:
1. Overview of the Dashboard
2. BI Monthly Reporting for January 2023
3. Key Dashboard Business Insights for January 2023 and the respective Recommended Business Decisions

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
![Screenshot 2024-05-29 at 10 05 10 PM](https://github.com/rnlow22/shopping_mall_sales_dashboard/assets/30455582/e5aab19f-7fab-41f5-b337-a8ed07bbc908)

2. Business users can tailor the number of past periods for trend chart analysis according to their needs.
![Screenshot 2024-05-29 at 10 06 36 PM](https://github.com/rnlow22/shopping_mall_sales_dashboard/assets/30455582/908311f1-65f5-4aac-b61e-2a21a4b5c355)

3. Various trend charts analyzing different Key Performance Indicators can be accessed by selecting from the dropdown menu.
![Screenshot 2024-05-29 at 10 07 32 PM](https://github.com/rnlow22/shopping_mall_sales_dashboard/assets/30455582/2ea29f34-1228-4149-814e-b27bd50926d7)

4. Month-on-Month Growth for Key Performance Indicators is displayed in a single view on the dashboard when selecting Date Type as "Monthly". This functionality extends to Day-on-Day, Week-on-Week, and Year-on-Year Growth as well.
![Screenshot 2024-05-29 at 10 08 41 PM](https://github.com/rnlow22/shopping_mall_sales_dashboard/assets/30455582/1ce4e04a-5afa-4461-b286-4cf66589e12d)

## BI Monthly Reporting for January 2023:
![image](https://github.com/rnlow22/shopping_mall_sales_dashboard/assets/30455582/63def021-41fb-4b26-a06b-27da0e0e2016)

1. January 2023 witnessed consistent **sales volumes** compared to historical data across all Key Performance Indicators, resulting in a total of **12k sales**, contributing to **TL 2.6 million**.
2. The **average sales amount per customer** in January 2023 was TL 667, with a total **customer count** of **3.9k**.
3. **Female** customers dominate the customer base, making up **60%**. The age distribution is relatively balanced, with adults **aged 25 to 64** comprising the **majority**, while customers **over 65** represent **only 9%** of the total.
4. The **top three categories by sales count** are **Clothing (34%)**, **Cosmetics (17%)**, and **Food & Beverage (15%)**. However, the **top three categories by sales amount** are **Clothing (45%)**, **Shoes (26%)**, and **Technology (23%)**.
5. **Shoes** and **Technology** achieve higher sales amounts despite not being in the top three for sales count, due to their **high average sales amounts per item (TL 1,050 for Technology and TL 600 for Shoes)**.
6. The **top three shopping malls** generating the **most sales revenue** in Isbantul are **Kanyon (TL 538k)**, **Mall of Isbantul (TL 528k)** and **Metrocity (TL 424k)**.

## Key Dashboard Business Insights for January 2023:
1. The number of customers **aged 55 to 64** purchasing **Cosmetic products** has gradually increased from **99 to 133 (34%)** over the past 7 months, resulting in a **50% increase in both sales count and sales amount (TL)**.
<p float="center">
  <img src="https://github.com/rnlow22/shopping_mall_sales_dashboard/assets/30455582/b0563fe5-8b3f-410a-a815-c534a5e5a3c8" width="45%" />
  <img src="https://github.com/rnlow22/shopping_mall_sales_dashboard/assets/30455582/3ade4b63-fcc0-4dfd-9ad0-2d92f0bcafa9" width="45%" /> 
  <img src="https://github.com/rnlow22/shopping_mall_sales_dashboard/assets/30455582/6973b600-f550-4e63-a108-2d5af1279abf" width="45%" />
</p>

**Recommended Business Decision**: The marketing team should conduct targeted personalized campaigns for customers aged 55 to 64, specifically focusing on Cosmetic products. Before launching the campaigns, A/B testing should be conducted to evaluate their effectiveness in boosting Sales Revenue (RM).

2. There has been a **sudden drop** in the number of **young adult customers aged 25 to 34** purchasing **Technology products** in January 2023 compared to the past 7 months, **decreasing from 39 to 26 (33%)**. Consequently, there was a corresponding **24% decrease** in **both sales count and sales amount (TL)** in January 2023.
<p float="center">
  <img src="https://github.com/rnlow22/shopping_mall_sales_dashboard/assets/30455582/3dae8337-fd3c-4db7-b8ff-a9236ffe7f6a" width="45%" />
  <img src="https://github.com/rnlow22/shopping_mall_sales_dashboard/assets/30455582/493632ef-c9d7-4979-b0aa-daf8f0a115bc" width="45%" /> 
  <img src="https://github.com/rnlow22/shopping_mall_sales_dashboard/assets/30455582/863a8c32-cdb7-4f6d-bb96-a5697158a2ba" width="45%" />
</p>

**Recommended Business Decision**: The product team should conduct an investigation into the root cause of the sudden drop in Technology product sales among young adult customers aged 25 to 34. Possible causes to investigate include:
  1. Insufficient stocks in the shopping mall
  2. Launch in virtual technology stores
  3. Other potential factors
