# 🛣️ Road Condition and Surface Type Classification Using Machine Learning

---

## 📖 Project Overview

**Road Condition and Surface Type Classification Using Machine Learning** is designed to automatically classify road conditions and road surface types using accelerometer-derived vibration features and vehicle speed data. The system applies signal preprocessing, feature extraction, and supervised machine learning techniques to analyze driving data and classify road conditions into **Good, Regular, and Bad**, and road surface types into **Asphalt, Cobblestone, and Dirt**. Multiple machine learning models, including **Decision Tree, Random Forest, XGBoost, LightGBM, and CatBoost**, were trained and evaluated to identify the best-performing models. The proposed system supports **road quality assessment**, **predictive road maintenance**, and **intelligent transportation systems** by providing an automated and data-driven approach to road condition and surface type classification.

### 🔹 Project Summary

- 🤖 Machine learning-based road condition classification system
- 📊 Uses real-world driver vibration and vehicle speed data
- 📡 Processes accelerometer vibration signals
- 🛣️ Classifies road conditions (Good, Regular, Bad)
- 🛤️ Predicts road surface types (Asphalt, Cobblestone, Dirt)
- ⚙️ Performs signal filtering and feature extraction
- 🤖 Compares multiple machine learning algorithms
- 🏆 Achieved **88.89%** accuracy for road condition classification
- 🏆 Achieved **85.33%** accuracy for road surface classification
- 🚗 Supports road quality assessment and predictive road maintenance

---



### 📊 Dataset 

| Dataset | Shape |
|----------|--------:|
| Sensor Dataset | **144,036 × 32** |
| Label Dataset | **144,036 × 14** |

### 🛣️ Road Condition Classes

- Bad
- Good
- Regular

### 🛤️ Road Surface Classes

- Asphalt
- Cobblestone
- Dirt

---


# ⚙️ Methodology

### 📌 Data Processing Pipeline

Driver Vibration & Vehicle Speed Data Collection  
→ Data Preprocessing  
→ Accelerometer Signal Filtering (Butterworth High-Pass Filter)  
→ Sliding Window Segmentation  
→ Statistical & Frequency-Domain Feature Extraction  
→ Label Preparation & Encoding  
→ Train-Test Split (80:20)  
→ Machine Learning Model Training (Decision Tree, Random Forest, XGBoost, LightGBM, CatBoost)  
→ Model Evaluation (Accuracy, Precision, Recall, F1-Score & Confusion Matrix)  
→ Best Model Selection  
→ Road Condition & Surface Type Prediction


---




# 🤖 Machine Learning Models

The following supervised machine learning algorithms were implemented and evaluated:

- Decision Tree
- Random Forest
- XGBoost
- LightGBM
- CatBoost

---

# 📈 Model Performance

## 🛣️ Road Condition Classification

| Model | Accuracy |
|--------|----------:|
| Decision Tree | 85.33% |
| Random Forest | 87.11% |
| XGBoost | 88.44% |
| LightGBM | 88.00% |
| **CatBoost** | **88.89%** 🏆 |

---

## 🛤️ Road Surface Classification

| Model | Accuracy |
|--------|----------:|
| Decision Tree | 78.67% |
| Random Forest | 83.11% |
| XGBoost | 84.89% |
| **LightGBM** | **85.33%** 🏆 |
| CatBoost | 84.00% |

---

# 🏆 Final Results

### 🥇 Best Road Condition Model

- Model: **CatBoost**
- Accuracy: **88.89%**

### 🥇 Best Road Surface Model

- Model: **LightGBM**
- Accuracy: **85.33%**


---

---

# 💻 Technology Stack

### 💡 Programming Language

- Python

### 📚 Libraries

- NumPy
- Pandas
- Scikit-learn
- SciPy
- XGBoost
- LightGBM
- CatBoost
- Matplotlib

### 🛠️ Tools

- Google Colab
- Jupyter Notebook
- Git
- GitHub

---

# 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

---

# 🚀 Applications

- Intelligent Transportation Systems
- Road Condition Assessment
- Road Surface Classification
- Predictive Road Maintenance
- Vehicle Safety Analysis
- Infrastructure Monitoring
