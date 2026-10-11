<div align="center">

💳 UPI Transaction Analytics Dashboard

Turning UPI transaction data into clear, actionable insights.

Explore payment performance, transaction trends, bank and app activity, geographic patterns, and potentially fraudulent transactions in one interactive dashboard.

<br/>





<br/>

📊 Dashboard Preview



</div>

📌 Overview

The UPI Transaction Analytics Dashboard brings key metrics and visual summaries of UPI transaction data into one place. It helps users explore transaction performance and patterns across time, payment applications, banks, states, transaction types, and transaction statuses.

By combining high-level KPIs with detailed charts and filters, the dashboard makes transaction data easier to explore, interpret, and communicate.

Project goal: Turn transaction data into clear, practical insights through an intuitive dashboard.

✨ Dashboard Highlights

Analysis Area

What It Shows

KPI Overview

Total transactions, transaction amount, success rate, and suspected-fraud count

Time Trends

Daily transaction amount over time

UPI App Analysis

Transaction distribution across the payment apps represented in the dataset

Transaction Status

Distribution of successful, failed, pending, and refunded transactions

Geographic Analysis

Transaction amount by state

Bank Analysis

Transaction amount comparisons across banks

Transaction Types

Activity across payment categories represented in the dataset

Hourly Analysis

Transaction amount grouped by hour

Day–Hour Heatmap

Time-based patterns across days of the week and hours

Interactive Filters

Explore the data using the filters available in the dashboard

📊 Key Metrics

Total Transactions — number of transactions in the current selection.

Total Transaction Amount (INR) — total transaction value represented in Indian rupees.

Success Rate — percentage of transactions marked successful.

Suspected Fraud — number of transactions flagged as potentially fraudulent.

Transaction Amount by Hour — transaction value grouped by hour.

Transaction Amount by State, Bank, and Type — comparisons across the available categories.

KPI Definitions

Use consistent definitions when validating or extending the report.

Success Rate

$$
\text{Success Rate} = \frac{\text{Successful Transactions}}{\text{Total Transactions}} \times 100
$$

Suspected Fraud Rate (include only if supported by the source data)

$$
\text{Suspected Fraud Rate} = \frac{\text{Transactions Flagged as Suspected Fraud}}{\text{Total Transactions}} \times 100
$$

Important: Suspected fraud is not the same as confirmed fraud. Validate all measures against the dataset and the report's calculation logic.

🔍 Business Questions

The dashboard can help investigate questions such as:

How does transaction value change over time?

Which payment apps account for the largest share of transactions?

Which banks and states contribute the most transaction value?

What share of transactions are successful, failed, pending, or refunded?

During which hours is transaction activity highest?

How does transaction value vary by transaction type?

How are transactions flagged as potentially fraudulent distributed across available categories?

These are questions the dashboard can help explore. Report conclusions only after validating the underlying data.

🧰 Tools & Technologies

Update this section to reflect the tools actually used in your implementation.

Dashboard / Visualization: Power BI (if applicable)

Data Preparation: Power Query, Excel, or Python (keep only the tools you used)

Data Source: Add the dataset name and source

Version Control: Git and GitHub

🗂️ Repository Structure

UPI_Transaction_Analytics_Dasboard/
├── assets/
│   └── upi-dashboard.png
├── data/
│   └── README.md
├── UPI-Transaction-Dashboard.pbix
└── README.md

File guide

assets/upi-dashboard.png — dashboard screenshot shown above.

data/README.md — dataset source, column descriptions, and data-preparation notes.

UPI-Transaction-Dashboard.pbix — Power BI report file, if applicable.

Adjust the example structure and filenames to match your actual repository. Do not upload confidential, personal, or unlicensed transaction data.

🚀 Getting Started

Clone or download this repository.

Open the dashboard file in the application used to create it.

If prompted, connect the report to the documented dataset location.

Refresh the data if appropriate and permitted.

Use the available filters and charts to explore metrics and trends.

Before publishing, document the dataset source, reporting period, data-cleaning steps, and assumptions used in calculations.

💡 Potential Enhancements

Add a date-range slicer and a Reset Filters button.

Create a dedicated fraud-analysis page with validated fraud-rate and flagged-value measures.

Add dynamic insight cards that respond to filter selections.

Improve chart-label readability and accessibility across screen sizes.

Add a data dictionary and document each KPI calculation.

Include data-quality checks for missing values, duplicates, and inconsistent categories.

Add a findings section based on verified results from the dataset.

⚠️ Data & Interpretation

The dashboard is only as reliable as its source data and metric definitions. Before drawing conclusions, verify:

Dataset source, date range, and currency units.

Whether amounts represent transaction value, settled value, or another measure.

How transaction statuses and suspected-fraud labels are defined.

Whether totals and percentages recalculate correctly when filters are applied.

Whether records are duplicated or categories contain inconsistent values.

Do not present flagged transactions as confirmed fraud unless the source explicitly establishes that status. Do not publish sensitive data or information you are not authorized to share.

👨‍💻 Author

Suayush Kumar Das

Data Analytics · Dashboard Design · Business Insights

<div align="center">

If you find this project useful, consider giving the repository a ⭐

Made with a focus on clear, practical data storytelling.

</div>
