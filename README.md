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

  - Vine reviews with 5-stars
  
  ![image](https://user-images.githubusercontent.com/78067427/121108847-76819800-c7d8-11eb-9658-ac021e169f99.png)

  - Non-vine reviews with 5-stars

  ![image](https://user-images.githubusercontent.com/78067427/121108918-95802a00-c7d8-11eb-9b6b-cb6563815915.png)

