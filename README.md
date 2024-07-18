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
   - Categorical features are one-hot and label encoded using `OneHotEncoder`
   - Impute missing values using `SimpleImputer`.
   - Create new features `Total_spent`: sum of  sepnding on various products categories and `Number_of_purchases`: total sum of purchases through web, catalog and store.

2. **Clustering:**
   - Determine the optimal number of clusters using the Elbow method, Silhouette Score, and Davies-Bouldin Index.
   - Train the K-means model with the optimal number of clusters.
   - Choose between PCA or t-SNE based on silhouette score for dimensionality reduction.
   - Visualize clusters using PCA for better understanding.

3. **Cluster Analysis:**
   - Analyze the cluster profiles and identify key characteristics.
   - Develop targeted marketing strategies based on cluster insights.

## Findings✨🕵
- **Cluster 0**: Lower income, more children at home, lower spending, lower campaign response.
- **Cluster 1**: Higher income, fewer children at home, higher spending, higher campaign response.

### Implications for Marketing📢📌:

- **Cluster 0**:
    - offer discounts on essential items.
    - introduce family oriented products that offer better value for money.
    - improve online shopping experince with features like wishlist reminder to convert web visits into purchases.
- **Cluster 1**:
    - promote premium and luxury products.
    - implement a robust loyalty program taht rewards frequent purchases and higher spending.
    - offer fast shipping options and easy returns to enhance their shopping experience.

## 👩‍💻 Author

- GitHub: [@rania3103](https://github.com/rania3103)
- LinkedIn: [LinkedIn](https://linkedin.com/in/rania-abassi-24105a249)

