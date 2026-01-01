# Bank Customer Segmentation Dataset

## Overview
This dataset is designed to support research and experimentation in **customer segmentation and personalized recommendation systems** within the retail banking domain.  
It provides structured customer-level data combining **demographic information, financial attributes, transaction records, and product interaction signals**.

The dataset is suitable for both **unsupervised learning** (e.g., clustering) and **collaborative filtering–based recommendation systems**, and has been prepared as part of an academic research study.

---

## Dataset Structure
The dataset is provided in CSV format and each row represents a customer interaction with a banking product.

---

## Feature Description

### 1. Customer Profile Features
These features describe the general characteristics of customers:
- Gender
- Monthly income
- Credit score category
- Debt-to-income ratio
- Repayment status

---

### 2. Transactional Features
These features capture customer banking activities:
- Transaction type
- Loan type
- Year and month of transaction
- Financial product category

---

### 3. Interaction Features
These features represent **implicit feedback** and customer engagement:
- Product view count
- Click interactions
- Purchase indicators

Interaction features can be weighted to reflect different engagement levels and are suitable for recommendation modeling.

---

## Data Preprocessing
The dataset has undergone the following preprocessing steps:
- Initial statistical inspection and validation
- Detection and handling of outliers using boxplot-based methods
- Exploratory Data Analysis (EDA) for numerical and categorical variables
- Correlation analysis among financial attributes
- Transformation of skewed numerical features to improve model performance

No personally identifiable information (PII) is included in this dataset.

---


## Potential Use Cases
- Personalized banking service recommendation
- Customer behavior analysis
- Marketing strategy optimization
- Customer relationship management (CRM)
- Academic research and benchmarking of machine learning algorithms

---

## License
This dataset is released under the **CC BY 4.0 License** and can be used for research, educational, and experimental purposes with proper attribution.

---

## Citation
If you use this dataset in academic work, please cite it as:

> Bank Customer Segmentation Dataset, Kaggle, 2025.

---

## Notes
- The dataset is suitable for machine learning, data mining, and analytics tasks.
- The structure allows easy extension for advanced modeling and deep learning pipelines.
- Feedback and contributions are welcome via Kaggle discussions.
