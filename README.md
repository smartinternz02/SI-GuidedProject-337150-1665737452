# 👥 Customer Segmentation using IBM Watson Machine Learning

<p align="center">
  <b>A Machine Learning System to Segment Customers for Business Decisions</b><br>
  Built with Python • ML Algorithms • Flask Web App • IBM Watson Deployment
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Machine_Learning-ML-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Flask_Web_App-black?style=for-the-badge">
  <img src="https://img.shields.io/badge/IBM_Watson-Deployment-lightgrey?style=for-the-badge">
</p>

---

## 📌 Project Overview

Customer Segmentation using IBM Watson Machine Learning is a data science project designed to help businesses identify different customer groups based on purchasing behavior and demographic profiles. By segmenting customers, companies can optimize marketing strategies, increase retention, and improve revenue.

This project explores unsupervised and supervised machine learning methods and integrates the best model into a Flask web application and IBM Watson deployment. ([GitHub][1])

---

## 🎯 Objectives

* Understand customer behavior and segment groups
* Perform data preprocessing and visualization
* Apply clustering and classification algorithms
* Select the best performing model
* Deploy model using IBM Watson Machine Learning
* Build a user interface with Flask

---

## 🧠 Business Understanding

In a competitive marketplace, businesses strive to identify their most valuable customers to optimize marketing spend and tailor strategies.

This project aims to:

* Analyze customer data
* Segment customers into distinct clusters
* Improve targeting and decision-making

Machine learning enables data-driven segmentation that can help businesses maximize profits and customer engagement. ([GitHub][1])

---

## 📊 Data Understanding

This project uses a customer dataset containing attributes such as:

* Demographic information
* Purchase history
* Spending habits

The dataset is explored to find patterns and relationships before building machine learning models.

Clustering (k-means, hierarchical) and classification algorithms (Random Forest, KNN, XGBoost) are used to segment and categorize customers. ([GitHub][1])

---

## 📸 Screenshots

*(Add screenshots into a folder called `screenshots` and link them below)*

### 📊 Data Visualization

```markdown
![Data Visuals](screenshots/data_visualization.png)
```

### 📦 Segmentation Results

```markdown
![Clusters](screenshots/clusters.png)
```

### 🧠 Model Performance

```markdown
![Model Metrics](screenshots/model_metrics.png)
```

### 🌐 Web App Interface

```markdown
![Flask App](screenshots/flask_app.png)
```

---

## 🛠️ Tech Stack

| Component        | Technology                                                                   |
| ---------------- | ---------------------------------------------------------------------------- |
| Language         | Python                                                                       |
| Libraries        | NumPy, Pandas, scikit-learn, Matplotlib, Seaborn                             |
| Algorithms       | k-means, Hierarchical Clustering, Decision Tree, Random Forest, KNN, XGBoost |
| Model Deployment | IBM Watson Machine Learning                                                  |
| Web App          | Flask                                                                        |
| Visualization    | Matplotlib & Seaborn                                                         |

---

## ⚙️ Setup & Installation

### 1. Clone the Repository

```bash
git clone https://github.com/smartinternz02/SI-GuidedProject-337150-1665737452.git
cd SI-GuidedProject-337150-1665737452
```

### 2. Create and Activate Virtual Environment

```bash
python -m venv venv
```

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Notebooks / Scripts

Open Jupyter Notebook files for EDA, model building, and visualization.

### 5. Run Flask App

```bash
python app.py
```

---

## 🧠 Methodology

### 🔹 Data Preprocessing

* Handle missing values
* Normalize/scale features
* Encode categorical variables

### 🔹 Unsupervised Learning

* Hierarchical Clustering
* K-means Clustering

### 🔹 Supervised Learning

* Decision Tree
* Random Forest
* K-Nearest Neighbors (KNN)
* XGBoost

Evaluate performance using suitable metrics and select the best model.

---

## 📌 Deployment

The best performing model is saved using pickle and deployed to **IBM Watson Machine Learning**.

The web app integrates the model to make predictions from user input. ([GitHub][1])

---

## 📍 Status

🟡 In Progress / Guided Project
✔ Model training completed
✔ Flask integration done
🔜 Improve UI and update web deployment

---

## 🙌 Credits

This project was completed as a part of the **SmartInternz Guided Project Program**.
