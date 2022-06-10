# Amazon_Vine_Analysis
---
## Overview:
---

  We have been tasked with analyzing Amazon reviews written by members of the paid Amazon Vine program, a service that allows manufacturers and publishers  to receive reviews of their products and determine if there are any biases between Vine members and Non-Vine members' reviews. Companies pay a fee to Amazon and provide free products to Vine members, who are then required to publish a review. In order to determine if there is any bias towards favorable reviews from Vine members vs. non-members, we will identify the percentage of 5 star ratings from all ratings for both groups. As part of this exercise, we selected from 50 datasets to extract, transform and load into a dataframe in order to complete our analysis. 

   In order to complete the analysis we must:

  - Use a Google Colaboratory sheets to import PySpark libraries and connect to Postgres in order to create SQL tables and export the results.
  - Use PySpark to extract the dataset, transform the data, and then connect to AWS RDS instance and load the transformed data into pgAdmin.
---
## Results:
---

Our analysis of the Vine Program lead to the following results:

  - There were a total of 7 Vine reviews and 105979 Non-Vine reviews.

![Vine_Program_Y](https://user-images.githubusercontent.com/99817571/173091119-1108fb95-f7dc-48d5-8586-63edbe4f9f97.png)

![Vine_Program_N](https://user-images.githubusercontent.com/99817571/173091166-37d9a5f1-3cb7-4ad7-a219-aeb58d61a11c.png)

  - There were no 5-star reviews from Vine reviews and 67580 5-star reviews from Non-Vine reviews.




Male checkout of bikes is substantially larger than for females with around 110k checkouts at its peak for males and around 35k for females. Both follow the same pattern with bike checkouts peaking at 10 minutes and most rides ending before 30 minutes.

Visualization 3: Trips by Weekday per Hour

<img width="1273" alt="Trips by Weekday per Hour" src="https://user-images.githubusercontent.com/99817571/170549840-452242d2-da9c-4936-ac29-4e9497844e4d.png">

There are peak hours of bike trips in the morning (7-9 a.m.) and in the afternoon (4-7 p.m.) during the week except for Wednesday. This trend is most likely correlated to the daily commute of NYC residents to work.

Visualization 4: Trips by Gender (Weekday per Hour)

<img width="1273" alt="Trips by Gender (Weekday per Hour)" src="https://user-images.githubusercontent.com/99817571/170549879-ec0fe405-405b-45b1-81ee-1c9f1f5038ab.png">

As we can see our previous pattern of higher male bike usage is substantiated.  However, regardless of gender the pattern of peak trip hours during the Weekday remains almost enitrely the same.

Visualization 5: User Trips by Gender by Weekday

<img width="1273" alt="User Trips by Gender by Weekday" src="https://user-images.githubusercontent.com/99817571/170550002-55338406-7442-4542-b8ad-4399159b3285.png">

Among subscribers, ridership is much higher with men whereas with Customers there is no clear distinction. Subscriber bike usage is higher overall during the week than for customers.

---
## Summary:
---


---
## Resources:
---

Data Source: 

Software: 
