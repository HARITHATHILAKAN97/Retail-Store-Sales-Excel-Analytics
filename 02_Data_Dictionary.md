# Retail Store Sales — Data Dictionary

## Source Table

This data dictionary is based **only on the `Retail Store Sales` table** from the Excel project.

## Data Dictionary

| Column Name | Description | Data Type | Example Value | Unique Values | Missing Values | Business Role |
|---|---|---|---|---:|---:|---|
| Order ID | Unique identifier for each order/transaction. | Integer | 1 | 555 | 0 | Identifier |
| Customer Name | Name of the customer associated with the order. | Text | Allison Hill | 499 | 0 | Customer Attribute |
| Product Category | Category of the product purchased. | Text | Electronics | 5 | 0 | Product Attribute |
| Product Name | Name of the product purchased. | Text | Smartphone | 25 | 0 | Product Attribute |
| Order Date | Date on which the order was placed. | Date | 20-May-2024 | 389 | 0 | Date |
| Delivered Date | Date on which the order was delivered. | Date | 24-May-2024 | 391 | 0 | Date |
| Quantity | Number of units purchased in the order. | Integer | 4 | 10 | 0 | Measure |
| Unit Price | Selling price of one unit of the product. | Decimal | 238.0 | 404 | 0 | Measure |
| Status | Order status indicating whether the order was completed or returned. | Text | Completed | 2 | 0 | Order Attribute |
| Country | Country associated with the customer/order. | Text | Australia | 7 | 0 | Geographic Attribute |
| Payment Method | Payment method used for the order. | Text | Mobile Money | 4 | 0 | Transaction Attribute |
| Year | Year extracted from the Order Date for time-based analysis. | Integer | 2024 | 2 | 0 | Calculated Date Attribute |
| Month | Month extracted from the Order Date for monthly analysis. | Text | May | 12 | 0 | Calculated Date Attribute |
| Day | Day of the week extracted from the Order Date. | Text | Mon | 7 | 0 | Calculated Date Attribute |
| Delivery time | Number of days between Order Date and Delivered Date. | Integer | 4 | 20 | 0 | Calculated Measure |
| Total Cost | Total calculated cost associated with the quantity purchased. | Integer | 714 | 509 | 0 | Calculated Measure |
| Sales Revenue | Revenue generated from the order, based on quantity and unit price. | Decimal | 952.0 | 514 | 0 | Calculated Measure |
| Net Profit | Profit calculated from Sales Revenue after deducting Total Cost. | Decimal | 238.0 | 474 | 0 | Calculated Measure |

## Table Summary

- **Source Table:** Retail Store Sales
- **Number of Records:** 555
- **Number of Columns:** 18
- **Missing Values:** 0
- **Order ID Uniqueness:** 555 unique Order IDs across 555 records
- **Purpose:** Reference guide for the fields used in the Excel retail sales analysis.

## Notes

- The dictionary includes only fields present in the `Retail Store Sales` table.
- Fields from other worksheets such as Cost Per Unit, KPI Analysis, Statistical Analysis, or Dashboard are not included.
- Calculated fields such as Year, Month, Day, Delivery time, Total Cost, Sales Revenue, and Net Profit are documented because they are present in the Retail Store Sales table.