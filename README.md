# Café Sales Analysis

## 📊 Project Overview

This project performs a comprehensive **sales analysis** for a café using transactional data. The dataset includes information about:

- Items sold (`Item`)
- Quantity sold (`Quantity`)
- Total revenue (`Total Spent`)
- Payment methods (`Payment Method`)
- Transaction dates (`Transaction Date`)

The analysis provides actionable insights into **monthly revenue trends**, **top-selling items**, **payment method usage**, and **overall sales performance**.

---

## 🗂 Dataset

| Column Name        | Description                                        |
|-------------------|--------------------------------------------------|
| Transaction ID     | Unique ID for each transaction                  |
| Item               | Name of the item sold                             |
| Quantity           | Number of units sold                              |
| Price Per Unit     | Price of one unit of the item                     |
| Total Spent        | Total amount spent in the transaction            |
| Payment Method     | Payment type used (Cash, Credit Card, Digital Wallet) |
| Location           | Purchase location (Takeaway, In-store)           |
| Transaction Date   | Date of transaction                               |

> **Note:** Only one year of data is available, but monthly trends are analyzed.

---

## 🔍 Analysis Performed

1. **Revenue Analysis**
   - Total revenue by month
   - Total quantity sold by month
   - Revenue contribution by item

2. **Item-Level Analysis**
   - Most sold items by quantity
   - Highest revenue-generating items
   - Item sales trends across months

3. **Payment Method Analysis**
   - Transaction count by payment method
   - Revenue per payment method
   - Monthly trends for each payment method

4. **Cross Analysis**
   - Item vs Month sales
   - Payment method vs Month revenue

5. **Outlier Detection**
   - Unusually high or low transaction amounts

6. **Visualizations**
   - Bar charts for revenue per month and top items
   - Pie charts for payment method distribution
   - Line charts showing monthly trends

---

## 📈 Key Insights

- Identified **months with highest sales revenue**  
- Determined **top-selling items** and their contribution to revenue  
- Analyzed **customer payment preferences**  
- Highlighted **anomalous transactions** for further review  

---

## 💻 Tools & Libraries

- Python 3  
- Jupyter Notebook / Google Colab  
- pandas, numpy  
- matplotlib, seaborn  

