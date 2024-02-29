ASSIGNMENT SUMMARY:

ETL and Data Pipelines using Apache AirFlow:

This assignment comprises two parts: ETL and Data Pipelines using Apache AirFlow.

For the ETL section, there are four exercises to complete. Before starting, ensure the lab environment is set up by initiating the MySQL server, MongoDB server, and downloading the database files from the provided link. Import the JSON data into a MongoDB collection, and the SQL data into the MySQL server. Additionally, confirm access to the IBM DB2 server instance.

In the first exercise, extract data from MySQL sales tables and MongoDB into CSV format. Then, transform OLTP data to match the data warehouse schema, including editing/dropping columns as necessary, and save the transformed data into a new CSV file. In the third exercise, perform data transformation tasks and load the transformed data into the data warehouse, ensuring proper loading and verification. Finally, automate daily incremental data extraction and load yesterday's data into the data warehouse using a Python script template.

In the Data Pipelines using Apache AirFlow section, prepare the lab environment by starting Apache Airflow and downloading the dataset to the specified destination from the provided source link. In the first exercise, create a DAG (Directed Acyclic Graph) that runs daily. Tasks include extracting IP address and date fields from the webserver log file and saving them into a CSV file, transforming the date field into YYYYMMMDD format, and archiving the transformed CSV file into a TAR file. Define the task pipeline accordingly.

In the second exercise, operationalize the DAG by saving it into a PY file, submitting, unpausing, and monitoring DAG runs from the Airflow console. Capture screenshots of the commands used and their outputs after completing each task, providing appropriate names for each screenshot.
