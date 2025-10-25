# Data Dictionary - Superstore Sales Dataset

## Dataset Overview
- **Source**: Kaggle - Superstore Dataset
- **Records**: ~10,000 transactions
- **Time Period**: 2014-2017
- **Business Type**: Retail (Office supplies, furniture, technology)

## Column Descriptions

| Column Name | Data Type | Description |
|------------|-----------|-------------|
| Row ID | Integer | Unique identifier for each row |
| Order ID | String | Unique order identifier |
| Order Date | Date | Date when order was placed |
| Ship Date | Date | Date when order was shipped |
| Ship Mode | String | Shipping method (Standard, Second Class, First Class, Same Day) |
| Customer ID | String | Unique customer identifier |
| Customer Name | String | Customer's full name |
| Segment | String | Customer segment (Consumer, Corporate, Home Office) |
| Country | String | Country of delivery |
| City | String | City of delivery |
| State | String | State of delivery |
| Postal Code | Integer | Postal code of delivery location |
| Region | String | Geographic region (West, East, Central, South) |
| Product ID | String | Unique product identifier |
| Category | String | Product category (Furniture, Office Supplies, Technology) |
| Sub-Category | String | Product sub-category |
| Product Name | String | Full product name |
| Sales | Float | Sales amount in USD |
| Quantity | Integer | Number of units sold |
| Discount | Float | Discount percentage (0-0.8) |
| Profit | Float | Profit amount in USD (can be negative) |

## Key Notes
- All monetary values are in USD
- Negative profit indicates a loss on that transaction
- Discount is represented as decimal (0.2 = 20% discount)
- Missing postal codes exist for some records