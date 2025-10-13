# 1. What is Data Engineering?
-Data Engineering is the practice of designing, building, and maintaining systems and architectures that collect, store, and process data efficiently. Data engineers create pipelines to move data from source systems to analytical platforms like data warehouses or data lakes.
# 2. What are ETL and ELT?
  -ETL (Extract, Transform, Load): Data is extracted from source, transformed in an intermediate system, and loaded into the warehouse.
  -ELT (Extract, Load, Transform): Data is first loaded into the warehouse or lake, and transformation happens there using tools like SQL or Spark.
  ## Example:
  ETL – traditional pipelines with Informatica, SSIS.
  ELT – modern cloud pipelines using Snowflake or BigQuery.
# 3.Explain Partitioning and Bucketing in Hive.
  -**Partitioning**: Divides table data based on column values (e.g., date). Makes queries faster.
  -**Bucketing**: Divides data into fixed-size “buckets” using a hash function on a column (e.g., user_id). Helps with joins and sampling.
