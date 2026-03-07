# online_retail_dataset

[![Python](https://img.shields.io/badge/Python-3.12-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A comprehensive analysis of a transactional dataset from a UK-based online retail store. This project examines sales trends, customer behavior, and product associations to derive actionable business insights.

## Research Questions

* **What is the sales trend over time? Are there seasons/months with higher sales?**
* **Who are the top 10% of customers in terms of purchase value? What percentage of total sales do they generate?**
* **Market basket analysis: which products are most often purchased together?**
* **What is the average order value? How does it change over time? Are there regions/countries with higher AOV?**
* **Customer retention: how many customers return after their first purchase? What is the difference between one-time and returning customers in terms of value?**

## Key Insights

* **Data Quality**: 22.77% of transactions lack a customer ID, representing a critical area for improving data collection processes.
* **Revenue Concentration**: Only 10% of customers, mainly from the United Kingdom, generate 55% of total sales.
* **Seasonality**: Activity peaks sharply between September and January, directly correlating with the holiday shopping season.
* **Retention & Value**: The retention rate sits at 75.4%, with returning customers generating nearly 40% higher average order value compared to one-time customers.
* **Process Transparency**: Identified anomalies in prices and quantities, including negative values, reflect legitimate business processes such as returns, fees, and write-offs rather than data errors.
* **Cross-Selling Potential**: Detected correlations in shopping carts provide ready-made opportunities for sales optimization through targeted cross-selling strategies.

## Technical Stack

* **Python 3.12+**
* **pandas** – Data manipulation and cleaning
* **numpy** – Numerical computing
* **matplotlib** – Data visualization
* **seaborn** – Advanced statistical graphics
* **openpyxl** – Excel file integration
* **jupyter** – Analytical environment

## Project Structure

```bash
online_retail/
├── data/
│   └── online_retail_II.xlsx
├── online_retail.ipynb
├── requirements.txt
├── README.md
└── LICENSE
```

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/tomszy91/online_retail.git
    cd online_retail
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Launch the analysis:

    ```bash
    jupyter notebook online_retail.ipynb
    ```

## Executive Summary

22.8% of transactions lack a customer ID, indicating data quality issues. The top 10% of customers (mostly UK) account for 55% of sales. Peak activity occurs from September to January, with high retention (75.4%) and returning customers spending 40% more per order. Anomalies in price and quantity reflect business processes, and detected product-pair correlations provide actionable cross-selling opportunities.
