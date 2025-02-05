# iGnosis-assignment

# Customer Segmentation & Bestselling Products Analysis

## Overview
This project analyzes transaction data to:
- Identify **loyal customer segments** based on spending behavior.
- Determine **the top-selling products**.
- Provide insights into **why customers prefer certain brands**.

This analysis helps businesses optimize marketing strategies and improve product positioning.

## Dataset
The analysis is based on two datasets:
1. **purchase_behaviour.csv** - Contains customer details:
   - `LYLTY_CARD_NBR`: Customer ID
   - `LIFESTAGE`: Customer's life stage (e.g., young families, retirees)
   - `PREMIUM_CUSTOMER`: Customer spending level (Premium/Mainstream/Budget)

2. **transaction_data.csv** - Contains transaction details:
   - `DATE`: Date of purchase
   - `STORE_NBR`: Store ID
   - `LYLTY_CARD_NBR`: Customer ID (links with purchase_behaviour.csv)
   - `TXN_ID`: Transaction ID
   - `PROD_NBR`: Product ID
   - `PROD_NAME`: Product name
   - `PROD_QTY`: Quantity purchased
   - `TOT_SALES`: Total amount spent

## Key Findings
- The **top 3 bestselling products** are:
  1. **Dorito Corn Chp Supreme**
  2. **Kettle Mozzarella Basil & Pesto**
  3. **Kettle Tortilla ChpsHny&Jlpno Chili** 	

- **Loyal customers** are mainly:
  - **MIDAGE SINGLES/COUPLES** customers who spend the most & customers who buy frequently.
  - They prefer **Kettle, Smiths, Pringles, Doritos, Twisties** brands due to **Marketing**.

- **Marketing Strategy Recommendation:**
  - Offer **loyalty discounts** to premium customers.
  - Create **bulk purchase deals** for budget buyers.
