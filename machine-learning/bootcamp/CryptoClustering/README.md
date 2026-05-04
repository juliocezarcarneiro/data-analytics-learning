# CryptoClustering

# CryptoClustering - Unsupervised Learning Project

### Overview
This project uses Python and unsupervised learning (K-Means clustering, PCA) to analyze cryptocurrency price changes and identify patterns based on 24-hour and 7-day trends.

### Key Tasks
* Data Preprocessing: Normalize cryptocurrency market data using StandardScaler().

* Optimal K-Value Selection: Use the elbow method to determine the best number of clusters (k).

* K-Means Clustering: Group cryptocurrencies based on price trends.

* PCA Optimization: Reduce dimensionality and compare clustering results.

* Visualization: Generate scatter plots using hvPlot.

### Files
* Crypto_Clustering.ipynb: Jupyter Notebook containing the full analysis.

* crypto_market_data.csv: Dataset with cryptocurrency price change metrics.

### Instructions
    1. Data Preparation
        * Load crypto_market_data.csv into a DataFrame.

        * Normalize data using StandardScaler().

        * Set coin_id as the index.

    2. Finding the Best K-Value (Elbow Method)
        * Compute inertia for k = 1 to 11.

        * Plot the elbow curve to determine the optimal k.

    3. K-Means Clustering (Original Data)
        * Fit a K-Means model using the best k.

        * Predict clusters and visualize using hvPlot:

        * X-axis: price_change_percentage_24h

        * Y-axis: price_change_percentage_7d

        * Color: Cluster labels

        * Hover: coin_id

    4. Optimizing with PCA
        * Reduce features to 3 principal components.

        * Check explained variance.

        * Repeat K-Means clustering on PCA-transformed data.

        * Compare results with the original clusters.

    5. Composite Visualization
        * Plot both original and PCA clusters side-by-side.

        * Analyze the impact of dimensionality reduction.

### Key Questions Answered
* What is the best k value for the original and PCA data?

* How much variance is explained by the first 3 principal components?

* What is the impact of using fewer features (PCA) on clustering?

### References

scikit-learn. K-Means clustering. Retrieved from: https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html

scikit-learn. StandardScaler (normalization). Retrieved from: https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html

scikit-learn. PCA (dimensionality reduction). Retrieved from: https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html

hvPlot. Interactive visualizations. Retrieved from: https://hvplot.holoviz.org/

Pandas. Data manipulation. Retrieved from: https://pandas.pydata.org/docs/

NumPy. Numerical computing. Retrieved from: https://numpy.org/doc/

Matplotlib. Plotting library. Retrieved from: https://matplotlib.org/stable/contents.html

Seaborn. Statistical visualizations. Retrieved from: https://seaborn.pydata.org/

OpenAI. ChatGPT. Retrieved from: https://chat.openai.com

