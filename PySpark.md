# Spark & PySpark

A deep dive into the questions that I ask myself during development, the sources that I use(d) to answer those questions, and where I put even better sources that my [awesome-list-of-lists](https://github.com/jamesonl/awesome-list-of-lists) repo may not have a perfect place for.

## Optimization of Joins

Combining large tables is a strength of Spark's. However, not knowing how to organize tables has led to some very challenging encounters. Mostly ending with me scratching my head trying to figure out why something doesn't run...

In no particular order (yet), here are all the questions that I encounter when developing along with all the solutions that I find (or lack thereof):

## Questions & Answers

**_Recommended Reading BEFORE asking questions...:_**
 - [Core Concepts Visualized](https://blog.usejournal.com/spark-study-notes-core-concepts-visualized-5256c44e4090)

**1. What is the best way to efficiently design joins?**

 - If at all possible **always try to avoid "full" joins**.
 - [Optimizing Spark SQL Joins](https://medium.com/datakaresolutions/optimize-spark-sql-joins-c81b4e3ed7da)
    - This article did a great job of identifying WHAT Spark naturally does and how a user should interact with the system
 - [DeepSense.ai Post on how to use **Distribute** and **Cluster**](https://deepsense.ai/optimize-spark-with-distribute-by-and-cluster-by/)
    - _"Your DataFrame is skewed if most of its rows are located on a small number of partitions, while the majority of the partitions remain empty. You really should avoid such a situation. Why? This makes your application virtually not parallel – most of the time you will be waiting for a single task to finish. Even worse, in some cases you can run out of memory on some executors or cause an excessive spill of data to a disk._"

**2. What is the correct order of operations when designing ETL flows in PySpark?**

 - TBD
 
**3. How to make data from nothing?**
