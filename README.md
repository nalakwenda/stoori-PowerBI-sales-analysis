#  Stoori

## 📌 Overview
This project analyzes sales, customer, and inventory data from a **Stoori** to uncover insights that drive better decision-making.  
The goal is to help the business understand its **top products, seasonal demand, customer behavior, and operational efficiency**, ultimately improving profitability and growth.

---

##  Executive Summary
This project examines the **Mexico Toy Sales** dataset—a fictional but realistic simulation of daily sales, inventory, product, and store-level data for a Mexican toy store chain, Maven Toys, spanning 2022–2023. Our goal is to surface strategic insights into:

- **Revenue drivers**: Which product categories and stores generate the most profit.
- **Seasonality**: Patterns tied to key sale periods (e.g., Christmas, Día de Reyes, Children’s Day).
- **Stock management**: Instances of stockouts leading to lost opportunities, and inventory tied up in underperforming products.
- **Operational efficiency**: Inventory turnover rates and cash flow implications.


---

## 🗂️ Data Structure Overview  

| **Table**   | **Field**          | **Description**                                                   |
|-------------|--------------------|-------------------------------------------------------------------|
| **Products** | Product_ID        | Product ID                                                        |
|             | Product_Name       | Product name                                                      |
|             | Product_Category   | Product category                                                  |
|             | Product_Cost       | Product cost ($USD)                                               |
|             | Product_Price      | Product retail price ($USD)                                       |
| **Inventory** | Store_ID         | Store ID                                                          |
|             | Product_ID         | Product ID                                                        |
|             | Stock_On_Hand      | Stock quantity of the product in the store (inventory)            |
| **Stores**   | Store_ID          | Store ID                                                          |
|             | Store_Name         | Store name                                                        |
|             | Store_City         | City in Mexico where the store is located                         |
|             | Store_Location     | Location in the city where the store is located                   |
|             | Store_Open_Date    | Date when the store was opened                                    |
| **Sales**    | Sale_ID           | Sale ID                                                           |
|             | Date               | Date of the transaction                                           |
|             | Store_ID           | Store ID                                                          |
|             | Product_ID         | Product ID                                                        |
|             | Units              | Units sold                                                        |
| **Calendar** | Date              | Calendar date                                                     |



## 🔗 Data Source
(https://mavenanalytics.io/data-playground/mexico-toy-sales)

## ❓ Business Questions & Findings

-



