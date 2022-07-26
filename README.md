Code Folder:
CS5664_TextPreProcessing_MetaData.ipynb
	- Contains:
		1. Parsing the metadata and produce essential pandas dataframes
		2. Creating product-copurchase edge lists

CS5664_NetworkAnalysis.ipynb
	- Contains:
		1. Network information such as degree centrality analysis
		2. Node degree distribution.
		3. Powerlaw and heavy tail distribution

CS5664_MetaData_and_ProductReviews_Analysis_EGO_Graph_Recommendations.ipynb
	- Contains:
		1. Text preprocessing.
		2. Meta data and Product Review processing.
		3. Sentiment Analysis
		4. Topic Modeling
		5. EgoGraph based Product Recommendations using product Titles.

CS5664_Product_Recommendations_MachineLearning.ipynb
	- Contains:
		1. Review rating analysis.
		2. KNN based SVD experimentation
		3. Hyperparameter tuning and training SVD with best params
		4. Product recommendations based on reviews.


Datasets Folder:
	Appliances.json - Reviews information for electronic appliances
	Magazine_Subscriptions.json - Reviews information for Magazines
	amazon-books.csv - information on products (books) generated from amazon-meta.txt
	amazon-books-copurchase.edgelist - information generated from amazon-meta.txt contains purchase - copurchase similar edgelist
	amazon-meta.txt - Data downloaded from SNAP
	products_copurchases_links.csv - Purchase Copurchase list for all products generated from amazon-meta.txt used for network analysis
	products_data.csv - contains all product information.

Supplementary Materials / Visualizations Folder:
	1. Network Analysis plots
	2. WordClouds - Reviews, Sentiments, Topics
	3. Sentiment Analysis plots
	4. LDA topics


