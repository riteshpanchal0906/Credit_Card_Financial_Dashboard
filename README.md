# Credit_Card_Financial_Dashboard
Power_BI_Dashboard

A Power BI dashboard for tracking, analyzing, and visualizing credit card spending, payments, and financial trends, backed by SQL for data storage and transformation.

## Features

- Spending breakdown by category, merchant, and time period
- Monthly/yearly trend analysis of expenses and payments
- Credit utilization and outstanding balance tracking
- Payment due date and minimum payment tracking
- Interactive filters and slicers for date range, card type, and category
- KPI cards for total spend, total payments, and outstanding balance

## Tech Stack

- **Power BI** – Dashboard design, DAX measures, interactive visuals
- **SQL** – Data storage, querying, and transformation (HeidiSQL)

## Data Source

- Brief note on where the data came from (Online Dataset from Bank)


## How to Use

1. Clone this repository
2. Open the `.sql` file(s) to set up the database schema and load sample data
3. Open the `.pbix` file in Power BI Desktop
4. Update the data source connection to point to your SQL database
5. Refresh the dashboard

## Project Structure

```
├── data/              # Sample/raw data files
├── sql/               # SQL scripts (schema, queries, transformations)
├── dashboard.pbix      # Power BI dashboard file
├── screenshots/       # Dashboard preview images
└── README.md
```

## Future Improvements

- Add fraud/anomaly detection for unusual transactions
- Automate data refresh via scheduled SQL jobs
- Add predictive spending forecasts

## Author

*(Ritesh Panchal / https://github.com/riteshpanchal0906/Credit_Card_Financial_Dashboard/tree/main)*
