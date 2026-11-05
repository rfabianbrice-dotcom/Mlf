# Mlf | Machine learning exercises

A collection of Python exercises on data cleaning, visualization, regression, classification, and clustering. Start with the house-price notebook to train a model using the data included in this repository.

## Run the house-price example

1. Clone the repository and launch JupyterLab in its root folder.

   ```sh
   git clone https://github.com/rfabianbrice-dotcom/Mlf.git
   cd Mlf
   python -m pip install jupyterlab pandas numpy matplotlib seaborn scikit-learn
   python -m jupyterlab
   ```

2. Open [price prediction mlf.ipynb](price%20prediction%20mlf.ipynb). In the data-loading cell, change `pd.read_csv('house.csv')` to `pd.read_csv('house_price.csv')`.
3. Run the cells in order. When prompted, enter a house size in square feet. The notebook prints a predicted price and plots the fitted line against the observed prices.

The included [house_price.csv](house_price.csv) contains 50 records with house size, bedroom count, age, and price. The example uses house size alone to predict price and evaluates the fit with R² on a held-out test set.

## Other notebooks

To run these exercises, supply the listed CSV beside the notebook. The repository includes only the housing CSV.

| Notebook | Exercise | CSV to supply |
| --- | --- | --- |
| [Finance analytics](Finance_Analytics_Dataset%20.ipynb) | Chart transaction counts by category, payment mode, and debit or credit type. Compare transaction amounts across customer segments and categories. | `2. Finance_Analytics_Dataset.csv` |
| [Iris classification](MLF.ipynb) | Predict species from four flower measurements with a depth-three decision tree. Inspect the confusion matrix and plot the tree. | `IRIS.csv` |
| [Exercise 6 · Used-car prices](MLF%20Practice%20Exercise%206_Task_14.ipynb) | Compare linear regression, a decision tree, and a random forest on selling price using MAE, MSE, RMSE, and R². | `car data.csv` |
| [Exercise 7 · Customer churn](MLF%20Practice%20Exercise%207_Task_15.ipynb) | Compare logistic regression, a decision tree, and a random forest. Select a model by F1 score and plot the random forest’s most important features. | `WA_Fn-UseC_-Telco-Customer-Churn.csv` |

Three additional notebook files serve as references or placeholders. [fabian logestic.ipynb](fabian%20logestic.ipynb) contains a text export of a purchase-prediction exercise using `Social_Network_Ads.csv`. [Housing Price Prediction fabian.ipynb](Housing%20Price%20Prediction%20fabian.ipynb) contains only a page marker, and [KNN code - fabian.ipynb](KNN%20code%20-%20fabian.ipynb) is empty.

## PDF walkthroughs

| Walkthrough | What it covers |
| --- | --- |
| [Cleaning customer orders](Fabian_mlf.pdf) | Handle missing values, duplicates, and invalid quantities in customer order data and calculate order totals. |
| [Exploring drug data](13.MLfpractise-.pdf) | Inspect 200 records and visualize how age and sodium-to-potassium ratio vary across the data. |
| [Weather survey classification](12.Fabbian.MLF.pdf) | Fit a decision tree to weather-checking survey responses and visualize its confusion matrix. |
| [Random forest classification](Random_Forest_0_31647500_1790577378.pdf) | Classify car acceptability from vehicle attributes and plot feature importance. |
| [Support vector classification](SVM_0_88209500_1790577401.pdf) | Apply support vector classification to the car acceptability data and inspect confusion matrices. |
| [Hierarchical clustering](HierarchicalClustering_0_10300700_1790577314.pdf) | Build a Ward-linkage dendrogram for ten points and assign them to two clusters. |
| [K-means clustering](K_Means_Clustering_0_38352200_1790577348.pdf) | Group 100 random two-dimensional points into three clusters and plot their centroids. |
