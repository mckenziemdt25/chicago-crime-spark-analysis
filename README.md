# Chicago Crime Big Data Analysis (Apache Spark)

## 📊 Project Overview

This project analyzes 7.3 million Chicago crime records using Apache Spark in a distributed environment.  
The goal was to design and optimize a scalable data processing pipeline under limited hardware resources (4GB RAM).

The project demonstrates:

- Distributed data processing with Apache Spark
- HDFS data storage
- CSV vs Parquet performance comparison
- Partition pruning optimization
- Feature engineering
- Year-over-Year crime trend analysis
- Volatility modeling

---

## 🛠 Tech Stack

- Apache Spark (PySpark)
- Hadoop HDFS
- Linux (Debian)
- Parquet
- Git & GitHub

---

## 📂 Dataset

- 7.3 million Chicago crime records
- Original format: CSV
- Optimized format: Partitioned Parquet (by year)

---

## ⚙️ Data Engineering Workflow

1. Loaded raw CSV data into Spark
2. Cleaned and casted date/time columns
3. Engineered `year` feature
4. Classified violent vs non-violent crimes
5. Partitioned dataset by year
6. Converted to Parquet for optimized querying
7. Compared performance between CSV and Parquet

---

## 🚀 Performance Optimization

The dataset was converted from CSV to Parquet to improve:

- Query speed
- Storage efficiency
- Partition pruning
- Memory usage

Partitioning by `year` enabled selective reads and improved time-series query performance.

---

## 📈 Analysis Performed

- Total crimes per year
- Violent vs non-violent classification
- Year-over-Year percentage change
- Volatility measurement across years

---

## 🧠 Key Takeaways

- Parquet significantly improves performance over CSV in Spark
- Partitioning is critical for large-scale datasets
- Big data workflows can be executed efficiently even on constrained hardware
- Spark enables scalable feature engineering and aggregation

---

## 🔮 Future Improvements

- Add Spark UI performance screenshots
- Implement window functions for deeper trend analysis
- Deploy pipeline in a cloud environment (AWS EMR / Databricks)
- Build dashboard visualization layer

---

## 👨‍💻 Author

Mckenzie Makwela  
Aspiring Data Engineer / Data Analyst  
