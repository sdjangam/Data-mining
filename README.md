# Data-mining


# Data Mining

The area of Data Mining specifically deals with topics like pattern mining, OLAP, data cubes, and outlier detection. Frequent pattern mining deals with mining frequent subsets, subsequences or subgraphs from transactional, sequence or graph datasets respectively. These are very useful for Basket data analysis, cross-marketing, catalog design, sale campaign analysis, Web log (click stream) analysis, and DNA sequence analysis. OLAP enables users to quickly analyze information that has been summarized into multidimensional views and hierarchies. By summarizing predicted queries into multidimensional views prior to run time, OLAP tools provide the benefit of increased performance over traditional database access tools. Outlier analysis has numerous applications in a wide variety of domains such as the financial industry, quality control, fault diagnosis, intrusion detection, web analytics, and medical diagnosis.

In this module, I will cover basic methods for pattern mining like Apriori and FP growth. I will also cover basic concepts in OLAP and in outlier detection.


![image](https://user-images.githubusercontent.com/67232573/113886301-6bc56b00-9775-11eb-8791-eda55cebe4a5.png)





# Frequent Pattern Mining and Association Rules

What is frequent patterns mining? What are the applications?

Understanding frequent patterns, association rules, support and confidence

Apriori Frequent Pattern Mining Method

Improving Apriori Frequent Pattern Mining Method: Less scans

FP Growth Frequent Pattern Mining Method: Building an FP tree

FP Growth Frequent Pattern Mining Method: Creating Conditional Pattern Bases

FP Growth Frequent Pattern Mining Method: Extracting Frequent Patterns

Comparing Apriori with FP Growth

ECLAT: Frequent Pattern Mining with Vertical Data Format

Which association rules are interesting? Lift, Chi Square

Which association rules are interesting? Null invariance

Understanding closed patterns and max patterns

Summary of frequent pattern mining

Python code: Hand-computing support and confidence

Python code: Association Rule Mining

Python code: Apriori

Python code: Evaluating lift for association rules

Python code: Problem on computing association rules with 100% confidence

Python code: Orange way of computing association rules and frequent patterns



![image](https://user-images.githubusercontent.com/67232573/113886566-a4fddb00-9775-11eb-978f-a72c782e384c.png)






# Basic Concepts of Data Warehousing

Basic Concepts in Data Warehousing

OLTP vs OLAP

Data Warehouse Architecture

Data Warehouse Modeling: Data Cubes

Conceptual Modeling of Data Warehouses

Concept Hierarchies and Types of Measures

Data Cube Example

OLAP Operations

Data Warehouse: Design and Usage

Data Cube Computation and Query Processing

Data Cube Computation: Preliminary Concepts

Efficient Data Cube Computation

Multi-Way Array Aggregation

Bottom-Up Computation (BUC)

High-Dimensional OLAP – Part 1

High-Dimensional OLAP – Part 2

Introduction to Sampling Cube

Query Expansion in Sampling Cube

Python Code: Introduction to OLAP and OLAP Server API in Python Cubes 1.1

Python Code: Loading data, specifying model and building aggregates in Python Cubes 1.1


![image](https://user-images.githubusercontent.com/67232573/113886863-daa2c400-9775-11eb-9090-8ff8dfdca122.png)


![image](https://user-images.githubusercontent.com/67232573/113886930-e8584980-9775-11eb-9d78-14327012ceba.png)



# Outlier Detection

What are outliers? What is outlier analysis?

Broad overview of outlier detection Methods

Statistical Methods for Outlier Detection

Proximity based Methods for Outlier Detection: Distance based outliers

Proximity based Methods for Outlier Detection: Density based outliers

Clustering based Methods for Outlier Detection

Classification based Methods for Outlier Detection

Outlier Detection for high dimensional data

Python Code: Remove values > 2 std dev from mean

Python Code: Percentile based outliers vs median absolute deviation based outliers

Python Code: Example of using LOF for outlier detection

Python Code: Example of using Cluster-based Local Outlier Factor (CBLOF) for outlier detection

Python Code: Example of using one class SVM for outlier detection using pyod

Python Code: Example of using PCA for outlier detection

Python Code: One class SVM using scikit learn for outlier detection



![image](https://user-images.githubusercontent.com/67232573/113887178-2190b980-9776-11eb-91fa-6892642cb955.png)




