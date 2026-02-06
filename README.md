# Online-Retail-Sales

## 💡 Executive Summary

This project executes a full-lifecycle analysis of a transnational dataset containing transactions occurring between **01/12/2010 and 09/12/2011** for a UK-based and registered non-store online retail.

The primary objective was to optimize marketing strategies and inventory management. This was achieved by cleaning raw transaction data, identifying seasonal trends, and performing **RFM (Recency, Frequency, Monetary) segmentation** to classify the customer base.

---

## 🔑 Key Outcomes

The analysis yielded the following critical insights and technical achievements:

* **Robust Data Pipeline:** Established a scalable data pipeline in **PostgreSQL** capable of handling over **500,000 transaction records**.
* **Critical Revenue Drivers:** Identified **Q4 (Quarter 4)** as the peak sales period, with **November sales doubling the annual average**, highlighting the importance of holiday season inventory planning.
* **Strategic Customer Segmentation:** Successfully segmented the customer base into four distinct categories—**Champions, Loyal, At Risk, and Standard**—to enable highly targeted retention campaigns and marketing strategies.

---

## 🛠️ Methodology & Tools

This project was executed using standard data analysis techniques and SQL for data processing:

* **Data Cleaning & Preprocessing:** Handling null values, removing duplicate transactions, and formatting date fields for analysis.
* **Exploratory Data Analysis (EDA):** Analyzing sales trends over time to identify seasonal patterns and peak periods.
* **RFM Analysis:** A marketing technique used to quantitatively rank and group customers based on the recency, frequency, and monetary total of their recent transactions.
* **Tool:** **PostgreSQL (pgAdmin)** was used for all data storage, querying, and manipulation.

---

## 📂 Project Structure

* `analysis_queries.sql`: The main SQL script containing the queries for data cleaning, trend analysis, and RFM segmentation. *(Note: Replace this with the actual name of your uploaded SQL file)*
* `sample_retail_data.csv`: A sample dataset used to demonstrate the SQL queries. *(Optional: Include this if you upload sample data)*
* `README.md`: This document providing an overview of the project.

---

## 🚀 How to Run the Code

To run the SQL queries in this project, follow these steps:

1.  **Prerequisites:** Ensure you have **PostgreSQL** and an interface like **pgAdmin** installed on your machine.
2.  **Clone the repository:**
    ```bash
    git clone [Your Repository URL]
    ```
3.  **Set up the Database:**
    * Create a new database in PostgreSQL (e.g., `retail_analysis_db`).
4.  **Import Data:**
    * Import the provided `sample_retail_data.csv` file into a table within your new database. Ensure table column names match those used in the SQL script.
5.  **Run the Queries:**
    * Open the `analysis_queries.sql` file in pgAdmin.
    * Execute the queries against your database to view the results of the analysis and segmentation.

---

## 👤 Author

* **Muthmainnah** - https://www.notion.so/Muthmainnah-s-Portfolio-297641a84f1880869b42e875a69c3a6e?source=copy_link
