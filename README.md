# Reporting on sales data

## 📖 Background
You work in the accounting department of a company that sells motorcycle parts. The company operates three warehouses in a large metropolitan area.

You’ve recently learned data manipulation and plotting, and suggest helping your colleague analyze past sales data. Your colleague wants to capture sales by payment method. She also needs to know the average unit price for each product line.

## 💾 The data

#### The sales data has the following fields:
- "date" - The date, from June to August 2021.
- "warehouse" - The company operates three warehouses: North, Central, and West.
- "client_type" - There are two types of customers: Retail and Wholesale.
- "product_line" - Type of products purchased.
- "quantity" - How many items were purchased.
- "unit_price" - Price per item sold.
- "total" - Total sale = quantity * unit_price.
- "payment" - How the client paid: Cash, Credit card, Transfer.

## **Findings**

### 1. The highest total sales is made by bank transfer payment method. Furthermore, this payment method is made by only wholesale clients who usually made large purchases from our company. Retail clients who visited the warehouses made payment using either credit cards or cash.

### 2. The top 3 products that have the highest average unit price are _engine, frame & body, and suspension & traction_. Engine has the highest unit average unit price but its total sales is ranked 5 out of the 6 products sold. This shows that engine has low sales revenue.

### 3. Total sales for warehouse in Central region is increasing and the highest among the 3 warehouses while warehouse in West region has declining sales.
