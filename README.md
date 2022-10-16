# Simple-EL-Pipeline-with-Data-Integrity-and-Quality-Checks
DAGs showing an EL pipeline with data integrity and data quality checking.  This demo solves the issue of quality-checking the data in the uploaded file. This DAG is a good starting point for a data integrity and data quality check.

Before running the DAG, set the following in an Airflow or Environment Variable:
- key: aws_configs
- value: { "s3_bucket": [bucket_name], "s3_key_prefix": [key_prefix], "redshift_table": [table_name]}
Fully replacing [bucket_name], [key_prefix], and [table_name].
