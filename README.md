# Amazon Vine Analysis

## Overview

In this project I analyzed Amazon reviews written by members of the paid Amazon Vine program. This program allows manufacturers and publishers to pay a small fee to Amazon, provide products to Amazon Vine members, and then receive reviews for their products.

The purpose of this project is to determine if there is a bias toward favorable reviews from paid Amazon Vine members. 

## Results

My analysis began with filtering an Amazon reviews dataset for two things. First, I filtered our data to show only reviews with 20 or more helpful reviews. Then, I filtered the data again to select only entries where 50% of the total reviews were helfpul. 

Then, I sorted the data into paid and unpaid reviews. A sample of these data frames can be seen below. 

![paid_df](https://github.com/nicole-tough/Amazon_Vine_Analysis/blob/main/Images/paid_df.PNG)

![unpaid_df](https://github.com/nicole-tough/Amazon_Vine_Analysis/blob/main/Images/unpaid_df.PNG)

Finally, I selected the data points necessary by filtering the dataframes that I created. The results of these fitlers can be seen below. 

![paid analysis](https://github.com/nicole-tough/Amazon_Vine_Analysis/blob/main/Images/paid_analysis.PNG)

![unpaid analysis](https://github.com/nicole-tough/Amazon_Vine_Analysis/blob/main/Images/unpaid_analysis.PNG)

Ultimately, I found the following results:

### Paid Reviews
Total number of paid reviews:  613 <br />
Number of paid 5 star reviews:  222 <br />
Percent of paid five star reviews:  36.22%

### Unpaid Reviews
Total number of unpaid reviews:  64968 <br />
Number of unpaid 5 star reviews:  30543 <br />
Percent of unpaid five star reviews:  47.01%

## Summary

I did not find any positive bias towards paid reviews. Of the paid reviews, 36.22% of them were 5 star reviews compared with 47.01% of unpaid reviews. 

In order to further test this, I recommend comparing 1-4 star reviews for both paid and unpaid reviews. While my analysis shows that there is no positive bias for 5 star reviews, there may be bias against giving a 1 or 2 star review if members are being paid and given free products. 
