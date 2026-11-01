# 🛒 E-Commerce Customer Segmentation Using Machine Learning

## 📌 Project Overview

This project focuses on segmenting e-commerce customers based on their purchasing behaviour using **Unsupervised Machine Learning** techniques.

The project uses RFM (Recency, Frequency, Monetary) analysis to understand customer behaviour and applies K-Means and DBSCAN clustering algorithms to identify different customer segments.

PCA and t-SNE are used for dimensionality reduction and visualization, while marketing personas are created to help businesses develop targeted marketing strategies.

## 🎯 Objectives

- Analyze customer purchasing behaviour using RFM analysis.
- Perform data cleaning and preprocessing.
- Apply feature scaling and log transformation.
- Implement K-Means clustering.
- Implement DBSCAN clustering.
- Determine optimal clusters using the Elbow Method and Silhouette Score.
- Apply PCA for dimensionality reduction.
- Visualize customer segments using t-SNE.
- Generate actionable customer marketing personas.

## 📂 Dataset

**Dataset:** Online Retail Dataset

**Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail)

The dataset contains online retail transaction information.

### Important Features

| Feature | Description |
|---|---|
| InvoiceNo | Transaction invoice number |
| StockCode | Product identification code |
| Description | Product description |
| Quantity | Number of products purchased |
| InvoiceDate | Date of transaction |
| UnitPrice | Price per unit |
| CustomerID | Unique customer identifier |
| Country | Customer's country |

A smaller customer-based subset of the original dataset is used for this project.

## 📊 RFM Analysis

RFM stands for:

- **Recency:** How recently a customer made a purchase.
- **Frequency:** How frequently a customer purchases products.
- **Monetary:** How much money a customer spends.

These three metrics help identify valuable customers and understand purchasing patterns.

## 🧠 Machine Learning Algorithms

### 1. K-Means Clustering
Used to divide customers into a predefined number of clusters based on purchasing behaviour.

### 2. DBSCAN
A density-based clustering algorithm used to identify customer groups and detect unusual data points or noise.

### 3. PCA (Principal Component Analysis)
Reduces the dimensionality of the dataset while retaining as much variance as possible.

### 4. t-SNE
Used to visualize customer clusters in a two-dimensional space.

## ⚙️ Project Workflow

1. Dataset Loading
2. Data Exploration
3. Data Cleaning
4. RFM Feature Engineering
5. Log Transformation
6. Feature Scaling using StandardScaler
7. Optimal K Selection using Elbow Method
8. K-Means Clustering
9. DBSCAN Clustering
10. PCA Dimensionality Reduction
11. t-SNE Visualization
12. Customer Persona Generation
13. Marketing Strategy Recommendations

## 👥 Customer Marketing Personas

The project identifies customer segments based on their RFM characteristics.

| Customer Segment | Marketing Strategy |
|---|---|
| VIP Customers | Exclusive rewards and loyalty benefits |
| At-Risk Loyal Customers | Personalized comeback offers |
| New / Occasional Customers | Welcome offers and recommendations |
| Low-Engagement Customers | Targeted promotions and reminders |

*Personas are assigned using cluster-level RFM statistics and business rules.*

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📁 Project Structure

```text
E-Commerce-Customer-Segmentation/
│
├── Online_Retail_under_20MB.csv
│
├── customer_segmentation.ipynb
│
├── customer_segments.csv
│
├── marketing_personas.csv
│
├── README.md
│
└── visualizations/
    ├── elbow_method.png
    ├── rfm_distribution.png
    ├── kmeans_pca.png
    ├── kmeans_tsne.png
    └── dbscan_tsne.png
```

## 🚀 Installation and Execution

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

### 3. Run the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Open `customer_segmentation.ipynb` and execute the cells.

## 📈 Expected Results

- Customer segmentation using K-Means and DBSCAN.
- Elbow Method visualization.
- Silhouette Score evaluation.
- PCA-based cluster visualization.
- t-SNE-based customer segment visualization.
- Customer marketing personas.
- Exported customer segmentation and marketing persona CSV files.

## 💡 Business Applications

- Identify high-value customers.
- Improve customer retention.
- Develop personalized marketing campaigns.
- Identify inactive customers.
- Improve customer engagement.
- Support data-driven marketing decisions.

## 🔮 Future Improvements

- Experiment with additional clustering algorithms.
- Optimize DBSCAN parameters.
- Develop an interactive Streamlit dashboard.
- Implement automated customer recommendations.
- Integrate real-time customer transaction data.

## 👨‍💻 Author

**Shubham**

Machine Learning | Python | Data Science

---

⭐ If you find this project useful, consider giving the repository a star.
