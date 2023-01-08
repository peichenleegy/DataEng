# Data Engineering(ISTA 322)

## Professor Nicholas DiRienzo
### Email: ​ndirienzo@email.arizona.edu
Office Location: NA for Spring 2020
Online office/lab hours: Thursday 11-12:30
Online Zoom office: ​https://arizona.zoom.us/j/2251199844
SLACK INVITE: ​https://join.slack.com/t/newworkspace-3wj6593/shared_invite/zt-kpzyvfw1-pQmAEAuzQZklCt3XovLQkg Prerequisites: ISTA 321 or equivalent machine learning class; ISTA 130 or equivalent python programming class
Final exam: Monday, May 10th from 9am-12pm or 2pm-5pm (you will pick a time that works)

## Course Description:
### This course will be inviting for a wide variety of students from across disciplines, and they will learn how to use industry standard tools and practices to make large data sets usable for scientists and other decision makers. From data collection and preparation, to the creation of big data stores, databases, or systems to make data flow, this course will focus on the practical work needed to prepare big data for analyses across contexts. Students will be introduced to a variety of technical tools for data management, storage, use, and manipulation.

## Course Objectives: 
### The objective of this course is to train students in the tools and theory behind data engineering so that they can be deployed in the real world. This will revolve around extracting data from static and streaming sources, learning how to transform it in a way to be used for later analytics/machine learning, and data science applications, storing and querying that data in a database. Additional emphasis will be placed on learning some cloud computing methods.

## Expected Learning Outcomes
###
1. Students will be able to extract data from static and streaming data sources
2. Students will develop and apply skills for data cleaning, munging, and transformation so that they are usable for
later analysis.
3. Students will be able to generate and query SQL databases and access said databases from a Python interface
4. Students will understand major cloud and distributed computing technologies and be able to leverage them for data
engineering application.

## Required Readings:
We’ll be using the book Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems​ ​by Martin Kleppmann. This will be coupled with other free online resources

## Grade Distribution:
###
90-100% = A “exemplary, far beyond reqs/expectations” 
80-89% = B “exceeds requirements/expectations”
70-79%= C “meets requirements/expectations”
60-69% = D “falls short of requirements/expectations” 
< 60%= E “repeat of course needed”

