## Overview

The purpose of this project is to analyze a dataset of book reviews from Amazon. To this end, we utilize PySpark to extract, transform, and load the data into pgAdmin while connecting to Amazon Web Service's Relational Database Service (RDS) instance. We will also use PySpark to ascertain whether the paid Amazon Vine program members leave more positive reviews based on the dataset.

---

## Resources

Data Source:

    https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Books_v1_00.tsv.gz

Software:

    Google Colaboratory notebook
    Python MapReduce library mrjob
    PySpark

---

## Results
<!-- Using bulleted lists and images of DataFrames as support, address the following questions:
How many Vine reviews and non-Vine reviews were there?
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars? -->

* There were 5,012 Vine reviews;
* There were 109,297 non-Vine reviews.

* 2,031 Vine reviews were five star;
* 49,967 non-Vine reviews were five stars.

* Approximately 40.52% of Vine reviews were five stars;
* Approximately 45.72% of non-Vine reviews were five stars.

---

## Summary
<!-- In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement. -->

Based on the calculations above, positivity bias from members of the Vine program is unlikely. The percentage of Vine reviews were five stars compared to the percentage of non-Vine reviews. An additional analysis could determine the distribution of star ratings by calculating the percentages of Vine reviews and non-Vine reviews at each star rating.