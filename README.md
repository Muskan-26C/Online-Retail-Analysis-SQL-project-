# SQL Online Retail Sales Project

## Subtitle: Analyzing Online Retail Sales Data with SQL

## Project Overview 📋

This is an end-to-end SQL project, from dataset creation and seeding to problem statement creation and data analysis through SQL. We created a fake database in MySQL consisting of 4 tables (sales, customers, suppliers, and products). The data was auto-populated randomly through AI, and then we conducted a sales and customer insights analysis.

---

## Dataset (Tables) 🗂️

This project consists of four tables.: `Sales`, `Customers`, `Suppliers`, `Products`

---

### Data Relationships 🔗

**Sales Table**
- `transaction_id` (Primary Key)
- `customer_id` (Foreign Key to Customers table)
- `product_id` (Foreign Key to Products table)
- `supplier_id` (Foreign Key to Suppliers table)

**Customers Table**
- `customer_id` (Primary Key)

**Products Table**
- `product_id` (Primary Key)
- `supplier_id` (Foreign Key to Suppliers table)

**Suppliers Table**
- `supplier_id` (Primary Key)
  
---

### Conclusions 💡

#### Sales Analysis:
- **Main Revenue Sources**: Electronics and Accessories are the top product categories.
- **Seasonal Trends**: Higher sales in the first quarter of the year.
- **Top Suppliers**: Our top 3 suppliers are Gadgets4U, ElectronicsRUs, and FashionTrends.

#### Customer Analysis:
- **Gender Distribution**: Sales distribution is 50/50 between genders.
- **Profitable Customer Demographics**: Profitable customers (3-5 purchases) are aged between 28-40 years old.


