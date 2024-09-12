## Overview

Amazon and Vine collaborated to create a paid subscription program for readers. To focus and refine marketing efforts for the program, we analyze all 114,00 book reviews to ascertain whether paid member reviews are positively biased compared to non-member reviews. To this end, we utilize Apache Spark and PySpark to initiate the extraction, transformation, and loading (ETL) process with cloud computing. Then we transfer the data into a PostgreSQL database with pgAdmin by creating and connecting to an Amazon Web Service's Relational Database Service (AWS RDS) instance. 

---

## Results
<!-- Using bulleted lists and images of DataFrames as support, address the following questions:
How many Vine reviews and non-Vine reviews were there?
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars? -->

* There were 5,012 Vine reviews;
* There were 109,297 non-Vine reviews.

![paid_reviews](https://user-images.githubusercontent.com/96349090/165081654-f9f54151-0e5b-4a5b-bc5b-f1bde0b7b675.png)

![unpaid_reviews](https://user-images.githubusercontent.com/96349090/165081685-2840b2fc-6d77-4d1d-b412-9d9de13c77cf.png)


* 2,031 Vine reviews were five stars;
* 49,967 non-Vine reviews were five stars.

![paid_5_stars](https://user-images.githubusercontent.com/96349090/165081705-3c9ceae6-cb15-4f80-ae2e-42096ea9a044.png)

![unpaid_5_stars](https://user-images.githubusercontent.com/96349090/165081723-dd5f9483-43ac-401b-895d-24b0956c5cf2.png)


* Approximately 40.52% of Vine reviews were five stars;
* Approximately 45.72% of non-Vine reviews were five stars.

![percentages](https://user-images.githubusercontent.com/96349090/165081753-6a9ee47c-2915-4322-b3ff-aafb706e0698.png)

### At-a-Glance
||Vine Reviews|Non-Vine Reviews|
|:---|:---:|:---:|
|Total Reviews|5,012|109,297|
|Number of Five Stars|2,031|49,967|
|Percentage of Five Stars|40.52%|45.72%|

---

## Summary
<!-- In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement. -->

Based on the calculations above, positivity bias from members of the Vine program is unlikely. The percentage of five-star Vine reviews was comparable to that of five-star non-Vine reviews. Additional analysis could determine the distribution of star ratings by calculating the percentages of Vine and non-Vine reviews at each star rating.

---

## Resources

Data Source:

    https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Books_v1_00.tsv.gz

Software:

    AWS RDS
    Google Colaboratory Notebook
    Apache Spark
    PySpark
    Python
    PostgreSQL
    pgAdmin
    Hadoop
    MapReduce
    mrjob
    
---

### Contact

Email: kate.wang00001@gmail.com

LinkedIn: [katewang01](http://linkedin.com/in/katewang01)
