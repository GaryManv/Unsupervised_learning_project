# Unsupervised_Learning

### Goal
Gain insights from the data sets and communicate them to stakeholders to make informed business decisions.

### Steps

Imported and cleaned the data sets, analyzed and visualized the relationships between the different variables, handled missing values and outliers, and performed feature engineering as needed.<br>

Performed clastering using KMean and Hierarchical Clustering. 

Checked correlation between customers spending and clusters, their dependace to region and channel

Conducted PCA analysis.

### Conclusion

No missing values or noticable fluctuaction in the dataset. All variables shows positively skewed distribution with high values at the beginning and smaller values to the right. Data transformation used to make the data close to a normal distribution.

In spite of visible outliers don't seems error to me, so kept them all.

Clearly visible correlations detected between Grocery and Detergents_Paper, and Milk and Grocery. It was conformed by correlation matrix showing strong positive correlations.

Logaritmic transformation have been chosen as it showed better results compared with square root transformation.

Hierarchical clustering and k-means clustering partially complement each other. In both cases, 4 clusters was a better choice.

New aggregation column was added to the dataset to sum of 6 numeric features and then check customer's spend by clusters.

Cluster #0 represents budget-conscious customers. Marketing strategy to be reviewed to involve those customers.

Cluster #3 represent VIP customers. Marketing strategy to be reviewed to identify their preferencies and make them even more loyal by additional offers.

Note: These marketing strategies are not channel or region specific.

Dataset and the number of features allow not to sacrifice much of the information.95% of variance was choosed as a treshold and 6 PCs were kept.

It was difficult to find any bussiness insight from PCA for unsupervised learning model as it's main role (as I understand) is in reducing the dementionality but in provided dataset it's not a big concern.

### Files in repo
Wholesale_Data.csv - dataset consisting of customers spending devided by product categories, distribution channels and regions<br>

Unsupervised_Learning_Project_GM.ipynb - file where EDA, preprocessing, clustering, PDA and modeling were combined.

README.MD - short description of the project