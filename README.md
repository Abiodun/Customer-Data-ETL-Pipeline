# Customer-Data-ETL-Pipeline

##Introduction
The goal of this project is to perform some ETL operations on customer data using various tools and technologies, GitHub, Python, Mage Data Pipeline Tool, BigQuery or MySQL, and Looker Studio.

## 🚀 Task
- Injest or load the data from two different sources Github
- Join the two csv on email
- Remove dollar sign from currency - so we can perform calculation/aggregartions on the column
- Replace ‘Ltd.’ with ‘Limited’ in company column
- Convert date from current format to DD/MM/YYYY
- Rename column header ‘currency’ into ‘new_pricing’
- Classify price by group eg <45 = Poor, 46-65 = Fair, 66-90=Very Good, >90 = Excellent
- Sink data into MySQ


## 🚀 Screenshots
![Loading the raw data](https://raw.githubusercontent.com/Abiodun/Customer-Data-ETL-Pipeline/main/screenshots/dataloader_1.png)

![Loading the raw data](https://raw.githubusercontent.com/Abiodun/Customer-Data-ETL-Pipeline/main/screenshots/data_transformer_1.png)

![result data](https://raw.githubusercontent.com/Abiodun/Customer-Data-ETL-Pipeline/main/screenshots/pipeline_tree_1.png)

![Loading the raw data](https://raw.githubusercontent.com/Abiodun/Customer-Data-ETL-Pipeline/main/screenshots/sinked_data_mysql.png)

## 🚀 About Me?
I'm just a normal guy doing stuff with data and providing solutions
