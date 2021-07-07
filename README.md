# ManyGiftsUK recommender system

## Business Situation 

ManyGiftsUK is a UK-based and registered non-store online retailer with some 80 members of staff. The company was established in 1981 mainly selling unique all-occasion gifts.

## Metadata

| Name                        | Meaning                                                                                                                                                        |
|-----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| InvoiceNo                   | Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.    |
| StockCode                   | Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.                                                            |
| Description                 | Product (item) name. Nominal.                                                                                                                                  |
| Quantity                    | The quantities of each product (item) per transaction. Numeric.                                                                                                |
| InvoiceDate                 | Invoice Date and time. Numeric, the day and time when each transaction was generated.                                                                          |
| UnitPrice                   | Unit price. Numeric, Product price per unit in pounds.                                                                                                         |
| CustomerID                  | Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.                                                                        |
| Country                     | Country name. Nominal, the name of the country where each customer resides.                                                                                    |
## Expected Outcomes

1. Explore the data and build models to answer the problems:
    1. Recommender system: the website homepage offers a wide range of products the user might be interested on
    2. Cold start: offer relevant products to new customers
2. Implement adequate evaluation strategies and select an appropriate quality measure
3. In the deployment phase, elaborate on the challenges and recommendations in implementing the recommender system
