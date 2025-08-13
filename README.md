# 🛒 Online Retail Data Analysis & Customer Segmentation using RFM

## 📍 Project Overview

This project explores customer purchasing behavior using the UCI Online Retail dataset. The goal is to extract insights and segment customers using RFM (Recency, Frequency, Monetary) modeling combined with clustering algorithms, to support data-driven business decisions and personalized marketing.

## 🗂️ Dataset Source

- **Dataset**: Online Retail
- **Source**: UCI Machine Learning Repository (https://archive.ics.uci.edu/dataset/352/online+retail)
- **Timeframe**: December 2010 – December 2011
- **Size**: ~541,909 transactions | 8 columns

## 🎯 Problem Statement

How can an online retailer identify and segment its customers to improve retention, increase revenue, and personalize outreach strategies?

## 🧹 Data Cleaning

- Removed rows with missing `CustomerID`
- Removed cancelled transactions (InvoiceNo starting with 'C')
- Filtered out invalid quantities and prices (negative or zero values)
- Handled duplicates and formatted `InvoiceDate` for time-based analysis

## 📊 Feature Engineering

- Created `TotalAmount` = `Quantity × UnitPrice`
- Computed RFM metrics:
  - **Recency**: Days since customer's last purchase
  - **Frequency**: Number of transactions per customer
  - **Monetary**: Total spending per customer

## 🧠 Modeling Approach

- **Normalization**: Used MinMaxScaler for RFM features
- **Clustering**: Applied K-Means algorithm to segment customers
- **Evaluation**:
  - Elbow method for optimal K
  - Silhouette score for validation
- **Interpretation**: Labeled clusters based on purchasing patterns

## 📈 Insights & Findings

- Identified 4 main customer segments:
  1. 💎 High-value loyal customers
  2. 🔁 Frequent but moderate spenders
  3. 🌱 Occasional shoppers
  4. ⚠️ At-risk customers (inactive)

- Top 20% customers contribute to 60%+ of revenue
- Clear segmentation enables focused marketing and retention strategies

## 💼 Business Recommendations

- Launch loyalty campaigns for VIPs
- Win back at-risk customers through offers
- Provide seasonal discounts to frequent shoppers
- Promote exclusive bundles to high-spending segments

## 🛠️ Tools & Technologies

- Python: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- Jupyter Notebook
- Power BI (for optional dashboard visualization)
- Git & GitHub for version control

## 📌 Future Work

- Extend to time-based cohort analysis
- Integrate advanced models: DBSCAN, GMM, or Hierarchical Clustering
- Develop live dashboard using Power BI or Streamlit
- Include Online Retail II dataset for multi-year comparison

## 📚 References

- UCI Machine Learning Repository: Online Retail Dataset
- Research papers on RFM modeling and customer lifetime value
- scikit-learn documentation for clustering algorithms

---

## 🙋‍♂️ About Me

**👨‍💼 Dhruv Nirwan**  
Data Analyst | Power BI | SQL | Excel | Python | Snowflake | Cloud (AWS, Azure, GCP)  | Google Collab | Prompt Engineering

🔗 [LinkedIn](https://www.linkedin.com/in/dhruv-nirwan)  
📧 dhruvnirwan836@gmail.com  
📂 [GitHub: dhruvnirwan](https://github.com/dhruvnirwan)

