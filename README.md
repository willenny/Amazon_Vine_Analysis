# Amazon_Vine_Analysis

## Overview

The purpose of this analysis was to analyze Amazon reviews written by members of the paid Amazon Vine program. Choosing from approximately 50 datasets, we selected sports products to analyze their reviews. Using PySpark, the ETL process was used to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, PySpark was used to determine if there is any bias toward favorable reviews from Vine members in your dataset. 

## Resources
Data Source: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Sports_v1_00.tsv.gz <br />
Software: Google Colab, Python, AWS RDS, pgAdmin4

### Results
- How many Vine reviews and non-Vine reviews were there?
  There were 334 and 61614 Vine and non-Vine reviews, respectively.
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  There were 139 and 32665 Vine and non-Vine 5 star reviews, respectively.
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  There were about 41.6% and 53% of Vine and non-Vines reviews that were 5 stars, respectively.
  
## Summary 
- Approximately 41.6% of the Vine reviews were rated 5 stars, whereas approximately 53% of non-Vine reviews were rated 5 stars. Based on this dataset of sports related purchased, there does not appear to appear any positivity biased for reviews in the Vine program. 
- One additional analysis that I would complete with the dataset is compare the star ratings of individual products broken down into Vine reviews and non-Vine reviews. This will show if Vine reviews are rating individual products higher or lower compared to non-Vine reviews. 
