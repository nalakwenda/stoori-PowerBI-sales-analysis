#  Stoori

## 📌 Overview
This project analyzes sales, customer, and inventory data from a **Stoori** to uncover insights that drive better decision-making.  
The goal is to help the business understand its **top products and customer behavior**, ultimately improving profitability and growth.

---
![Stories Sales Summary](https://github.com/user-attachments/assets/c61c5d74-2539-451f-822f-ded832880b55)
![Stoorie Products](https://github.com/user-attachments/assets/960e9ced-3f5b-4313-a354-51107b95c86a)
![Stoori Sales Location](https://github.com/user-attachments/assets/d0b328c7-dc1f-4a43-8dc4-ad2b5c4f8015)

---

##  Executive Summary
This project examines the **Mexico Toy Sales** dataset—a fictional but realistic simulation of daily sales, inventory, product, and store-level data for a Mexican toy store chain, Maven Toys, spanning 2022–2023. Our goal is to surface strategic insights into:

- **Revenue drivers**: Which product categories and stores generate the most profit.


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

---

## 🔗 Data Source
(https://mavenanalytics.io/data-playground/mexico-toy-sales)
---
## ❓ Business Questions & Findings

### *** 1.  What was the total revenue? ***
- $ 14,444,572.35

### *** 2.  What was the total profit? *** 
- $ 40,414,029

### *** 3.  What was the total number units sold? ***
- 1090565

### *** 4.  Which 10 cities have the highest sales? ***
***Findings***

| Store_City         | Total Profit ($USD) |
|-------------------|-------------------|
| Cuidad de Mexico   | 465,558           |
| Guadalajara        | 368,930           |
| Monterrey          | 346,729           |
| Hermosillo         | 263,608           |
| Puebla             | 229,694           |
| Guanajuato         | 235,047           |
| Mexicali           | 175,048           |
| Xalapa             | 163,720           |
| Saltillo           | 163,248           |
| Toluca             | 162,702           |

### *** 5.  Which 10 cities have the lowest sales sales? ***
***Findings*** 
| Store_City           | Total Profit ($USD) |
|---------------------|-------------------|
| Chilpancingo         | 66,558            |
| Tuxtla Gutierrez     | 65,787            |
| Merida               | 64,399            |
| Culiacan             | 63,959            |
| Pachuca              | 63,989            |
| Durango              | 62,673            |
| Zacatecas            | 59,160            |
| Oaxaca               | 59,618            |
| La Paz               | 57,407            |
| Cuernavaca           | 56,811            |

### *** 6. How much revenue did each product category generate? ***
***Findings***

| Product_Category     | Total Revenue ($USD) |
|---------------------|--------------------|
| Toys                | 5,093,241.00       |
| Art & Crafts        | 2,705,364.26       |
| Electronics         | 2,246,771.25       |
| Games               | 2,226,836.27       |
| Sports & Outdoors   | 2,172,359.57       |


### *** 7. Which which product had the highest revenue? ***
 - Lego Bricks

### *** 8. Which which product had the lowest revenue? ***
- Uno Game Card

### *** 9.  Which 10 products have the hightest sales? ***
***Findings*** 
| Product_ID | Product_Name   | Total Sales ($USD) |
|------------|----------------|--------------------|
| 7          | Dart Gun       | 505,092.12         |
| 24         | Nerf Gun       | 530,594.57         |
| 2          | Animal Figures | 507,766.11         |
| 8          | Deck Of Cards  | 587,397.66         |
| 30         | Rubik's Cube   | 912,983.28         |
| 6          | Colorbuds      | 1,564,476.32       |
| 31         | Splash Balls   | 541,629.52         |
| 1          | Action Figure  | 926,748.42         |
| 18         | Lego Bricks    | 2,388,882.63       |
| 19         | Magic Sand     | 968,962.02         |

### *** 10.  Which 10 products have the lowest sales? ***
***Findings***
| Product_ID | Product_Name            | Total Sales ($USD) |
|------------|-------------------------|--------------------|
| 32         | Supersoaker Water Gun   | 101,827.07         |
| 12         | Foam Disk Launcher      | 91,363.80          |
| 22         | Monopoly                | 67,666.15          |
| 23         | Mr. Potatohead          | 85,963.95          |
| 28         | Playfoam                | 45,696.42          |
| 20         | Mini Basketball Hoop    | 66,148.53          |
| 35         | Uno Card Game           | 21,652.90          |
| 4          | Chutes & Ladders        | 49,738.71          |
| 33         | Teddy Bear              | 83,343.84          |
| 5          | Classic Dominoes        | 44,665.29          |

