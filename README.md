# Basket-Market-Analysis
#  E-commerce Sales Analysis using Python

This project focuses on **Market Basket Analysis** using **Apriori** and **FP-Growth algorithms** to identify frequent product combinations and discover valuable association rules in e-commerce sales data.  
The goal is to uncover purchasing patterns that can enhance cross-selling strategies, optimize inventory, and support data-driven marketing decisions.

---

##  Project Overview

The dataset contains detailed transactional records from an online retail business, including:

- **Order Details:** Order ID, Order Date, Ship Mode  
- **Customer Information:** Customer ID, Segment, Location  
- **Product Details:** Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit  

**Data Preparation Steps:**
- Split *Location* into **Country** and **State**
- Checked and handled missing values
- Performed basic statistical and exploratory analysis on sales and profit data

---

##  Analysis Techniques

- **Apriori Algorithm** – Identifies frequent itemsets based on minimum support and confidence  
- **FP-Growth Algorithm** – Efficient alternative for discovering frequent product combinations  
- **Association Rules** – Extracted using *lift*, *confidence*, and *support* metrics to detect strong relationships

---

##  Key Insights

- Top frequent products: **Binders**, **Paper**, **Furnishings**, **Phones**, and **Storage**  
- Example Rules Discovered:
  - Customers buying **Binders** often purchase **Appliances**  
  - **Furnishings** are frequently bought with **Phones** or **Storage**
- Lift values greater than 1 indicate meaningful product associations useful for recommendation systems

---

##  Technologies Used

- **Python**
- **Pandas**, **NumPy** – Data manipulation  
- **Matplotlib**, **Seaborn** – Visualization  
- **mlxtend** – Apriori & FP-Growth algorithms  

---

##  Business Applications

- **Cross-Selling:** Recommend related products frequently bought together  
- **Inventory Optimization:** Identify which products should be stocked together  
- **Marketing Campaigns:** Create targeted bundle offers and promotions  
