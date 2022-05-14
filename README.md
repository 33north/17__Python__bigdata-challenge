# 17__Python__bigdata-challenge
17__Python__bigdata-challenge

Learning about big data, I looked at Amazon product review data.  I grabbed 2 datasets for electronics and books and did an extract, transform, and load (ETL) of the data.

First the datasets were individually loaded into separate Jupyter Notebooks via PySpark and into a dataframe.
Second transforming data via checking datatypes for each column in the dataset and making it so that the dataset schemas matched the schemas for the SQL database running on Amazon RDS.  Four tables were created in the database and they are: customers, products, review_id_table, and vine_table.  Once the data was transformed in PySpark using Google CoLaboratory, it was loaded into the database.  This portion took a lot of time as the records in the datasets were in the millions.

