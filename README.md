# Exploratory Data Analysis and Data cleansing

This repository for exploratory data analysis and data cleansing.

The issues to address in these files are:
* Detecting and fixing errors. Errors can be syntactic, semantic or coverage.
* Detecting and removing outlier rows w.r.t. delivery_fee
* Imputing missing values

## About the dataset

The dataset contains Food Delivery data from a restaurant in Melbourne, Australia. The restaurant has three branches around CBD area. All three branches share the same menu but they have different management so they operate differently.

| Attribute               | Description                                                                |
| ----------------------- | -------------------------------------------------------------------------- |
| order_id                | A unique id for each order                                                 |
| date                    | The date the order was made in YYYY-MM-DD format                           |
| time                    | The time the order was made hh:mm:ss format                                |
| order_type              | One of 3 types of order: Breakfast, Lunch or Dinner                        |
| branch_code             | The branch code in which the order was made. One of 3 branches: BK, NS, TP |
| order_items             | A list of tuples of the form: (Item ordered, Quantity ordered)             |
| order_price             | Total order price                                                          |
| customer_lat            | Latitude of customer coming from nodes.csv                                 |
| customer_lon            | Longitude of customer coming from nodes.csv                                |
| customerHasloyalty?     | Boolean variable representing if customer has loyalalty card               |
| distance_to_customer_KM | Shortest distance between branch and customer node                         |
| delivery_fee            | Delivery fee for an order                                                  |

## Setup

```
pip install requirements.txt
```