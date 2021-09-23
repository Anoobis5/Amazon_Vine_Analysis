# Amazon_Vine_Analysis

## Project Overview

In this project, we examined Amazon reviews of Digital Video Games, using Pyspark to perform ETL processes. We extracted the data, transformed the data, and connected it to the RDS Database generated through the AWS server service. Using the review, we aim to determine if there is bias among the reviews from Vine members. 


## Results

* How many Vine reviews and non-Vine reviews were there?
  When we ran our ETL processes on the Digital Video Games review dataset, to our surprise we found that there were no Vine reviews.
  ![Vine_Reviews](https://user-images.githubusercontent.com/84881187/134436944-b9848f15-f9ae-48a6-8180-49a907f956b4.PNG)

  ![Vine_Table_SQL](https://user-images.githubusercontent.com/84881187/134436951-a2186bac-b262-4077-ac4b-c1a9b9ef9ee7.PNG)
  
  ![reviews_overview_V2](https://user-images.githubusercontent.com/84881187/134437079-15ae62ec-160b-4936-b136-53ec848edf18.PNG)

  
*How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    Since we had no Vine reviews to analyze, we looked at how many non-Vine reviews were 5-Stars
    
   ![Non-Vine_Reviews](https://user-images.githubusercontent.com/84881187/134437155-0b348441-6246-4dd9-b8d5-ebdb35447906.PNG)
   ![5-Star_Reviews](https://user-images.githubusercontent.com/84881187/134437158-7f026700-358f-43ae-b4a2-0dbcb3465251.PNG)

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

Summary:

The summary states whether or not there is bias, and the results support this statement (2 pt)
An additional analysis is recommended to support the statement (2 pt)
faf
