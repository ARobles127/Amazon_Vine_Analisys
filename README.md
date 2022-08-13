# Amazon_Vine_Analysis


## Overview of the analysis: 

In this project we are going to analyze reviews written by members of the paid Amazon Vine program, where members receive a product from Amazon and then they are required to write a review. Since the members are incentivized this could potentially create bias towards the reviews written as part of the Vine program. Our goal is to analyze the dataset by creating dataframes and then filtering the necessary columns as well as applying functions to provide insights that will help detect biased reviews.  



## Results:

The following images represent our findings and help answer key questions pertaining to the dataframe assigned to this project. 

- How many Vine reviews and non-Vine reviews were there? 
The total paid Vine reviews were 1,207. Total non-Vine reviews were 97,839. 		

![paid_reviews.png](https://github.com/ARobles127/Amazon_Vine_Analysis/blob/main/Images/paid_reviews.png) 

![unpaid_reviews.png](https://github.com/ARobles127/Amazon_Vine_Analysis/blob/main/Images/unpaid_reviews.png)    


- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
There were 509 Vine five star reviews. There were 45,858 non-Vine star reviews.

![paid_five_star.png](https://github.com/ARobles127/Amazon_Vine_Analysis/blob/main/Images/paid_five_star.png) 

![unpaid_fivestar.png](https://github.com/ARobles127/Amazon_Vine_Analysis/blob/main/Images/unpaid_fivestar.png)  


- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
The percentage of Vine five star reviews was 42.17%. The percentage of non-Vine five star reviews was 46.87%

![paid_percentage_five.png](https://github.com/ARobles127/Amazon_Vine_Analysis/blob/main/Images/paid_percentage_five.png) 

![unpaid_percentage_five](https://github.com/ARobles127/Amazon_Vine_Analysis/blob/main/Images/unpaid_percentage_five.png) 



## Summary: 
To reduce bias we analyzed a large dataset containing reviews where only 1,200 belong to the paid Vine program against the almost 98,000 from non-Vine program. From the paid reviewers,  42% gave a five star review to the product, whereas 47% of the non-paid reviewers gave a five star review. In conclusion, we determine there is no bias on the reviews written by the Amazon Vine program. 

As part of an analysis to find the statistics data we could apply functions from Pandas library to our dataset to find the media, mean and mode. 

![stats_data.png](https://github.com/ARobles127/Amazon_Vine_Analysis/blob/main/Images/stats_data.png) 
