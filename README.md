# 🧑🏻‍🤝‍🧑🏽💁🤝📊Customer Segmentation Analysis Using Clustering📈🕵️🔎🔢

<img src="img.jpg">

## Overview 🔍
This project leverages clustering techniques to segment customers based on various attributes such as demographics, purchasing behavior, and response to marketing campaigns. By identifying distinct customer segments, businesses can develop targeted marketing strategies that resonate with each group's unique characteristics and needs. The analysis provides actionable insights and tailored marketing strategies for each identified segment.

## Dataset 🗂️

The dataset used can be found on Kaggle [here](https://www.kaggle.com/datasets/vishakhdapat/customer-segmentation-clustering).

## Tools Used 🛠️
<p>  
  <img alt="Python" src="https://img.shields.io/badge/python-306998.svg?style=for-the-badge&logo=python&logoColor=white"/>
  <img alt="Pandas" src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img alt="Matplotlib" src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black"/>
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white"/>
  <img alt="Scikit-learn" src="https://img.shields.io/badge/scikit--learn-F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img alt="Seaborn" src="https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=Seaborn&logoColor=white"/>
  <img alt="NumPy" src="https://img.shields.io/badge/NumPy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white"/>
</p>

- **Pandas:** Data manipulation and analysis.
- **Seaborn:** Statistical data visualization.
- **Matplotlib:** Plotting library for Python.
- **Scikit_learn:** Machine learning library for Python.
- **numpy:** Fundamental package for scientific computing with Python.

## Project Workflow 🎯
1. **Data Preprocessing:**
   - Numerical features are scaled using `StandardScaler`.
   - Categorical features are one-hot and label encoded using `OneHotEncoder`, `LabelEncoder`.
   - Impute missing values using `SimpleImputer`.
   - Convert `Dt_Customer` to datetime and calculate `Days_since_joining`.

2. **Clustering:**
   - Determine the optimal number of clusters using the Elbow method.
   - Train the K-means model with the optimal number of clusters.
   - Reduce dimensions using PCA for visualization.
   - Visualize the clusters using scatter plots.

3. **Cluster Analysis:**
   - Analyze the cluster profiles and identify key characteristics.
   - Develop targeted marketing strategies based on cluster insights.

## Findings✨🕵
- **Cluster 0**: Low income, high education, more kids at home, low spending on wines and fruits, low response to campaigns.
- **Cluster 1**: High income, average education, more kids at home, high spending on wines and fruits, high response to campaigns.
- **Cluster 2**: Average income, low education, more teenagers at home, moderate spending on wines, negative spending on fruits, moderate response to campaigns.
- **Cluster 3**: Slightly above average income, slightly below average education, more kids at home, moderate spending on wines, high spending on fruits, slightly lower response to campaigns.

### Implications for Marketing📢📌:
- **Cluster 0**: Target with affordable products, educational content, and family-oriented products and services.
- **Cluster 1**: Target with luxury and premium products, especially wines and gourmet foods. Offer premium family packages.
- **Cluster 2**: Target with moderately priced products. Focus on tech gadgets, educational tools, and entertainment options for teenagers.
- **Cluster 3**: Target with balanced offers combining affordable luxury and practical family products. Promote health-oriented products, particularly fruits.

## 👩‍💻 Author

- GitHub: [@rania3103](https://github.com/rania3103)
- LinkedIn: [LinkedIn](https://linkedin.com/in/rania-abassi-24105a249)

