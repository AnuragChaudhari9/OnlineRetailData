# OnlineRetailData
This dataset is available on Kaggle under "Ecommerce Data," and is centered around online retail transactions. This dataset primarily contains transactional data from an e-commerce store based in the UK, recorded between December 2010 and December 2011. The data includes 541,909 records of purchases made by customers from various countries. Each record represents a single transaction, detailing the invoice number, stock code (product ID), product description, quantity purchased, invoice date, unit price, and customer ID.

## Sample Ecommerce Data

Here is a sample of the data from the e-commerce dataset:

| InvoiceNo | StockCode | Description                             | Quantity | InvoiceDate         | UnitPrice | CustomerID | Country        |
|-----------|-----------|-----------------------------------------|----------|---------------------|-----------|------------|----------------|
| 536365    | 85123A    | WHITE HANGING HEART T-LIGHT HOLDER      | 6        | 12-01-2010 08:26    | 2.55      | 17850      | United Kingdom |
| 536365    | 71053     | WHITE METAL LANTERN                     | 6        | 12-01-2010 08:26    | 3.39      | 17850      | United Kingdom |
| 536365    | 84406B    | CREAM CUPID HEARTS COAT HANGER          | 8        | 12-01-2010 08:26    | 2.75      | 17850      | United Kingdom |
| 536365    | 84029G    | KNITTED UNION FLAG HOT WATER BOTTLE     | 6        | 12-01-2010 08:26    | 3.39      | 17850      | United Kingdom |
| 536365    | 84029E    | RED WOOLLY HOTTIE WHITE HEART           | 6        | 12-01-2010 08:26    | 3.39      | 17850      | United Kingdom |
| 539434    | 90201A    | PURPLE ENAMEL FLOWER RING               | 1        | 12/17/2010 14:41    | 2.96      |            | United Kingdom |
| 539434    | 90202A    | PURPLE ENAMEL FLOWER HAIR TIE           | 1        | 12/17/2010 14:41    | 2.96      |            | United Kingdom |
| 539434    | 90206A    | GOLD DIAMANTE STAR BROOCH               | 1        | 12/17/2010 14:41    | 5.09      |            | United Kingdom |
| 539434    | 90214E    | LETTER "E" BLING KEY RING               | 1        | 12/17/2010 14:41    | 0.85      |            | United Kingdom |
| 539434    | 90214H    | LETTER "H" BLING KEY RING               | 1        | 12/17/2010 14:41    | 0.85      |            | United Kingdom |

## Sample Data from Cleaned Dataset (data_cleaned)

Here is a sample of the data from the cleaned dataset:

| Quantity | InvoiceDate | UnitPrice |
|----------|-------------|-----------|
|    6     | 12-01-2010  |    2.55   |
|    6     | 12-01-2010  |    3.39   |
|    8     | 12-01-2010  |    2.75   |
|    6     | 12-01-2010  |    3.39   |
|    6     | 12-01-2010  |    3.39   |
|    2     | 12-01-2010  |    7.65   |
|    6     | 12-01-2010  |    4.25   |
|    6     | 12-01-2010  |    1.85   |
|    6     | 12-01-2010  |    1.85   |

Data Wrangling was done in Excel which included getting dates in proper DD-MM-YYYY format. Removed unwanted columns.

## Power BI
![Power BI Dashboard](https://github.com/AnuragChaudhari9/OnlineRetailData/blob/main/E-commerce%20Sales%20UK.jpg)
Download the Power BI report file: [dashboard.pbix](https://github.com/AnuragChaudhari9/OnlineRetailData/blob/main/Sales.pbix)

The revenue column was calculated by multiplying quantity with unit price. This was then used to plot crucial plots to gain insights into Total Revenue trend per month, Total Revenue vs Price of the item, and quantities sold per year.

The Revenue was highest in January 2010 and has a slight decreasing trend overall, coming into December 2011. Total transactions in 2011 were much higher than in 2010. Items priced less than £50 generated most revenue (97.92%).
