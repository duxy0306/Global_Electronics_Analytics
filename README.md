# Global Electronics Retail Performance Analysis

## Project Overview

I analyzed 62,884 sales line items to identify which product categories
contributed the most estimated gross profit and understand where the decline
in Computers unit sales was concentrated.

## Workflow

- Used Python and Pandas to audit six source files, check order-line
  uniqueness, clean product prices and costs, and join product data to sales.
- Used SQLite to reproduce the category gross profit ranking and checked
  the result against the Pandas summary.
- Built a Tableau dashboard showing estimated gross profit by category and
  comparing Computers unit sales by channel over matching periods in 2020
  and 2021.

## Key Findings

- Computers contributed $11.28 million in estimated gross profit,
  representing 34.53% of the total across all categories.
- Over the matching periods, Computers unit sales fell from 2,920 to 982.
  Physical stores accounted for 85.24% of the decline in units sold.
- Across 5,580 online orders, delivery took an average of 4.52 days,
  with a median of 4 days.

## Metric Definitions

Estimated sales use listed unit price multiplied by quantity. Estimated
gross profit subtracts listed unit cost multiplied by quantity. The
year-over-year comparison uses the same calendar dates in both years.

## Dashboard

![Global Electronics Retail Performance dashboard]