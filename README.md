# Ecommerce STP Analysis Exercise

## Project Overview

This project addresses a common challenge in e-commerce: all customers currently receive the same promotions and communications, resulting in suboptimal marketing outcomes. To enhance campaign effectiveness and customer retention, the company aims to segment its customer base into groups with similar purchasing behaviors using advanced, data-driven clustering techniques.

### Business Case & Objectives

- **Goal:**
  Optimize marketing and retention strategies by identifying distinct customer segments based on their purchasing behavior, and deliver personalized marketing actions to each segment.

- **Dataset:**
  The analysis uses the "Online Retail" dataset, which contains transaction data from an online store, including invoice numbers, product details, quantities, prices, customer IDs, and countries of residence.

- **Key Steps:**
  1. **Data Preparation:**
     - Load and explore the dataset.
     - Handle missing values and outliers.
     - Engineer features and apply necessary data transformations (e.g., normalization, PCA).
  2. **Clustering & Model Creation:**
     - Compare and apply clustering algorithms (e.g., K-Means, DBSCAN, Hierarchical).
     - Determine the optimal number of clusters using methods such as the elbow method or silhouette score.
  3. **Interpretation & Implementation:**
     - Analyze the characteristics and business value of each customer segment.
     - Propose personalized marketing strategies (e.g., targeted promotions, product recommendations, loyalty programs) for each segment.
     - Use clustering results to support further predictive analytics and association rule mining for actionable recommendations.

- **Business Impact:**
  By segmenting customers and tailoring marketing strategies, the company aims to improve profitability, increase customer satisfaction, and make more informed, data-driven business decisions.

## Contents
- **RUN_FIRST_data_cleaning.ipynb**: Jupyter notebook for initial data cleaning.
- **RUN_SECOND_AI2_model.ipynb**: Jupyter notebook for model building and analysis.
- **AI2_Assignment_2_Darren2.pdf**: Assignment report in PDF format.
- **Others/Online Retail.xlsx**: Raw dataset.
- **Others/df_clean.csv**: Cleaned dataset ready for analysis.
- **requirements.txt**: Python dependencies for running the notebooks.
- **.gitignore**: Git ignore file for unnecessary or large files.
- **outputs/**: Folder containing supporting outputs, intermediate results, and additional explanation files (see below).

### outputs/ (Supporting Explanation Files and Objects)
The following files are included in the `outputs/` folder to provide further context, outputs, or intermediate results from the analysis:
- **BusinessCase - Unsupervised Clustering.pdf**: Business case explaining the rationale and approach for unsupervised clustering in this project.
- **cluster_association_rules.pkl**: Pickle file containing cluster association rules.
- **customer_segments.csv**: CSV file with customer segmentation results.
- **df_clean.csv, df_clean.parquet**: Cleaned datasets in CSV and Parquet formats.
- **online_retail.csv**: Additional CSV version of the raw dataset.
- **product_categories.csv**: CSV file with product category information.
- **rules_cluster_0.pkl, rules_cluster_1.pkl, rules_cluster_2.pkl, rules_cluster_3.pkl, rules_cluster_4.pkl**: Pickle files with association rules for each cluster.

---

For detailed answers to the business case questions, methodology, and results, please refer to the full assignment report: **AI2_Assignment_2_Darren2.pdf**.
