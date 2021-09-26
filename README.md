# Amazon_Vine_Analysis

## Overview
- Determine impact that the Vine program has on reviews for watches sold on Amazon.

## Resources
- Software: Google Colab, PySpark, PgAdmin, RDS
- The data was collected from https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Watches_v1_00.tsv.gz

## Results
- Review totals
	- Vine: 43
	- non-Vine: 7720
- Number of 5 Star reviews
	- Vine: 14
	- non-Vine: 4018
- Percentage of 5 star reviews
	- Vine: 32.56%
	- non_Vine: 52.05%

- Review Summary:

  ![Review Summary](https://github.com/jediracer/Amazon_Vine_Analysis/blob/main/images/Vine_analysis.png)	
  
## Summary

- Based on the data, it would seem that there is not a bias on paid(Vine) reviews vs non-paid reviews.  There is higher percentage of 5-star ratings in the non_Vine group.
- To further analyize the impact on Vine reviews, I would suggest perfoming the same tasks on the remaining star ratings (0 through 4). 