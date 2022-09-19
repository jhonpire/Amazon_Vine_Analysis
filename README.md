# Project Overview

The purpose of this project is to perform the process of ETL "Extract Transform and Load" to generate an analysis of the reviews received on a specific set of products on Amazon's website. The tools intended for this project are PySpark, Postgresql and AWS RDS server, making possible handling a large dataset at higher efficientcy than on a local computer.

# Deliverables

#### Deliverable 1: Perform ETL on Amazon Product Reviews

#### Deliverable 2: Determine Bias of Vine Reviews

#### Deliverable 3: A Written Report on the Analysis


**Overview of the analysis:** 

**Results:** Using bulleted lists and images as support, the learners should address the following questions.

1- **How many total reviews were there for a review that was or wasn’t written as part of the Vine program?**

* Total Non-Vine Reviews 37840
* Total Vine Reviews 170

2- **How many 5 star reviews were there for a review that was or wasn’t written as part of the Vine program?**

* 5-Star Non-Vine Reviews 20612
* 5-Star Vine Reviews 65

3- **What is the total percentage of 5 star reviews for or a review that was or wasn’t written as part of the Vine program?**

* 5-Star Non-Vine Reviews: 38.24%
* 5-Star Vine Reviews: 54.47%

**Conclussions:**
 After performing the analysis we can conclude that there is no evidence of a bias generated by the Vine-Program members. At the same time we must note that the data although present with great information, should not be taken blindly as when it is filtered for only 5-Star ratings it becomes as a small sample. 

 We recommend performing a similar analysis, by either changing the filtering to a lower count of stars or a different data set that wouldn't be as vulnerable to such filtering.

 


