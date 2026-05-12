# 📊 Live Selling Engagement Clustering using Unsupervised Machine Learning

A Machine Learning project focused on analyzing and clustering Facebook live-selling engagement behavior using unsupervised learning techniques. The project identifies customer interaction patterns from social media live-selling posts using clustering algorithms and dimensionality reduction techniques.

---

# 📌 Project Overview

Social media live-selling has become an important digital marketing strategy for online businesses. Understanding audience engagement patterns helps sellers optimize content strategy and improve customer interaction.

This project performs clustering analysis on Facebook live-selling engagement data to discover meaningful behavioral patterns among user interactions.

---

# 🎯 Objectives

- Analyze engagement behavior of live-selling posts
- Identify meaningful customer interaction patterns
- Compare clustering algorithms for performance evaluation
- Visualize clusters using dimensionality reduction techniques

---

# 📂 Dataset Information

The dataset contains over **7000 Facebook live-selling posts** from Thai fashion and cosmetics retailers.

### Features Included:
- Number of Reactions
- Comments
- Shares
- Likes
- Loves
- Wows
- Hahas
- Sads
- Angrys
- Post Type
- Posting Time

---

# ⚙️ Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 🔍 Data Preprocessing

Performed the following preprocessing techniques:

- Handling missing values
- Feature selection
- Data normalization and scaling
- Exploratory Data Analysis (EDA)
- Categorical feature handling

---

# 🧠 Clustering Algorithms Implemented

## 🔹 K-Means Clustering
- Partition-based clustering algorithm
- Achieved the best clustering performance

## 🔹 Hierarchical Clustering
- Agglomerative clustering approach
- Used for hierarchical relationship analysis

## 🔹 DBSCAN
- Density-based clustering technique
- Effective for detecting noise and outliers

## 🔹 Gaussian Mixture Model (GMM)
- Probabilistic clustering approach
- Supports soft clustering assignments

---

# 📉 Dimensionality Reduction

### Principal Component Analysis (PCA)

Applied PCA for:
- Feature reduction
- Cluster visualization
- Improved interpretability

---

# 📈 Model Evaluation Metrics

The clustering models were evaluated using:

- Silhouette Score
- Davies–Bouldin Index
- Calinski–Harabasz Score

---

# 🏆 Performance Comparison

| Algorithm | Silhouette Score | Performance |
|-----------|------------------|-------------|
| K-Means | 0.677 | Best |
| Hierarchical Clustering | 0.633 | Good |
| GMM | 0.199 | Moderate |
| DBSCAN | -0.032 | Poor |

---

# 📌 Key Insights

- K-Means achieved the best clustering performance
- Engagement patterns varied significantly across post types
- Reactions, comments, and shares strongly influenced cluster formation
- PCA visualization showed well-separated engagement clusters

---

# 📁 Project Structure

```bash
Live-Selling-Engagement-Clustering/
│
├── data/
│   └── Live.csv
│
├── notebook/
│   └── Live-Selling-Engagement-Clustering.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 🚀 Future Improvements

- Real-time engagement analysis
- Integration with social media APIs
- Interactive dashboard visualization
- Advanced deep learning based clustering approaches

---

# 💡 Conclusion

This project demonstrates how unsupervised machine learning techniques can effectively identify engagement behavior patterns in social media live-selling data.

Among all implemented models, **K-Means achieved the best clustering performance** and provided meaningful customer engagement insights.

---

# 👩‍💻 Author

### Ankita Rani Patro
