# End-to-End-Data-Engineering-Pipeline-How-the-Stock-Market-is-affected-by-Economic-Indicators

<b2>This project demonstrates a complete data engineering pipeline that extracts, processes, and visualizes financial and economic data from multiple sources. It combines Python, AWS, Snowflake and Power BI to build a scalable, automated data solution. Please see the files above for the data extraction and AWS/ Snowflake integration and table transaformation. This project was about showing capabilties in these platforms rather than finding meaningful correlations between the stock market and economic factors.<b2>

**Features**\
**Data Extraction**
- Pull historical stock data (S&P 500, NASDAQ) using yfinance, and key U.S. economic indicators (Inflation, Unemployment, Interest Rate) via fredapi.

**Data Storage**
- Store raw datasets in AWS S3 buckets.

**Cloud Data Warehouse Integration**
- Load data into Snowflake using external stages and COPY INTO SQL commands.

**Data Transformation**
- Join stock and economic datasets to form a unified view of market trends vs. economic conditions.

**Data Visualization**
- Connect Snowflake to Power BI to build insightful visualizations:

**Future Upgrade Ideas:**\
**Automation:**
- Use Python and Boto3 for seamless upload to AWS S3.
- Schedule daily data updates using an Apache Airflow DAG.

**Tech Stack**
- Python (yfinance, pandas, fredapi)
- AWS S3
- Snowflake
- Power BI
