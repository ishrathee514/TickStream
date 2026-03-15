# TickStream — Real-Time Stock Analytics

## Project Overview

TickStream is a real-time data engineering pipeline designed to ingest, process, and analyze streaming stock market data. The system captures live price movements, processes high-frequency trading data, and generates near real-time analytics to help identify market trends, volatility patterns, and trading signals.
________________________________________
## Dataset Used

Here is the dataset used - https://github.com/darshilparmar/stock-market-kafka-data-engineering-project/blob/main/indexProcessed.csv
________________________________________
## Architecture 

<img src="Architecture.jpg">
________________________________________
## Key Questions

•	How can real-time stock price streams be efficiently ingested and processed at scale?

•	Which stocks exhibit the highest intraday volatility and trading activity?

•	Can streaming analytics detect unusual price spikes or market anomalies?

•	How do sector-level movements influence individual stock performance?

•	What indicators can be generated in real time to support trading insights?
________________________________________
## Approach

•	Streaming Data Ingestion: Use Apache Kafka producers to simulate or ingest live stock market price feeds.

•	Stream Processing: Implement Apache Spark Structured Streaming to process incoming price events and calculate indicators such as price changes, moving averages, and volatility.

•	Data Storage: Store processed streaming outputs in a structured database or data warehouse for analytics and querying.

•	Analytics Layer: Generate aggregated metrics like sector performance, top gainers/losers, and intraday trends.

•	Visualization: Connect processed data to dashboards to display live insights and trading patterns.
________________________________________
## Insights & Impact

•	Identified high-volatility stocks and sectors during trading sessions.

•	Detected abnormal price movements that could indicate trading opportunities or market anomalies.

•	Enabled real-time monitoring of market activity, reducing latency between data ingestion and analysis.

•	Demonstrated a scalable architecture capable of handling high-frequency financial data streams.

•	Provided a foundation for algorithmic trading insights and financial market monitoring.
________________________________________
## Tools and Techniques

•	Languages: Python

•	Streaming & Messaging: Apache Kafka

•	Stream Processing: Apache Spark Structured Streaming

•	Data Storage: PostgreSQL / Delta Lake / Cloud Data Warehouse

•	Data Processing: PySpark, Pandas

•	Visualization: Power BI / Tableau / Streamlit

•	Infrastructure: Docker / Cloud (AWS / Azure)






