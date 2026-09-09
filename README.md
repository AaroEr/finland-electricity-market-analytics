# finland-electricity-market-analytics
End-to-end electricity market analytics pipeline for Finland. Ingests consumption, production, and day-ahead price data via Fingrid and ENTSO-E APIs, transforms it through a medallion architecture (Bronze/Silver/Gold) on Databricks using PySpark, and visualizes it in Power BI with a star schema and DAX measures.
