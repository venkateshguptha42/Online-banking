# Online-Banking
In this project we are working on a loan dataset, customer credit card dataset and a bank transaction dataset by using Apache Spark, which is a data processing framework that can quickly perform processing tasks on very large data sets, and can also distribute data processing tasks across multiple computers, either on its own or in tandem with other distributed computing tools. Using these datasets and Spark SQL we have created various use cases pertaining to real life scenarios in banking.

# Technologies Used
1.Spark
2.PySpark
3.SparkSQL
4.HDFS
5.Hive
6.Python
7.DataBricks

# USE CASES FOR LOAN DATASET
>>>The number of loans on each category.
>>>The number of loans taken on each occupation.
>>>Know the number of members who taken more than 1lack loan.
>>>Number of members whose overdue is more than 5.
>>>The number of members whose debt record is less than 20k.
>>>Marital status of loans takers.
>>>Number of loans in each category.
>>>Partitioning dataframe on column ‘Loan Category’.
>>>Number of people with 2 or more returned cheques and income less than 50000.

# USE CASES FOR CUSTOMER CREDIT DATASET

>>>The number of members who are eligible for credit card.
>>>The number of members who are eligible and active on bank.
>>>The number of targeted persons for credit card.
>>>The targeted persons count whose tenure is less than 5.
>>>The targeted persons count who exited.
>>>The number of targeted persons whose number of product is equal to 1.
>>>Credit card users in Spain.
>>>Number of customers who’s Estimated Salary less than 1 lakh and number of products more than 1.

# USE CASES FOR CUSTOMER TRANSACTION DATASET

>>>Count of transaction on every account.
>>>Maximum withdrawal amount of an account.
>>>Minimum withdrawal amount of an account.
>>>Maximum deposit amount of an account.
>>>Minimum deposit amount of an account.
>>>Sum of balance in every bank account.
>>>Count of transaction methods what customers used for transaction.
>>>Number of transaction on each date.
>>>List of customers with withdrawal amount more than 1 lakh.

# Getting Started
1.create the data frame using the SparkSession and load the data intoit.

df = spark.read.csv("C:/Users/sidse/Downloads/big data course/ASSIGNMENTS/projects/Banking P2/loan.csv", inferSchema = True, header = True)
df.printSchema()

2.perform some use cases
>>>number of people who have taken more than 1 lack loan.
>>>number of people with 2 or more returned cheques and are single.
>>>number of people with income greater than 60000 rupees.

# Roles and Responsibilities:
1.collected some use cases for loan dataset, transaction dataset.
2.Integrated spark with jupyter using the module pyspark.
3.Worked on the aggregate functions and verity of use cases.For the purpose the partitioning the data we have also worked on ubuntu.Collected the data set from Kaggle and processed using the pyspark.
4.Coordinated ina tem of five members and working with github.
5.Implemented various use cases on loan data set and transaction data to fetch required information.
6.For the purpose of finding the more use cases i have worked on databricks.
7.Worked on the management of time and quality to achieve the project goal in time with improved quality.
8.Deployed the project on Github with repository name as an Online-Banking
9.Deployed the setup of spark environment to run PySpark.
10.Utilized the VI editor to develop code on a Virtual Machine.


# CONTRIBUTERS:
1.Akhil
2.Rajib
3.Anand
4.Abhilash
5.Venkatesh
6.Sidhanth
