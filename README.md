# **Home Sales Big Data Analysis with SparkSQL/PySpark**

## **Overview**
This project analyzes home sales data using **SparkSQL/PySpark** to gain insights into home prices. The analysis explores price trends based on various home features (e.g., number of bedrooms, bathrooms, and views) and examines how these trends change over time.

By leveraging **SQL queries, caching, and partitioned Parquet data**, this project demonstrates efficient big data processing techniques to optimize performance and data management.

---

## **Project Summary**

### 🔹 **Key Tasks:**
- Load home sales data into a **Spark DataFrame**.
- Run **SQL queries** to extract insights (e.g., average home price per year for different property types).
- Utilize **caching** to optimize query performance and compare execution times with and without caching.
- **Partition the dataset** by `date_built` and save it as **Parquet files** for better data management.
- Re-run queries on **Parquet data** and compare performance with cached data.
- Implement and verify **caching and uncaching** operations correctly.

---

## **Technologies Used**
- **PySpark / SparkSQL**
- **Parquet File Format**
- **SQL for Data Analysis**
- **Caching & Partitioning Strategies**

---

## **Results & Learnings**
By completing this project, we will:
✅ Understand how large datasets can be processed and analyzed using **PySpark**.
✅ Learn how **performance improvements** can be achieved through **caching** and **partitioning**.
✅ Gain insights into **home price trends** and how various property features impact pricing over time.
