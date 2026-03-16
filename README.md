# PySpark Learning Repository

This repository documents my learning journey with **PySpark**, focusing on big data processing using **Apache Spark and Python**. I am currently learning **RDDs and DataFrame transformations** to understand distributed data processing.

## What I Am Learning

Currently I am exploring the following PySpark concepts:

- RDD (Resilient Distributed Dataset)
- RDD transformations
- RDD actions
- DataFrame transformations
- Basic data aggregation and analysis

## RDD (Resilient Distributed Dataset)

RDD is the **fundamental data structure of Apache Spark**. It is an immutable distributed collection of objects that can be processed in parallel across a cluster.

### Key Characteristics

- Distributed data processing
- Fault tolerance
- Lazy evaluation
- Parallel computation

## Creating an RDD

Example:

```python
rdd = spark.sparkContext.parallelize([1,2,3,4,5])
