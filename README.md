# Amazon_Vine_Analysis

## Project Overview

In this project, we examined Amazon reviews of Digital Video Games, using Pyspark to perform ETL processes. We extracted the data, transformed the data, and connected it to the RDS Database generated through the AWS server service. Using the review, we aim to determine if there is bias among the reviews from Vine members. 


## Results

* How many Vine reviews and non-Vine reviews were there?
 * When we ran our ETL processes on the Digital Video Games review dataset, to our surprise we found that there were no Vine reviews.
  ![Vine_Reviews](https://user-images.githubusercontent.com/84881187/134436944-b9848f15-f9ae-48a6-8180-49a907f956b4.PNG)

  ![Vine_Table_SQL](https://user-images.githubusercontent.com/84881187/134436951-a2186bac-b262-4077-ac4b-c1a9b9ef9ee7.PNG)
  
  ![reviews_overview_V2](https://user-images.githubusercontent.com/84881187/134437079-15ae62ec-160b-4936-b136-53ec848edf18.PNG)

  
*How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  *  Since we had no Vine reviews to analyze, we looked at how many non-Vine reviews were 5-Stars
    
   ![Non-Vine_Reviews](https://user-images.githubusercontent.com/84881187/134437155-0b348441-6246-4dd9-b8d5-ebdb35447906.PNG)
   ![5-Star_Reviews](https://user-images.githubusercontent.com/84881187/134437158-7f026700-358f-43ae-b4a2-0dbcb3465251.PNG)
![Vine_Reviews](https://user-images.githubusercontent.com/84881187/134455253-f150dbcd-fc79-4410-9c34-39c07c1d7df9.PNG)

*What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
* Out of all of the reviews of Digital Video Games, about 37.45% of them had a 5-Star rating. Since all of our reviews are non-Vine, the total non-Vine reviews that are 5-Stars are also 37.45%. Out of 5-Star Reviews 40.48% of the reviews were Paid Reviews, and 34.50% were Unpaid reviews.
![5-Star_Reviews](https://user-images.githubusercontent.com/84881187/134450122-57c9a40b-160f-432e-bcc9-a39104327b19.PNG)
![Percentage of Reviews](https://user-images.githubusercontent.com/84881187/134450124-878330b8-eb7a-4bca-8225-bdc9cc6823ed.PNG)


Summary:

Looking at our dataset, it is unclear if there is a bias towards Vine Reviews for Digital Games, because in out sammple there are no Vine Reviews with 5-Stars. We would need to do an analysis of filtered reviews for the other levels of review tiers, to see if Vine reviews might have been biased to give lower reviews. Our data shows that there is no bias for Vine reviews when it comes for leaving 5-Star reviews, but we do not know if they could be biased at leaving lower quality star reviews. 

An additional analysis is recommended to support the statement (2 pt)
faf
