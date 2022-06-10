# Amazon_Vine_Analysis
---
## Overview:
---

  We have been tasked with analyzing Amazon reviews written by members of the paid Amazon Vine program, a service that allows manufacturers and publishers  to receive reviews of their products and determine if there are any biases between Vine members and Non-Vine members' reviews. Companies pay a fee to Amazon and provide free products to Vine members, who are then required to publish a review. In order to determine if there is any bias towards favorable reviews from Vine members vs. non-members, we will identify the percentage of 5 star ratings from all ratings for both groups. As part of this exercise, we selected from 50 datasets to extract, transform and load into a dataframe in order to complete our analysis. For this analysis the US-Music-Reviews data set was selected.

   In order to complete the analysis we must:

  - Use a Google Colaboratory sheets to import PySpark libraries and connect to Postgres in order to create SQL tables and export the results.
  - Use PySpark to extract the dataset, transform the data, and then connect to AWS RDS instance and load the transformed data into pgAdmin.

---
## Results:
---

Our analysis of the Vine Program yielded the following results:

  - There were a total of 7 Vine reviews and 105,979 Non-Vine reviews.

![Vine_Program_Y](https://user-images.githubusercontent.com/99817571/173091119-1108fb95-f7dc-48d5-8586-63edbe4f9f97.png)

![Vine_Program_N](https://user-images.githubusercontent.com/99817571/173091166-37d9a5f1-3cb7-4ad7-a219-aeb58d61a11c.png)

  - There were no 5-star reviews from Vine reviews and 67580 5-star reviews from Non-Vine reviews.

![5star_reviews_Y](https://user-images.githubusercontent.com/99817571/173093196-f35f1762-9686-4ca5-8918-e80bef992294.png)

![5star_reviews_N](https://user-images.githubusercontent.com/99817571/173093231-d0181b0f-d898-4c72-86ab-9c2bef5a6dbe.png)

  - Since there weren't any 5-star reviews the percentage of 5-star reviews of the total Vine reivews will be 0. The percentage of 5-star reviews to the to
    of Non-Vine reviews was 63.78%.

![Percent_5star_N](https://user-images.githubusercontent.com/99817571/173094565-96633d0e-e89e-4beb-ba72-d79efb451534.png)

---
## Summary:
---

Based on the results of our Vine Review vs Non-Review analysis we can observe that there isn't an indication of positivity bias. There weren't any 5-star reviews from Vine-Reviews whereas there were 105,979 5-star reviews from Non-Vine reviews. However, it is unclear from this analysis alone if there isn't positivy bias across the entirety of Vine Reviews from Amazon. We need to remember that this is a sub-set of data of Amazon US Music Reviews from which we extrapolated Vine Review data. In order to further substantiate our conclusion that Vine Reviews do not lead to a positivty bias and more 5-star reviews we would sample data across several Amazon Review datasets. We would have to ensure that we have random samples of the same size from each data set and from there conduct the same calculations and observe what percentage of 5-star reviews were Vine vs Non-Vine reviews.

---
## Resources:
---

Data Source: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Music_v1_00.tsv.gz 

Software: GoogleColab, pgAdmin 6.7, PySpark
