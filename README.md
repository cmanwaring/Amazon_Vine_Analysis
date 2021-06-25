# Amazon_Vine_Analysis
## Purpose
The purpose of this project was to take a large amount of data, load it into an RDS, ETL through Colab, and then analyze the data to determine if there is a positivity bias of Vine reviews.
## Results
### Total Reviews
 - Overall: 37921  
![Total Overall Reviews](images/overall_reviews.png)
 - Vine Reviews: 90 (0.2%)  
![Total Vine Reviews](images/total_vine_reviews.png)
 - Non-Vine Reviews: 37831 (99.8%)  
![Total Non-Vine Reviews](images/total_nvine_reviews.png)
### Total 5-Star Reviews
 - Overall: 14748 (38.9% of total)  
![Overall 5-Star Reviews](images/overall_five_reviews.png)
 - Vine 5-Star Reviews: 44  
![5-Star Vine Reviews](images/vine_five_reviews.png)
 - Non-Vine 5-Star Reviews: 14704  
![5-Star Non-Vine Reviews](images/nvine_five_reviews.png)
### Percentage of 5-Star reviews by Vine Y/N
 - Vine 5-Star Review Percentage: 48.9%  
![Vine 5-Star Percentage](images/vine_five_perc.png)
 - Non-Vine 5-Star Review Precentage: 38.9%  
![Non-Vine 5-Star Percentage](images/nvine_five_perc.png)
## Summary
Because there is a 10% difference in the 5-Star review percentage between Vine reviews and non-Vine reviews, I do believe that there may be some positivity bias for reviews in the Vine program. Although, There is such a small number of Vine reviews compared to the number of Non-Vine reviews, I would be curious to explore just how much the Vine positivity bias would actually impact the overall dataset. My guess would be that the positivity bias would have little effect on a dataset that is so largely inproportionately Non-Vine dominant.
