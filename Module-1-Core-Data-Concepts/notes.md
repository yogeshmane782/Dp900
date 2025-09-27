# what is data?
- Data is collection of raw facts,numbers,symbols or information that does't have much meaning until proessed.
- **Tyeps of Data**
  # 1.Structure data-
    -Structure data refer information that is organised in row and columns inside database.
    -ex:-sql table
    -row=records
    -colums=attributes
# 2. Semi-Strucured Data-
  -Data that does not follow table structure but has some properties to make it easier to understand.
  ## feature
    -no fixed schema
    -stored in nosql database (ex:-Mongo DB,Cosmos DB)
    -use tag,key-value pairs or json/xml (ex:-sensor data,email,social media)
# 3.Unstructured Data-
  - Data that has no predefined structure and cannot store in table easily.
  - no row/columns
  - Requires data lakes,big data system
-EX:-images,video,audio,recording,pdf file,scan document,cctv footage

# Data Workloads
# 1.Transactional worklads (OLTP)-
  -OLTP is a type of database system designed to handle day-to-day transaction in real time. It focuses on fast insert,update,delete operations (not big report).
  -Ex:-Banking system (transfer,withdraw,deposit)
      -E-commerce (order placement,cart updates)
      -Ticket booking (airlines,trains)
# 2. Analytical workloads (OLAP):
  -OLAP is a type of database system designed for data analysis and reporting not daily transaction. It focuses on complex queries over large volumes of istorical data.
  Examples:
    -Sales trend analysis (e.g., “Which product sold most in 2024 Q1?”).
    -Power BI or Tableau dashboards.
    -Customer behavior analysis (e.g., “Which city buys most smartphones?”).
# 3.Batch data processing-
  -Batch processing means collecting data over a period of time and then processing it together in bulk.
  -processing is not real-time it happens after data is collected.
 ## Example:-
     -Bank statement,generating a daily sales report.electricity bills
# 4. Streamig data processing-
    -Streaming means data processed as soon as it is generated in real or near real time.
    ## Example:-
        -stock market price, fraud detection,  smart phone sensor, online gaming
**OLTP = Current, fast, small transactions.
OLAP = Historical, large, deep analysis.
Batch = Big chunks, scheduled.
Streaming = Continuous, real-time.**

# Data Roles:-
  ## 1.Data Administrator (DBA)-
  **-Definition:**
-A DBA is responsible for managing and maintaining databases.
-They ensure databases are secure, available, and performing well.

**Key Responsibilities:**
-Install, configure, and upgrade database servers.
-Manage user access, permissions, and security.
-Backup & recovery of databases.
-Monitor performance and tune queries.
-Ensure high availability and disaster recovery.

**Example in real world:**
A bank’s DBA ensures that the transaction database is always available and secure.

  ## 2. Data Engineer-
  **Definition:**
-A Data Engineer designs and builds the systems that collect, store, and process data.
-They prepare the data so that analysts and scientists can use it.

**Key Responsibilities:**
-Build ETL pipelines (Extract, Transform, Load).
-Work with big data technologies (Hadoop, Spark, Azure Data Factory).
-Ensure data quality, reliability, and scalability.
-Integrate multiple data sources (databases, APIs, logs).
-Optimize data storage (data lakes, data warehouses).

**Example in real world:**
  -At Amazon, a data engineer builds pipelines that collect sales data from all regions and load it into a central warehouse.

## 3. Data Analyst-
**Definition:**
-A Data Analyst helps organizations make business decisions by analyzing data and creating reports/dashboards.

**Key Responsibilities:**
-Query data using SQL.
-Build reports and dashboards (Power BI, Tableau, Excel).
-Identify patterns, trends, and insights in data.
-Communicate findings to stakeholders in simple terms.
-Work closely with business teams to answer questions.

**Example in real world:**
-A retail company’s data analyst creates a sales dashboard showing which products are selling best in each city



| Workload             | Azure Service                         |
| -------------------- | ------------------------------------- |
| OLTP (Transactional) | Azure SQL DB, PostgreSQL, MySQL       |
| OLAP (Analytical)    | Synapse Analytics, Data Explorer      |
| NoSQL                | Cosmos DB, Table Storage              |
| Batch Processing     | Data Factory                          |
| Streaming Processing | Stream Analytics, Event Hubs, IoT Hub |
| Unstructured Data    | Blob Storage, Data Lake Storage       |


        
  
