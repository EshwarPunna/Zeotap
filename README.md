# Zeotap
DataScientist Intern Assignment


Data Science Assignment: eCommerce Transactions Dataset
Overview:
This project is an exploration and analysis of an eCommerce Transactions dataset. The dataset consists of three CSV files: Customers.csv, Products.csv, and Transactions.csv. The goal is to perform Exploratory Data Analysis (EDA), build predictive models, and derive actionable insights from the data.

Dataset:
The dataset includes the following files:

Customers.csv:

CustomerID: Unique identifier for each customer.
CustomerName: Name of the customer.
Region: Continent where the customer resides.
SignupDate: Date when the customer signed up.
Products.csv:

ProductID: Unique identifier for each product.
ProductName: Name of the product.
Category: Product category.
Price: Product price in USD.
Transactions.csv:

TransactionID: Unique identifier for each transaction.
CustomerID: ID of the customer who made the transaction.
ProductID: ID of the product sold.
TransactionDate: Date of the transaction.
Quantity: Quantity of the product purchased.
TotalValue: Total value of the transaction.
Price: Price of the product sold.
Objectives:
Exploratory Data Analysis (EDA):

Understand the structure of the data and uncover useful patterns.
Visualize trends, distributions, and relationships between the variables.
Clustering:

Perform customer segmentation based on purchasing behavior.
Apply clustering algorithms (such as K-Means) and evaluate the performance of the clustering models.
Predictive Modeling:
Methodology
Data Preprocessing: Merging and cleaning the datasets.
Exploratory Data Analysis (EDA): Identifying patterns and insights through visualizations and statistical analysis.
Clustering: Using KMeans to form customer segments based on features like total spend, transaction count, and product variety.
Evaluation: Assessing the quality of clusters using DB Index, silhouette score, and other metrics.
Requirements
Python 3.x
pandas
numpy
scikit-learn
matplotlib
seaborn
Build models to predict future transactions or customer behavior.
Files and Naming Conventions:
EshwarRaj_Punna_EDA.pdf: A report on the EDA process and findings.
EshwarRaj_Punna_EDA.ipynb: Jupyter notebook containing the code for EDA.
EshwarRaj_Punna_Lookalike.csv: Output from the clustering (segmentation) model.
EshwarRaj_Punna_Lookalike.ipynb: Jupyter notebook with the clustering code.
EshwarRaj_Punna_Clustering.pdf: A report on clustering results including DB Index, Silhouette Score, and other relevant metrics.
EshwarRaj_Punna_Clustering.ipynb: Jupyter notebook containing the clustering code.
Instructions:
Clone this repository to your local machine:

bash
Copy
Edit
git clone https://github.com/yourusername/ecommerce-data-science-assignment.git
Install required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Load the dataset by downloading the files from the links provided:

Customers.csv
Products.csv
Transactions.csv
Review the EDA and clustering code in EshwarRaj_Punna_EDA.ipynb and EshwarRaj_Punna_Lookalike.ipynb for insights and results.

Evaluation Criteria:
Accuracy and depth of the clustering model.
Exploratory data analysis insights and visualizations.
Clear presentation of findings, including metrics such as DB Index and Silhouette Score.
Clarity in documentation (README, code comments, and reports).
License:
This project is licensed under the MIT License - see the LICENSE file for details.

