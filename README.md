# Amazon_Vine_Analysis 

Deliverable 3: A Written Report on the Analysis (README.md)

**Overview of the analysis:

This project demonstrates effective way of Extracting, Transforming & Loading dataset.
Used PySpark, Postgresql Pandas to determine if there is any bias toward favorable reviews from Vine members in your dataset.
Bias determination is necessary to weigh the reliability of positive reviews on categorical items. Companies pay Amazon a small fee to provide products to the Amazon Vine members in return for a required review published on the product. If company's rely on these product reviews to strategize future action items, it is important to ensure that these reviews are actually reflective of the product, by isolating the reviews published by "marketing dollars" vs those driven organically.
We will determine bias by iteratively narrowing into our dataset to filter for only helpful reviews, based on a minimum count of total votes and the proportion of helpful votes compared to the total for an indiviual product. Once the paid vs non-paid reviews are identified, we will compare each groups review count in respect to the number of 5-star reviews.


Results:
- How many Vine reviews and non-Vine reviews were there?
•	Total Vine reviews: 
•	Total non-Vine reviews: 


- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
•	5-star Vine reviews: 
•	5-star non-Vine reviews: 


- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- •	% of 5-star Vine reviews: 
•	% of 5-star non-Vine reviews: 

**Summary:


