# Markov-Model-for-Stocks
Building Markov Model for Stocks after applying Clustering to Time Series data in Python

<br/>

### 1. Applying k-means clustering to identify market states
1. Data Preparation
2. Feature Preparation
3. **Check for Multicollinearity**
4. **Normalize** (as some features might dominate due to larger scale) w/ `MinMaxScaler`
5. **Finding Optimal k** w/ WCSS or **elbow method** 
6. Fit the model and identify the clusters
7. Analyzing clusters
8. Analyzing each cluster


#### [View Clustering](https://github.com/s1dewalker/Markov-Model-for-Stocks/blob/main/py_files/MarkovModel1_Clustering.ipynb)
<br/>

Python libraries used: `pandas`, `yfinance`, `sklearn`, `matplotlib`, `seaborn`

<br/>

### 2. Building Markov Model to create a transition matrix
#### [View Model](https://github.com/s1dewalker/Markov-Model-for-Stocks/blob/main/py_files/MarkovModel2-Building_MarkovModel.ipynb)
