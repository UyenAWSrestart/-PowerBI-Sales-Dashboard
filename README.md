# -PowerBI-Sales-Dashboard

Author: [Uyen Nguyen]  
Date: November 2024  
Tools Used: Power BI 

---

## 📑 Table of Contents  
I. [Introduction](#i-introduction)  
II. [Dataset Description](#ii-dataset-description)  
III.[Design Thinking Process](#iii-design-thinking-process)  
IV.[Power BI Visualization](#iv-power-bi-visualization)  
V. [Final Conclusion & Recommendations](#v-final-conclusion--recommendations)

## I. Introduction

Based on the AdventureWorks database, this project analyzes the manufacturing process of a bicycle manufacturer using Power BI.
### The objective:
- Ensure products are delivered on time.
- Minimize scrapped products.
  
### Stakeholders: 
The insights gained will empower the following stakeholders to make informed strategic decisions and enhance overall business operations:
- Data analysts & business analysts
- Production managers
- Decision-makers & executives

### Business Questions:
- Why does the company fail to deliver these products on time?
- What strategies can be implemented to minimize scrapped products?
  

## II. Dataset Description

- Source: The Bicycle Manufacturer dataset is stored in a public Google BigQuery dataset named "adventureworks2019"
- Data Structure:
  There are 5 tables that we will work on it.

| Table                | Type                                                                                                                      |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| Fact_Product         | Details of product sold or used in production.                                                                            |
| Fact_Workorder       | Contains order details, including product ID, scrapped products quantity, due date, start date, and end date.             |
| Dim_ScrapReason      | Reason for scrapped products.                                                                                             |
| Dim_WorkOrderRouting | Lists only on-time and late orders. Details of location, actual order and delivery time for each work order and product.  |
| Dim_Location         | Lists each stage in the production process.                                                                               |


-  Data relationships: (bổ sung data modelling)





## III. Design Thinking Process

### 1. Empathize

<img width="1247" alt="Screen Shot 2025-03-06 at 10 34 41 AM" src="https://github.com/user-attachments/assets/e5ae3da8-8c5d-4b25-b8c6-cdeeb54b6a27" />

### 2. Define point of view



### 3. Ideate




Next, I proceeded with Step 4 - Prototype and Review multiple times and achieved the final result, which will be presented in the following section as a dashboard.



## IV. Power BI Visualization
### Dashboard 1 Preview



### Dashboard 2 Preview



### Dashboard 3 Preview

<img width="1066" alt="Screen Shot 2025-03-05 at 2 10 57 PM" src="https://github.com/user-attachments/assets/27838d22-69e1-40e3-953f-0b69deb91c78" />

### Dashboard 4 Preview



## V. Final Conclusion & Recommendations 

The analysis has revealed some inefficiencies in manufacturing performance. The most critical problems are:



These issues directly impact manufacturing efficiency, delivery performance, and cost control, making them a priority for process improvement.

**Recommendations:**

