# SQL Advanced Module - Final Assignment

## Description
This repository contains the final assignment for the SQL Advanced module. The task involves analyzing user activity in an e-commerce database, including account creation, email engagement (sent, opened, clicked), verification, and subscription status. Data allows comparison between countries, identification of key markets, and user segmentation.

## SQL Query Requirements
- Use at least one CTE for logical parts of the query.
- Calculate metrics per the following dimensions:
  - `date` (account creation or email sent)
  - `country`
  - `send_interval`
  - `is_verified`
  - `is_unsubscribed`
- Metrics to calculate:
  - `account_cnt` — number of accounts created
  - `sent_msg`, `open_msg`, `visit_msg` — email metrics
  - Additional country-level metrics and ranks:
    - `total_country_account_cnt`, `total_country_sent_cnt`
    - `rank_total_country_account_cnt`, `rank_total_country_sent_cnt`
- Use `UNION` to combine account and email metrics.
- Filter final result to top 10 countries by account count or sent emails.


## Visualization
- Create a Looker Studio dashboard showing:
  - Country-level metrics: `account_cnt`, `total_country_sent_cnt`, `rank_total_country_account_cnt`, `rank_total_country_sent_cnt`
  - Trend over time for `sent_msg`

## Deliverables
- SQL query with comments explaining logic
- Screenshot of Looker Studio visualization
- Document link attached in assignment submission
