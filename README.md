# Amazon_Vine_Analysis

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. In this project, we will analyze Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.

In this project, I have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. I will be focusing on US reviews for sports items. PySpark will be used to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I'll use PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset.

Results: Using bulleted lists and images of DataFrames as support, address the following questions:

- How many Vine reviews and non-Vine reviews were there?
As seen in the image below there were 334 Vine reviews and 61,614 non-Vine reviews.

<img width="450" alt="Total_Reviews_Image" src="https://user-images.githubusercontent.com/60076980/163737718-28e7e41a-64ad-489c-9961-b8a190202060.png">



How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
