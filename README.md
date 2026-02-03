# 🎒 Vauban 50 (V-50) Backpack Conversion Prediction

[![Spark](https://img.shields.io/badge/Apache_Spark-FFFFFF?style=for-the-badge&logo=apachespark&logoColor=E25A1C)](https://spark.apache.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)
[![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)](https://www.markdownguide.org/)

## 📋 Table of Contents
- [🎯 Project Overview](#-project-overview)
- [📊 Business Context](#-business-context)
- [🎯 Project Objectives](#-project-objectives)
- [🚀 Technologies Used](#-technologies-used)
- [📁 Dataset Structure](#-dataset-structure)
- [🔧 Project Setup](#-project-setup)
- [📈 Methodology](#-methodology)
- [📂 Project Structure](#-project-structure)
- [👥 Team Members](#-team-members)
- [📅 Timeline](#-timeline)
- [📄 Deliverables](#-deliverables)
- [🏆 Evaluation Criteria](#-evaluation-criteria)

## 🎯 Project Overview

This project is part of the **Big Data Analytics course** where we act as business and data science consultants for **Vauban 50 (V-50)**, a premium accessories brand specializing in urban professional backpacks. Our mission is to predict the probability of website visitors placing orders and provide actionable business insights to optimize their marketing strategy.

## 📊 Business Context

**Vauban 50 (V-50)** is a French premium accessories brand founded in 2022 by three former IESEG students. The brand offers four premium backpack models:

| Product | Features | Color |
|---------|----------|-------|
| **CorePack** | Water-resistant, laptop sleeve, main compartment | Slate Grey |
| **TechFortress** | CorePack features + crush-proof padding, USB-C port, anti-theft pocket | Matte Black |
| **AirLite** | Ultra-lightweight nylon, minimal flat lay | Electric Blue |
| **EcoShell** | Foldable, 100% recycled PET material | Earthy Green |

## 🎯 Project Objectives

### Primary Goals:
1. **📊 Prediction Model**: Build a machine learning model to predict whether a website visitor will place an order (binary classification)
2. **🎯 Multi-class Prediction**: Predict which specific product a customer will order (optional bonus)
3. **💡 Business Insights**: Identify key factors influencing purchase decisions
4. **📈 Marketing Analysis**: Evaluate channel profitability and landing page performance

### Key Questions:
- What drives conversion on the V-50 website?
- Which marketing channels are most profitable?
- Which landing page designs perform best?
- How can V-50 improve their conversion rate?

## 🚀 Technologies Used

### **Data Processing & ML:**
![PySpark](https://img.shields.io/badge/PySpark-3.5.0-E25A1C?logo=apachespark&logoColor=white)
![Python](https://img.shields.io/badge/Python_3.9+-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)

### **Machine Learning:**
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikit-learn&logoColor=white)
![MLlib](https://img.shields.io/badge/Spark_MLlib-D22128?logo=apachespark&logoColor=white)

### **Development & Collaboration:**
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?logo=googlecolab&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?logo=markdown&logoColor=white)

### **Visualization:**
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?logo=python&logoColor=white)

## 📁 Dataset Structure

### **Core Datasets:**

| Dataset | Rows (Sample) | Rows (Holdout) | Columns | Description |
|---------|---------------|----------------|---------|-------------|
| **Products** | 4 | - | 3 | Product catalog information |
| **Orders** | 28,991 | - | 8 | Order transactions |
| **Order Items** | 35,626 | - | 7 | Individual items within orders |
| **Website Sessions** | 434,008 | 38,861 | 10 | Website visit sessions |
| **Website Pageviews** | 1,052,523 | 103,278 | 4 | Individual page views |


## 🔧 Project Setup

### **Prerequisites:**
```bash
# Required Software
- Python 3.9+
- Apache Spark 3.5.0
- Google Colab account
- Git

# Python Packages
pyspark==3.5.0
pandas==2.0.3
numpy==1.24.3
matplotlib==3.7.2
seaborn==0.12.2
```

