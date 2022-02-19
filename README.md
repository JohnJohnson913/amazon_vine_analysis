Challenge 16 -- Big Data and Amazon Vine

## Amazon Vine Overview
My organization is looking to gauge the success of pay-for-reviews on amazon product types which will allow us to send products to vine customers in exchange for a review.  For this analysis I've conducted the analysis on device accessories.  Today we will be looking to see if there if there is influence in these reviews that may result in a less objective product review.

## Here's what we found

 - For the cellular accessories category we found a total of 61,724 reviews. 

https://github.com/JohnJohnson913/amazon_vine_analysis/blob/6169021f7a15e339bc321e768e29096fa608f377/total_reviews.png

 - Of the total reviews 585 were paid. 

https://github.com/JohnJohnson913/amazon_vine_analysis/blob/6169021f7a15e339bc321e768e29096fa608f377/total_paid_reviews.png

 - Though a very small percentage of paid reviews we should still be able to verify objectivity.  To much surprise, a lesser percentage of 5 star rated reviews were producted from the paid reviews.  It's important to note that the paid reviews were not incentivised to produce a positive review.

https://github.com/JohnJohnson913/amazon_vine_analysis/blob/6169021f7a15e339bc321e768e29096fa608f377/paid_vs_unpaid_total.png
https://github.com/JohnJohnson913/amazon_vine_analysis/blob/6169021f7a15e339bc321e768e29096fa608f377/paid_vs_unpaid_percentage.png

## In Summary

To reiterate, it's important to note that the paid reviews result in a lesser percentage of 5 star reviews than the unsoliceted reviews.  This represents the likelyhood of that producing results from paid reviews doesn't result in a positivity bias and will result in possibly more objective reviews.  To provide additional insight into the efficacy may be to also review the one star ratings as well.   Do we see the same behavior from individuals that are not pleased with the product.  The invernse is often as telling as the data provided in this analysis.
