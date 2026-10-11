<div align="center">

💳 UPI Transaction Analytics Dashboard

Turning UPI transaction data into clear, actionable insights.

An interactive dashboard to explore payment performance, transaction trends, bank and app activity, geographic patterns, and potentially fraudulent transactions.

<br/>

<!-- Add your dashboard screenshot at assets/upi-dashboard.png -->

<img src="assets/upi-dashboard.png" alt="UPI Transaction Analytics Dashboard preview" width="100%"/>

<br/>





</div>

📌 Overview

The UPI Transaction Analytics Dashboard presents key metrics and visual summaries of UPI transaction data in one place. It is designed to make transaction performance easier to understand and to help users explore patterns across time, payment applications, banks, states, transaction types, and transaction statuses.

The dashboard combines high-level KPIs with detailed charts so users can move from an overall summary to more focused analysis using the available filters.

Project goal: Make transaction data easier to explore, interpret, and communicate through an intuitive analytics dashboard.

✨ Dashboard Highlights

Area

What you can explore

KPI Overview

Total transactions, transaction amount, success rate, and suspected-fraud count

Time Trends

Daily transaction amount over time

UPI App Analysis

Distribution of transactions across payment apps in the dataset

Transaction Status

Successful, failed, pending, and refunded transaction distribution

Geographic Analysis

Transaction amount by state

Bank Analysis

Comparison of transaction amount across banks

Transaction Types

Activity across payment categories represented in the dataset

Hourly Analysis

Transaction amount by hour

Day–Hour Heatmap

Time-based patterns across days of the week and hours

Interactive Filters

Explore the data using the filters available in the dashboard

📊 Key Metrics

The dashboard highlights the following metrics. Values respond to the selected filters where supported by the report.

Total Transactions — number of transactions in the current selection.

Total Transaction Amount (INR) — total transaction value represented in Indian rupees.

Success Rate — percentage of transactions marked successful.

Suspected Fraud — number of transactions flagged as potentially fraudulent.

Transaction Amount by Hour — transaction value grouped by hour.

Transaction Amount by State / Bank / Type — comparisons across the available categories.

KPI definitions

Use consistent definitions when validating or extending the report:

[
\text{Success Rate} =
\frac{\text{Successful Transactions}}{\text{Total Transactions}} \times 100
]

[
\text{Suspected Fraud Rate} =
\frac{\text{Transactions Flagged as Suspected Fraud}}{\text{Total Transactions}} \times 100
]

The suspected-fraud rate is a suggested derived metric; add it only if the source data supports it. Suspected fraud is not the same as confirmed fraud. Confirm all measures against the dataset and the report's calculation logic.

🔍 Business Questions

This dashboard can be used to investigate questions such as:

How does transaction value change over time?

Which payment apps account for the largest share of transactions?

Which banks and states contribute the most transaction value?

What share of transactions are successful, failed, pending, or refunded?

During which hours is transaction activity highest?

How does transaction value vary by transaction type?

How are transactions flagged as potentially fraudulent distributed across available categories?

These are analytical questions the dashboard can help explore; actual findings should be reported only after validating the underlying data.

🧰 Tools & Technologies

Update this section to reflect the tools actually used in your implementation.

Dashboard / Visualization: Power BI (if this is the tool used)

Data preparation: Power Query, Excel, or Python (retain only the tools used)

Data source: Add the dataset name and source

Version control / Portfolio: Git and GitHub

🗂️ Repository Structure

A suggested structure for this repository:

UPI-Transaction-Analytics-Dashboard/
├── assets/
│   └── upi-dashboard.png
├── data/
│   └── README.md
├── UPI-Transaction-Dashboard.pbix
└── README.md

File guide

assets/upi-dashboard.png — dashboard screenshot displayed in this README.

data/README.md — dataset source, column descriptions, and data-preparation notes.

UPI-Transaction-Dashboard.pbix — Power BI report file, if applicable.

Rename or remove example files to match your actual project. Do not upload confidential, personal, or unlicensed transaction data.

🚀 Getting Started

Clone or download this repository.

Open the dashboard file in the application used to create it.

If the report requests a data source, connect it to the documented dataset location.

Refresh the data if appropriate and permitted.

Use the available filters and charts to explore the metrics and trends.

Before publishing, document the dataset source, reporting period, data-cleaning steps, and any assumptions used in calculations.

💡 Potential Enhancements

Add a date-range slicer and a Reset Filters button.

Create a dedicated fraud-analysis page with validated fraud-rate and flagged-value measures.

Add dynamic insight cards that respond to filter selections.

Improve chart-label readability and accessibility at different screen sizes.

Add a data dictionary and document each KPI's calculation.

Include data-quality checks for missing values, duplicates, and inconsistent categories.

Add a short findings section based on verified results from the dataset.

⚠️ Data & Interpretation

This dashboard is only as reliable as its source data and metric definitions. Before drawing conclusions, verify:

The dataset source, date range, and currency units.

Whether amounts represent transaction value, settled value, or another measure.

How transaction status and suspected-fraud labels are defined.

Whether totals and percentages recalculate correctly when filters are applied.

Whether records are duplicated or categories contain inconsistent values.

Do not present flagged transactions as confirmed fraud unless the source explicitly establishes that status. Do not publish sensitive data or information you are not authorized to share.

👨‍💻 Author

<div align="center">

Suayush Kumar Das

Data Analytics • Dashboard Design • Business Insights

</div>

<div align="center">

If you find this project useful, consider giving the repository a ⭐

Made with a focus on clear, practical data storytelling.

</div>
