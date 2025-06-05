# 🏠 Big Data Analytics: Airbnb Listings Project

This is our project repository for the **Big Data Analytics** course, where we analyze Airbnb listings using **Databricks Community Edition**. The project involves both **clustering analysis** and **price prediction** using big data tools and machine learning workflows. It includes data preprocessing, feature engineering, model pipelines, and performance evaluation.

---

## 📌 Project Overview

The goal of this project is to explore and model Airbnb listings data to:

- 🧼 Perform data cleaning and exploratory data analysis (EDA)
- 🔍 Identify natural groupings of listings via clustering
- 💰 Predict listing prices using various regression models
- ⚙️ Build reusable and scalable ML pipelines using Spark MLlib

This project demonstrates the use of **Apache Spark** in Databricks for handling and modeling data at scale, with an emphasis on clean, modular design and reproducibility.

---

## 🗂 Repository Structure

📁 Project_Data/
└── airbnb_listings.zip → Compressed CSV file with Airbnb listing data

📓 1_bda_group63_eda&cleaning.ipynb
→ EDA and data cleaning operations

📓 2_bda_group63_pipeline.ipynb
→ Pipeline for data transformation, training, and evaluating predictive models

📓 transformers.ipynb
→ Custom transformer used in the model pipeline

📓 utils.ipynb
→ Utility functions for plotting, missing value checks, etc.

📓 bda_group63_clustering.ipynb
→ Clustering using Spark MLlib (e.g., KMeans)

📄 Guidelines.pdf
→ Project description and requirements

🖼 Workflow_Diagram.png
→ Visual representation of the project workflow

---

## 🚀 Getting Started

1. Clone this repository.
2. Import notebooks into your **Databricks Community Edition** workspace.
3. Upload the `airbnb_listings.zip` file from `Project_Data/` and extract it within a Databricks DBFS folder.
4. Run the notebooks in order:
   - `1_bda_group63_eda&cleaning.ipynb`
   - `bda_group63_clustering.ipynb`
   - `2_bda_group63_pipeline.ipynb`

> 🔧 Make sure your cluster is running and has adequate resources.

---

## 📈 Project Highlights

- Cleaned and analyzed Airbnb listings data.
- Built a robust **pipeline-based price prediction model** using Spark's `Pipeline` and `Estimator` API.
- Explored and visualized **clusters of similar listings** to uncover insights.
- Modular and reusable structure using custom utility notebooks and transformers.

---

## 💡 Explore & Contribute

Feel free to explore the repository, run the notebooks, and use the code for your own experiments.
We welcome feedback, suggestions, and contributions!
