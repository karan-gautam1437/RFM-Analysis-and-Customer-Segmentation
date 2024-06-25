# RFM (Recency, Frequency, Monetary) Analysis on an Online Retail Customers using K-Means Clustering with Python

The Online Retail data contains customer purchasing history. Including CustomerID, Stock Code, Item Description, Quantity, Unit Price, Invoice Date, and Country.


# Business Understanding
**PROBLEM** : Only have basic customer data but want to know customer behaviour to plan marketing strategy accordingly.

**QUESTION** : 1.How to understand customer behaviour to plan marketing strategy accordingly?
			   2.Calculate the  a) recency (R), b)  frequency (F), c)  monetary value (M) for each customer based on the given dataset? 
			   3.Segment the customers based on their RFM scores using the dataset?
			   Segments with RFM score range: 

				 - Champions: RFM score range - R: 4-5, F: 4-5, M: 4-5 
				 - Loyal customers: RFM score range - R: 3-5, F: 3-5, M: 3-5 
				 - Potential loyalist: RFM score range - R: 4-5, F: 2-3, M: 2-3 
				 - Recent customers: RFM score range - R: 4-5, F: 1-2, M: 1-2 
				 - Promising: RFM score range - R: 4-5, F: 1-2, M: 1-2 
				 - Needs attention: RFM score range - R: 3-5, F: 3-5, M: 3-5 
				 - About to sleep: RFM score range - R: 1-2, F: 1-2, M: 1-2 
				 - At risk: RFM score range - R: 2-5, F: 1-3, M: 1-3 
				 - Can't lose them: RFM score range - R: 1-3, F: 4-5, M: 4-5 
				 - Hibernating: RFM score range - R: 1-2, F: 1-2, M
 
**MEASURE** : A well clustered customer basen on basic data that we have.

# RFM Analysis for Customer Segmentation
RFM analysis is a data-driven customer behavior segmentation methodology in which RFM stands for recency, frequency, and monetary value. The concept is to segment customers based on when their last purchase was (Recency), how many times they have purchased in the past (Frequency), and how much they have spent (Monetary).

RFM analysis enables personalized marketing, improves satisfaction and helps marketers to develop unique, appropriate deals for the right customer groups.

# Conclusion
Most customers are rookie customers and regular customers. There are very few loyal and core customers in this online retail. This may be because the online retail store has not been around for a long time and is still progressing towards success.

# References
* “RFM Analysis: An Effective Customer Segmentation technique using Python” by Ahmat Yuce

https://medium.com/@yuce.ahmet.tr/exploring-rfm-analysis-methodologies-and-innovative-approaches-360f82fc536b

* Pareto Chart

https://tylermarrs.com/posts/pareto-plot-with-matplotlib/
