# Task 1: Data Collection & Dataset Understanding
**Author:** Besong Justin | **Internship:** Decode Labs Data Analytics Programme  
**Batch:** 15th May 2026 – 15th June 2026

---

## 1. Dataset Overview

The dataset used for this project is a fictional e-commerce sales dataset provided as part of the Decode Labs Data Analytics Internship. It simulates real-world transactional data from an online store, capturing customer orders across multiple products, payment methods, and referral sources.

- **File format:** CSV / Excel (.xlsx)
- **Total rows:** 1,200 (each row represents one order)
- **Total columns:** 14
- **Date range:** January 2023 – June 2025

---

## 2. Column Names and Data Types

| Column | Data Type | Description |
|---|---|---|
| OrderID | Text | Unique identifier for each order (e.g. ORD200000) |
| Date | Date | The date the order was placed (YYYY-MM-DD format) |
| CustomerID | Text | Unique identifier for each customer (e.g. C72649) |
| Product | Text | Name of the product ordered |
| Quantity | Number (Integer) | Number of units ordered per transaction |
| UnitPrice | Number (Decimal) | Price of a single unit of the product |
| ShippingAddress | Text | Customer's shipping address |
| PaymentMethod | Text | Method used to pay for the order |
| OrderStatus | Text | Current status of the order |
| TrackingNumber | Text | Shipment tracking reference (e.g. TRK37947903) |
| ItemsInCart | Number (Integer) | Total number of items in the customer's cart at checkout |
| CouponCode | Text | Discount coupon applied to the order (if any) |
| ReferralSource | Text | Channel through which the customer discovered the store |
| TotalPrice | Number (Decimal) | Total monetary value of the order (Quantity × UnitPrice) |

---

## 3. Dataset Size and Features

| Feature | Detail |
|---|---|
| Number of rows | 1,200 |
| Number of columns | 14 |
| Numeric columns | Quantity, UnitPrice, ItemsInCart, TotalPrice |
| Date columns | Date |
| Text/Categorical columns | OrderID, CustomerID, Product, ShippingAddress, PaymentMethod, OrderStatus, TrackingNumber, CouponCode, ReferralSource |
| Missing values | 309 missing values in CouponCode (orders with no coupon applied) |
| Duplicate rows | None |

### Unique Values in Categorical Columns

| Column | Unique Values |
|---|---|
| Product | Laptop, Monitor, Phone, Tablet, Chair, Desk, Printer (7 products) |
| OrderStatus | Delivered, Shipped, Pending, Cancelled, Returned |
| PaymentMethod | Online, Cash, Credit Card, Debit Card, Gift Card |
| ReferralSource | Instagram, Email, Google, Facebook, Referral |
| CouponCode | SAVE10, FREESHIP, WINTER15, NO COUPON |

---

## 4. What the Data Represents

This dataset represents the transactional records of an e-commerce store operating between January 2023 and June 2025. Each row captures a single customer order — from the product purchased and the price paid, to how the customer found the store and what happened to their order after it was placed.

The data can be used to answer key business questions such as:
- Which products generate the most revenue?
- Which months have the highest order volumes?
- What percentage of orders are successfully delivered?
- Which referral channels drive the most sales?
- Are there any unusually high-value orders worth flagging?

It provides a realistic simulation of the kind of data a business analyst would encounter in an e-commerce or retail environment, making it suitable for practising data cleaning, exploratory analysis, SQL querying, and visual reporting.

---

## 5. Tools Used for This Project

- Microsoft Excel — initial data exploration and cleaning
- SQL Server Management Studio (SSMS) — data cleaning and querying
- Microsoft Power BI — data visualization and dashboard building

---

## Author
**Besong Justin**
- LinkedIn: [linkedin.com/in/besong-justin](https://linkedin.com/in/besong-justin)
- Twitter/X: [@Justin_analyst](https://twitter.com/Justin_analyst)
