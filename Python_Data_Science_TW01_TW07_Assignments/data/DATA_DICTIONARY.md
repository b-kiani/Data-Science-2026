# Assignment data dictionary

## beginner_sales.csv

- `order_id`: order identifier
- `order_date`: source date text; one value is intentionally invalid
- `customer_id`: customer identifier; `C999` is intentionally unmatched
- `region`: source region label; includes spacing, case, and missing-value issues
- `product`: product label; includes case inconsistency
- `units`: quantity; one value is intentionally missing
- `unit_price`: price per unit in GBP
- `satisfaction`: score from 1 to 5; one value is intentionally missing

The file contains one exact duplicate row for cleaning practice.

## customers.csv

One row per customer. Customer `C006` intentionally has no order.

## orders.csv

One row per order. Customer key `C999` intentionally has no matching customer.

## week2_environment_notes.txt

A UTF-8 text file for relative-path and file-reading practice.
