# Amazon_Vine_Analysis
## **Overview**
From our previous work on SellBy, Jennifer has asked us to analyse Amazon reviews written by members fo the paid Amazon Vine Prorgam.  For this selection, I focused on the video game reviews.  Utilizing Google Colaboratories and Pyspark to perform the ETL from AWS webserver, the objective is to determine if there is a favorable review bias from the Vine members from the supplied dataset. 

## **Resources**
Postgres 14.2, PG Admin 6.7, Google CoLaboratory, Pyspark 3.03, AWS
Amazon Review datasets

## **Results**
### *How Many Vine Reviews and non-Vine Reviews were there?
- There were a total of 4,291 Vine reviews.
- 40,471 reviews from non-Vine.
<img width="264" alt="Screen Shot 2022-04-03 at 6 20 08 PM" src="https://user-images.githubusercontent.com/91889241/161453230-4e1f1ff9-0810-452c-879f-a24fa1a9dda0.png">

### *How Many Vine Reviews were 5 stars?  How many non-Vine reviews were 5 stars?
- There were a total of 15,711 5 star reviews
- 15,663 were non-Vine based.
<img width="262" alt="Screen Shot 2022-04-03 at 6 21 51 PM" src="https://user-images.githubusercontent.com/91889241/161453317-1e3a1f77-7d2d-4100-b9d8-1599da541094.png">

### *What percentage of Vine reviews were 5 stars?  What percentage of non-Vine reviews were 5 stars?
- 38.2% were 5 star reviews from Vine.
- 38.9 were non-Vine 5 star reviews.
<img width="1174" alt="Screen Shot 2022-04-03 at 6 24 23 PM" src="https://user-images.githubusercontent.com/91889241/161453413-8b9b5b3d-bf47-4484-bc52-5a76f9f3d52d.png">

## **Summary**
