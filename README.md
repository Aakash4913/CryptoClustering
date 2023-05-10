# CryptoClustering


This project involves clustering cryptocurrencies using K-means clustering based on their price changes. The steps involved in the process are:


STEPS

1. Normalize the data using StandardScaler() module from scikit-learn.
2. Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.
3. Use the elbow method to find the best value for k.
4. Cluster the cryptocurrencies using the best value for k on the original scaled data.
5. Create a scatter plot using hvPlot to visualize the clustered data.
6. Perform Principal Component Analysis (PCA) on the original scaled DataFrame and reduce the features to three principal components.
7. Use the elbow method on the PCA data to find the best value for k.
8. Cluster the cryptocurrencies using the best value for k on the PCA data.
9. Create a scatter plot using hvPlot to visualize the clustered data.


to get started with this project, you'll need to have Python 3.x installed on your system, along with the following libraries:

pandas
scikit-learn
hvplot
matplotlib


Usage

The project consists of a Jupyter Notebook that contains the implementation and explanation of the steps involved in clustering the cryptocurrencies. To run the notebook, follow these steps:

1. Clone or download the repository to your local machine.
2. Open a terminal or command prompt and navigate to the project directory.
3. Run jupyter notebook command to start the Jupyter Notebook server.
4. Open the crypto_clustering.ipynb file in your web browser.
5. Run each cell in the notebook to execute the code and see the results.

Note: Some of the code in the notebook may take several minutes to run, depending on the size of the dataset and the complexity of the computations.