# Amazon_Vine_Analysis

## Project Overview

In this project, we examined Amazon reviews of Musical Instruments, using Pyspark to perform ETL processes. We extracted the data, transformed the data, and connected it to the RDS Database generated through the AWS server service. Using the review, we aim to determine if there is bias among the reviews from Vine members. 


## Results

* How many Vine reviews and non-Vine reviews were there?
 * When we ran our ETL processes on the Musical Instruments review dataset, we found that there were 60 Vine reviews and 14477 non-Vine reviews.

![Review_Totals](https://user-images.githubusercontent.com/84881187/134606067-6d7cb2b2-08d2-4b69-9cbb-9946e1968d97.PNG)

  
*How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  *  Looking at the review totals, there were 34 5-Star Vine reviews and 8212 5-Star non-Vine reviews.


*What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
* When we analyzed what percentage of the reviews were 5-Stars, we found that about 57% of the reviews were Vine/paid reviews, and about 57% of the reviews were non-Vine/unpaid reviews. There are an equal amount of 5-star reviews for both Vine and non-Vine reviews.



Summary:

Looking at our dataset, we can observe that there does not appear to be any sort of positive bias between Vine and non-Vine reviews. Both percentages of 5-Star reviews for Vine and non-Vine reviews are about 57%. To check if there truly are no biases between the two review types, we could also filter and check lower star reviews to see if there are negative biases. We could also collect statistical distribution data to test the mean, mode, and median of the reviews. 
