# DecodeLabs-Internship
Deliverables for Data Analytics Project
Dataset Included
File: Cleaned Dataset for Data Analytics.xlsx

Description: Final cleaned dataset prepared for analytics tasks (customer orders,Customer ID, Order ID, Tracking Numbers, payment methods, coupons, referral sources, and total prices).

Cleaning Steps
Converted all General formats to proper data types:

IDs (OrderID, CustomerID, TrackingNumber) → Text

Dates → Date

Quantities → Whole Number (0 decimals)

Prices → Number (2 decimals)

Categorical fields (PaymentMethod, OrderStatus, Coupon, ReferralSource) → Text
Standardized categorical values:

PaymentMethod → Credit Card, Debit Card, Cash, Online, Gift Card

OrderStatus → Shipped, Delivered, Cancelled, Returned, Pending

Coupon → NoCoupon, SAVE10, FREESHIP, WINTER15

ReferralSource → Instagram, Facebook, Email, Google, Referral

Ensured logical consistency:

TotalPrice = Quantity × UnitPrice (rounded to 2 decimals)

TrackingNumber present only for Shipped/Delivered orders

Removed helper columns and ensured final dataset is analysis‑ready.
