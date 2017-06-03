# PM2.5Correlation
20170518 Assignment for Advanced Data Mining and Big Data Analysis Class
###### tags: `pm2.5` `spark` `correlation`

Target
===
- Use SPARK
- Calculate the PM2.5 correlation between the Dali and other stations.
- Let it run as fast as possible.

Program
===
- Python 2.7
- Pyspark

Environment
===
- Databricks
- Data Science Experience

Result
===
- Version 1：About 5 minute
- Version 2：About 16 second

Conclusion
===
The more RDD we have, the more job we create.

Hence, when RDDs' collect, it wiil waste a lot of time in this case.