## Course Schedule:
###
1. Wednesday, January 13 - ​([What is data engineering](https://docs.google.com/document/d/1_77Iigd0VruNyMY6KYDpMG5HIPmonW9PJf5lWpn4yys/edit?usp=sharing))
a. Lecture 1 - ([what is DE](https://docs.google.com/presentation/d/1LBbLNw3-v_D2-TCzS2Wp3Yt-v-DDOeEapNS8dhP7yxs/edit?usp=sharing))
b. Lecture 2 - ([Where does data come from and what is it](https://docs.google.com/presentation/d/1Fj7w9k0_tFmPmtwNkzXIKtg2tia-U5Rcq1RogdNIzDc/edit?usp=sharing))
c. MAKING ACCOUNTS
2. Wednesday, January 20 - ([What is and how to work with it](https://docs.google.com/document/d/1jOH-zkyXHp5JrNDkuXrLI20aZ3-dD8c14Lxu9XBQh3Q/edit?usp=sharing))
a. Lecture 3 - ([Data types and working with data](https://docs.google.com/presentation/d/1tkSUe2uCkLcLtO5TbE4BCV4bjf6tRkuQk_xWz-xPVEc/edit?usp=sharing))
b. Notebook 1 - ([Working with data](https://colab.research.google.com/drive/1C-7x9z0G4QWvVty1Jse0UroPXrgxx5pD?usp=sharing))
c. Notebook 2 - ([Functions and loops](https://colab.research.google.com/drive/101OQHx7OSXrRN3uNmkeUZ-daVWIeHonM?usp=sharing))
d. HW1 - ([Python programming and data manipulation](https://colab.research.google.com/drive/1tr91eHm-qrhcNZQlzVm2K2KV6xU6FE-x?usp=sharing))
i. Due Tuesday January 26th
3. Wednesday January 27th - Intro to data manipulation in python
a. Notebook 2 - ([Transform flat files](https://colab.research.google.com/drive/1T3OmFavQaVj4prba1vpRbyI2pmLOXfRG?usp=sharing)) - ​([version with fill in parts for lesson](https://drive.google.com/file/d/10u-8sHMcXflS7_MPiUQ_K-61yXcIVF14/view?usp=sharing))
b. ([Lecture 4](https://docs.google.com/presentation/d/1q__a-_-v8U1nrrNBzTkmBdbOSPiAepo-CxVGq8_04Ts/edit?usp=sharing)) - Data transforms​ - ([slides](https://docs.google.com/presentation/d/1q__a-_-v8U1nrrNBzTkmBdbOSPiAepo-CxVGq8_04Ts/edit?usp=sharing)), ([video](https://www.youtube.com/watch?v=nrqQkjth5KA))
4. Wednesday, February 3 - Jsons and semi-structured data
a. Notebook 3 - ([Flattening Spotify JSON data](https://colab.research.google.com/drive/1KCaj9xtrLA1q0bhYic4ThE_Fb0HiIT7z?usp=sharing)) - ([completed version](https://colab.research.google.com/drive/1ckoMywZlch2PE2-RZ6T4DZTHPrNSkegZ?usp=sharing))
b. HW2 - Due Tuesday February, 9
c. ([HW2 - completed](https://colab.research.google.com/drive/165ZNfsPzfCOMS1DNyCbnj_orPMY6fO2X?usp=sharing))
d. ([HW2 - blank](https://colab.research.google.com/drive/1CfZBmZTxbmDESblQaD4QDMGRAd6lmJCq?usp=sharing))
5. Wednesday, February 10 - Intro to SQL
a. ([Setting up movies DB](https://colab.research.google.com/drive/1hnvnlIme6vF29daIES8H7riuFO9CbgWP?usp=sharing))
b. ([Notebook 4 - Intro to SQL](https://colab.research.google.com/drive/10wxJg1LRnClnLdvZNCvBb3fVPBCBdl5k?usp=sharing))
c. ([Lecture - RDBMS](https://docs.google.com/presentation/d/1_R9O2lNObx28BI74m1fnOkXnmvxiM7oIDqAwyj0sDKE/edit?usp=sharing)) - ([Video here](https://youtu.be/nj6clqeIxB8))
6. Wednesday, February 17 - More SQL
a. ([Ticket sales DB setup](https://colab.research.google.com/drive/1ncGwfIPaaKHNGuv9ApN-SvsQClR0_bpM?usp=sharing))
b. HW3 - Due Tuesday February 23
c. ([HW3 - completed](https://colab.research.google.com/drive/1IgArMtNCYIdnUTjOwsRJ5XiuaXqG1_iH?usp=sharing))
d. ([HW3 - blank](https://colab.research.google.com/drive/1vMiDqpWnuRCOd9zy5EHRvsfhJvm3slE-?usp=sharing))
e. ([Lecture - RDBMS](https://docs.google.com/presentation/d/1_R9O2lNObx28BI74m1fnOkXnmvxiM7oIDqAwyj0sDKE/edit?usp=sharing))
7. Wednesday, February 24th SQL loads
a. Expand datatypes part of lesson
b. ([Setting up database on AWS - lecture slides](https://docs.google.com/presentation/d/1VbLuhe8xrooxVSw20NxPUEuwoITWTBNsTarsVPyJ0eo/edit?usp=sharing))
c. ([Notebook - test database connection](https://colab.research.google.com/drive/1vFPJJ_LHZ_Rt9wG5OjcPqldwOawgvoeZ?usp=sharing))
d. HW4 - Due Tuesday, March 2nd
                            2
i. MAKE - Have have them write several loads
e. Review
8. Midterm - Friday, March 5th
a. ([Notebook for SQL](https://colab.research.google.com/drive/1xrFDj0khd8_Y1q9Odh_Pdb81aF0DIl7f?usp=sharing))
9. Monday, March 8th to Friday March 12th - Off week
10. Monday, March 15 - DB normalization & ETL on AWS
a. Expand conceptual side and examples of normalization and also key specification in HW
b. Simple lecture on normalization - ([slides](https://docs.google.com/presentation/d/1wlH2xDerVRq_Vt60J_9SOA3bF8Bq3GfLO9UqRm-hMFU/edit?usp=sharing)), ([video](https://www.youtube.com/watch?v=4hq7nto3ZOk))
c. Notebook - ([Simple ETL (S3 -> colab -> RDB on AWS)](https://colab.research.google.com/drive/1ZeHR62H_haqGhhsUj0kdOWkP2jw4hRKW?usp=sharing))​ - goes with HW4
d. ([Video of going through notebook](https://www.youtube.com/watch?v=UfoC5dpyl4k))
e. ([HW4 - completed](https://colab.research.google.com/drive/17Jjf2raaFz9XLL49wwkuIrPlqBJbamzu?usp=sharing)) - etl - turn into HW5
f. ([HW4 - blank](https://colab.research.google.com/drive/1BKESR7HXX1joocc3CCDkSHgTwKG8VFwX?usp=sharing)) - etl - turn into HW5
g. HW5 - Due Sunday, March 21
11. Monday, March 22 - Tools to deal with lots of data - mapreduce, spark, etc and theory - pyspark
a. ([Outline]())
b. Why distributed computing and mapreduce - ([slides](https://docs.google.com/presentation/d/1qwOFJUZTIgwU4hW3IGnh_EuKw45VVOzOrY_rbAwMPh0/edit?usp=sharing)), ([video](https://www.youtube.com/watch?v=5IliiHpL1y0))
c. Notebook - ([ipynb file to give intro to databricks - OPEN ON databricks](https://drive.google.com/file/d/1cxFtfX1Zyo3Tu8UyhNvbU1R6Hh2eVUMD/view?usp=sharing))
d. ([Link to databricks community edition](https://community.cloud.databricks.com/))
e. Need to expand detail on mapreduce process and find general reading
i. How it might work on other data
12. Monday, March 29 - More databricks
a. ([Notebook - More transform operations on databricks](https://drive.google.com/file/d/1U6bi2OhtdESJ0IBUS2sEkOh7cOFx05Cx/view?usp=sharing))
i. Note - ‘light’ lesson as students were really struggling at this point last semester due to covid/elections
b. ([HW 5 - blank to be done on databricks](https://drive.google.com/file/d/1j07oWSm1qNEVMsG1SQZxCGeMU2Qh9ovc/view?usp=sharing)) - update to HW6!
c. ([HW 5 - completed](https://drive.google.com/file/d/17II_S3FSBGm96_UdfJD8v27MWVQSxOFA/view?usp=sharing)) -
i. HW6 - Due Sunday, April 4 - Move into previous week and then make new shorter one on semi-structured? Current HW is sorta light in that it’s just some transforms.
ii. OR - Connecting to S3 via databricks and brief lesson the week before?
d. semi-structured data?
13. Monday, April, 5 - Scheduling and Airflow
a. HW7 - Due Sunday, April 11
i. Make on scheduling via airflow
14. Monday, April 12 - ​Flex​/​TBD
15. Monday, April 19 - Final project W/1
a. Final project goals - ([slides](https://docs.google.com/presentation/d/1UNrabTJVj7TND2HxDV1OiBr1UO1CU1IFxEisT8QRTWk/edit?usp=sharing)), ([video](https://www.youtube.com/watch?v=-Ep3wEK61OQ))
b. ([Notebook - Final project template](https://colab.research.google.com/drive/1EDKiVopEGKLE-HJaaf-OzvjD9u8_0oi5?usp=sharing))
c. ([Guide to getting data on sheets for import](https://docs.google.com/presentation/d/1GenM4fGzVs6g4zCnbUb_fZfRBFnxZYx4B2kHqgdkrCQ/edit))
d. Points for validating data and question - Due Thursday, April 22
i. MAKE
16. Monday, April 26 - Final project W/2
a. Final project due Sunday, May 2
17. Monday, May 3 - Wednesday, May 6 - Final review
18. Final exam - Monday, May 10
a. ([Study guide](https://docs.google.com/document/d/1XcYp-8Fzgci4MmkWZuNtpuzR0-lzPsPZYdAxmDDALlQ/edit?usp=sharing))
b. Final exam was short due to breaks I gave them. Could be beefed up.

