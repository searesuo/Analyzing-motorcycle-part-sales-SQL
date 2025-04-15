# 🏍️ Analyzing Motorcycle Part Sales with SQL

This project explores wholesale motorcycle part sales data across three warehouse locations to provide key revenue insights. Using SQL, we break down **monthly net revenue by product line and warehouse** to help the company understand its sales trends and make informed, data-driven decisions.

---

## 🎯 Project Objectives

In this project, we aim to:

1. 📦 Analyze **net revenue** across different product lines
2. 🗓️ Track **monthly sales performance** over time
3. 🏢 Compare sales across the company's **three warehouse sites**
4. 📊 Generate insights for **decision-making and revenue optimization**

---

## 🗃️ Data Overview

The dataset is structured into multiple relational tables. A typical schema might include:

### `sales`
| Column         | Description                             |
|----------------|-----------------------------------------|
| `sale_id`      | Unique sale transaction ID              |
| `product_id`   | Foreign key referencing `products`      |
| `warehouse_id` | Foreign key referencing `warehouses`    |
| `sale_date`    | Date of sale                            |
| `
