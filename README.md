# Amazon_Vine_Analysis

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. In this project, we were tasked with analyzing the Amazon Vine program and determining if there was a bias toward favorable reviews from Vine members.

In this project, I had access to approximately 50 datasets. Each one contained reviews of a specific product, from clothing apparel to wireless products. I chose to focus on US reviews for sports items. PySpark was used to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used PySpark to determine if there was any bias toward favorable reviews from Vine members in the dataset.

## Results
### Sports Items DataFrame
<img width="1334" alt="Sports_DF" src="https://user-images.githubusercontent.com/60076980/163738250-6f50a9d9-5dc3-4ebb-b292-7e1bf2d99f77.png">

1. How many Vine reviews and non-Vine reviews were there?
- As seen in the image below there were 334 Vine reviews and 61,614 non-Vine reviews.

<img width="450" alt="Total_Reviews_Image" src="https://user-images.githubusercontent.com/60076980/163737718-28e7e41a-64ad-489c-9961-b8a190202060.png">

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- As seen in the image below there were 139 Vine reviews with 5 stars and 32,665 non-Vine reviews with 5 stars.
<img width="646" alt="5StarReviews_Image" src="https://user-images.githubusercontent.com/60076980/163737888-6fbd7b5c-d7cb-4262-b3b0-1b26dbc0f256.png">

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- As seen in the image below the percentage of Vine reviews that were 5 stars was 42% and percentage of non-Vine reviews that were 5 stars was 53%.

<img width="620" alt="Percentage_5_Star_Reviews" src="https://user-images.githubusercontent.com/60076980/163737980-4e7e6b96-92f3-4da7-81bd-a8543df6f6c2.png">

## Summary
We can see from the analysis above that the percentage of 5 star reviews from non-Vine users was 53%, which is higher than the percentage of 5 star reviews from Vine users at 42%. This shows that there is no positivity bias for reviews in the Vine program. Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews to see if this also supports the statement above.
