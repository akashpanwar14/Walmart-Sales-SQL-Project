# Walmart Sales SQL Project

This repository contains SQL scripts and queries used to analyze Walmart sales data. The project demonstrates database creation, data cleaning, and comprehensive analysis across dimensions such as city, branch, product line, and customer type.

## About

The Walmart Sales SQL Project aims to transform raw sales data into actionable insights. The database is built with a focus on enhancing data with additional columns—such as `time_of_day`, `day_name`, and `month_name`—which allow for a detailed examination of sales trends, customer behavior, and product performance. The project uses simple yet powerful SQL queries to answer key business questions and support decision-making.

## Database Schema

The core table in this project is `sales`, which includes the following columns:

- **invoice_id:** Primary Key (VARCHAR)
- **branch, city, customer_type, gender, product_line:** (VARCHAR)
- **unit_price:** (DECIMAL)
- **quantity:** (INT)
- **tax_pct:** (FLOAT)
- **total:** (DECIMAL)
- **date:** (DATETIME)
- **time:** (TIME)
- **payment:** (VARCHAR)
- **cogs:** (DECIMAL)
- **gross_margin_pct:** (FLOAT)
- **gross_income:** (DECIMAL)
- **rating:** (FLOAT)
- **Additional columns:** `time_of_day`, `day_name`, and `month_name` added during data cleaning

## Key Insights

- **Unique Cities:** Sales records involve three cities: Yangon, Naypyitaw, and Mandalay.  
- **Monthly Trends:** January shows the highest revenue and COGS, while March and February follow.  
- **Product Performance:** Electronic accessories top the quantity sold, but Food and Beverages lead in overall revenue.  
- **Customer Behavior:** Member customers contribute slightly more revenue than Normal customers, and ratings peak in the afternoon.  
- **Tax Insights:** Naypyitaw has the highest average tax rate among cities.

## Getting Started

1. **Clone the Repository:**

   ```bash
   git clone <https://github.com/akashpanwar14/Walmart-Sales-SQL-Project>
   ```

2. **Set Up the Database:**

   - Import the SQL scripts into your MySQL environment.
   - Ensure that safe mode is turned off for updates if you need to modify data.

3. **Run the Queries:**

   Use your favorite SQL client to execute the provided scripts. These queries will:
   
   - Create and manage the database.
   - Clean and transform data by adding useful columns.
   - Generate insights regarding sales trends, customer behavior, product performance, and tax metrics.

## Usage

This project serves as a learning tool for SQL data manipulation and analysis. It is ideal for:
- Analyzing business data to extract valuable insights.
- Demonstrating practical SQL techniques for data cleaning and transformation.
- Guiding business decisions based on trends in revenue, product performance, and customer preferences.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests. For major changes, please open an issue to discuss your ideas first.

