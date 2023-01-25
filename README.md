# Amazon_Vine_Analysis 

Deliverable 3: A Written Report on the Analysis (README.md)

**Overview of the analysis:

This project demonstrates effective way of Extracting, Transforming & Loading dataset.
Used PySpark, Postgresql Pandas to determine if there is any bias toward favorable reviews from Vine members in your dataset.
Bias determination is necessary to weigh the reliability of positive reviews on categorical items. Companies pay Amazon a small fee to provide products to the Amazon Vine members in return for a required review published on the product. If company's rely on these product reviews to strategize future action items, it is important to ensure that these reviews are actually reflective of the product, by isolating the reviews published by "marketing dollars" vs those driven organically.
We will determine bias by iteratively narrowing into our dataset to filter for only helpful reviews, based on a minimum count of total votes and the proportion of helpful votes compared to the total for an indiviual product. Once the paid vs non-paid reviews are identified, we will compare each groups review count in respect to the number of 5-star reviews.

![image](https://user-images.githubusercontent.com/40743420/214451824-111c8f0d-cd2a-4a91-9941-0a55879418ab.png)


Results:
- How many Vine reviews and non-Vine reviews were there?
•	Total Vine reviews: 33.000000
•	Total non-Vine reviews: 45388.000000


- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
•	5-star Vine reviews: 15.000000
•	5-star non-Vine reviews: 23733.000000


- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- •	% of 5-star Vine reviews: 45.45%
•	% of 5-star non-Vine reviews: 52.28%

Summary:
The Analysis above is indicating that there is infact NO evidence of positivity bias for Vine-member reviews. However, it must be stated that I cannot say with certainty that bias doesn't exist, as this particular exercise lacks much external validity--the sample size is far too small after extensive "one size fits all" filtering, and the dataset is extremely imbalanced between non-vine vs vine reviews.

One cannot adequately compare bias simply on the frequency of 5 star reviews and its penetration to the total number of helpful votes. For example, although it seems that the % of 5-star vine reviews are only lagging by less than 10 percentage points, 24,000 5-star votes is a much more robust, meaningful datapoint than 15.

We need a larger, more evenly distributed dataset of vine reviews via oversampling, undersampling, or performing ETL on a more actively shopped category, to create a more accurate comparison of the two groups to draw bias conclusions.

We should provide more analysis to amplify our findings against the non-preprocessed ahd filtered data. 
