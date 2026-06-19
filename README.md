# DecodeLabs-Internship
Deliverables for Data Analytics Project

Dataset Included

File: Cleaned Dataset for Data Analytics.xlsx

## Project Overview
This repository contains the cleaned dataset and documentation for my Data Analytics internship project. It demonstrates data cleaning, formatting, and preparation for analysis.

## Dataset Included
- File: `Cleaned Dataset for Data Analytics.xlsx`
- Description: Final cleaned dataset prepared for analytics tasks (customer orders, payment methods, coupons, referral sources, and total prices).

Description: Final cleaned dataset prepared for analytics tasks (customer orders,Customer ID, Order ID, Tracking Numbers, payment methods, coupons, referral sources, and total prices).

Cleaning Steps:

Converted all General formats to proper data types:

1-IDs (OrderID, CustomerID, TrackingNumber) → Text

2-Dates → Date

3-Quantities → Whole Number (0 decimals)

4-Prices → Number (2 decimals)

5-Categorical fields (PaymentMethod, OrderStatus, Coupon, ReferralSource) → Text
Standardized categorical values:

6-PaymentMethod → Credit Card, Debit Card, Cash, Online, Gift Card

7-OrderStatus → Shipped, Delivered, Cancelled, Returned, Pending

8-Coupon → NoCoupon, SAVE10, FREESHIP, WINTER15

9-ReferralSource → Instagram, Facebook, Email, Google, Referral

Ensured logical consistency:

10-TotalPrice = Quantity × UnitPrice (rounded to 2 decimals)

11-TrackingNumber present only for Shipped/Delivered orders

12-Removed helper columns and ensured final dataset is analysis‑ready.
## How to Use
- Open the dataset in Excel for quick inspection.  
- Import into Power BI or Tableau for visualization.  
- Use Python (pandas) or SQL for deeper analysis.  

