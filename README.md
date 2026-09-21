I have developed an end-to-end Ecommerce Sales Analytics project using Databricks, leveraging PySpark, Python, and SQL. The solution is built on the Medallion Architecture (Bronze–Silver–Gold layers) to ensure scalable, reliable, and structured data processing.

Data Processing Jobs

Dimension Data Processing Job:
Handles ingestion and transformation of dimension tables.
Implements Bronze → Silver → Gold layer progression for clean, enriched, and business-ready data.

Fact Data Processing Job:
Processes transactional fact tables across all three layers.
After transformations, a combined fact-dimension table is created under the Gold layer, optimized for dashboard usage.

Dashboard & KPIs

For visualization and business insights, I created dashboards using the Gold layer data. The dashboard highlights key ecommerce metrics:

Average Order Value (AOV)
Average Discount Percentage
Total Revenue
Total Quantities Sold
Overall Discount Percentage / Amount on Gross Sales

Additionally, I designed graphs and charts for better visualization, enabling stakeholders to quickly interpret trends and performance.
