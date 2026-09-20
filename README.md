# Repeat Purchase Behaviour Analysis

## Project Overview

This project analyzes customer repeat purchase behaviour using the Olist Brazilian E-Commerce dataset. The objective is to identify first-time and repeat customers, measure repeat purchase rate, compare average order value, and segment customers based on their order frequency.

## Objective

* Measure repeat purchase rate
* Identify repeat customer segments
* Compare first-time and repeat customer AOV
* Analyze customer revenue contribution
* Generate business insights from customer purchasing behaviour

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib

## Dataset

Olist Brazilian E-Commerce Dataset

The analysis uses:

* olist_customers_dataset.csv
* olist_orders_dataset.csv
* olist_order_items_dataset.csv
* olist_order_payments_dataset.csv

## Repeat Customer Definition

A customer with only one completed order is classified as a One-Time customer.

A customer with two or more completed orders is classified as a Repeat customer.

## Customer Segments

* One-Time: 90557 order
* Repeat: 5689 orders
* Highly Loyal: 232 orders

## Analysis Performed

1. Loaded and inspected the Olist datasets
2. Filtered completed delivered orders
3. Identified customers using customer_unique_id
4. Calculated the number of orders per customer
5. Classified customers into purchase-frequency segments
6. Calculated repeat purchase rate
7. Calculated first-time and repeat customer AOV
8. Created a customer-level repeat purchase table
9. Created a customer segment summary
10. Analyzed revenue by customer segment
11. Created visualizations for customer segments, AOV, and revenue
12. Exported analysis results as CSV files

## Key Results

* Repeat Purchase Rate: 3.00%
* First-Time Customer AOV: 137.96
* Repeat Customer AOV: 123.02

## Output Files

* customer_repeat_purchase_table.csv
* repeat_customer_segment_table.csv
* first_time_vs_repeat_aov.csv
* repeat_purchase_rate.csv
* order_frequency.csv

## Business Insights

* Most customers made only one purchase, indicating a large opportunity for customer retention.
* Repeat customers represented a smaller portion of the customer base.
* First-time and repeat customers showed different average order values.
* Customers with multiple purchases can be targeted with retention and loyalty campaigns.
* Understanding order frequency can help businesses design targeted customer engagement strategies.

## Conclusion

The analysis provides a clear view of customer repeat purchase behaviour and identifies customer segments based on purchase frequency. These findings can support retention strategies, loyalty programs, and targeted marketing campaigns.
