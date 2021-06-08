# Amazon_Vine_Analysis

### Overview of the analysis

In this project, dataset showing reviews of musical instrument product was selected to determine if there is any bias toward favorable reviews from Vine members in the dataset. PySpark was used to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin, then PySpark was used further to determine the biasness of the dataset.

### Results

After analysis was carried out, below are relevant questions and answers on the dataset

- How many Vine reviews and non-Vine reviews were there?
  
  - Vine reviews
  
  ![image](https://user-images.githubusercontent.com/78067427/121107182-759b3700-c7d5-11eb-9780-37a619130047.png)

  - Non-vine reviews
  
  ![image](https://user-images.githubusercontent.com/78067427/121107279-9fecf480-c7d5-11eb-817e-f09d304a4d51.png)

  The total number of reviews are 904,763
  The total number of Vine reviews with the above criterias is 14537, of which Vine reviews and non-Vine reviews are 60 & 14,477 respectively.
 
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

  - Vine reviews with 5-stars & its percentages
  
  ![image](https://user-images.githubusercontent.com/78067427/121108847-76819800-c7d8-11eb-9658-ac021e169f99.png)

  - Non-vine reviews with 5-stars & its percentages

  ![image](https://user-images.githubusercontent.com/78067427/121108918-95802a00-c7d8-11eb-9b6b-cb6563815915.png)
  
### Summary
 
It is inconclusive to say the 5-stars ratings was helpful to indicate to potential customers an unbiased view of the vine program.
 
From the results, 5-stars rating of paid vine is 34 of 60 reviews. This looks pretty great, however it is only 0.23% of the vine dataset which cannot represent a positive outlook of the product line. We need to understand that this 5-star ratings didn't result a positive view for potential customers, but having to ignore 3-4stars rating which can be very useful makes the analysis biased to accept the results were unfavourable.

Further analysis should be carried out on 3-5stars rating which could show the product line has a positive overview. Also, the verified purchases should be used as a criteria, because most reviews can be influenced by one or group of persons trying to promote/downgrade the product line.
