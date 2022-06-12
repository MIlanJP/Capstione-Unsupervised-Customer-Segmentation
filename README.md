# Capstone-Unsupervised-Customer-Segmentation


Problem Description
In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

Data Description

Attribute Information:
InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.<br>
StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product..<br>
Description: Product (item) name. Nominal..<br>
Quantity: The quantities of each product (item) per transaction. Numeric..<br>
InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated..<br>
UnitPrice: Unit price. Numeric, Product price per unit in sterling..<br>
CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer..<br>
Country: Country name. Nominal, the name of the country where each customer resides..<br>


1.	In this project, we have several techniques to perform analysis through in the dataset we dint have any information on customers age gender education, and other specific details hence we were not able to perform customer segmentation based on the case the of demographic psychographic and behavioral segments.
2.	The best way to do clustering using customer data is RFM analysis i.e. we track the recent visit (Recency), Frequency of customer visit (Frequency), and amount of money spent by customers (Monetary),i.e. together we call this analysis RFM Analysis
3.	By the use of RFM analysis we will be able to  segment customers into Potential Customers, Average Customers, Lost Potential Customer, and several other segments, and this segmentation of customers are helpful for the companies so that they have various methods to treat different segment customers to increase the organization’s profit i.e. For Example: In case if the customer belongs to a lost potential customer they provide some attracting offers to retain the lost potential customers, Example 2: If the customers are segmented as Best Loyal Customers then the company provides services to them on high priority to make them maintain their consistency of holding the Best Loyal Customer Badge
4.	We started with a simple binning and quantile-based simple segmentation model first then moved to more complex models because simple implementation helps to have a first glance at the data and know where/how to exploit it better. 
5.	Then we moved to k-means clustering and visualized the results with different several clusters. As we know there is no assurance that k-means will lead to the global best solution. We moved forward and tried Hierarchical Clustering and DBSCAN clustering as well.
6.	 We created several useful clusters of customers based on different metrics and methods to categorize the customers based on their behavioral attributes to define their value, loyalty, profitability, etc for the business. Though significantly separated clusters are not visible in the plots, the clusters obtained are fairly valid and useful as per the algorithms and the statistics extracted from the data.
7.	 Segments depend on how the business plans to use the results and the level of granularity they want to see in the clusters. Keeping these points in view we clustered the major segments based on our understanding as per different criteria
