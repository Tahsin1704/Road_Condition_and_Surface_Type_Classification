# 🛣️ Road Condition and Surface Type Classification Using Machine Learning

---

## 📖 Project Overview

**Road Condition and Surface Type Classification Using Machine Learning** is a machine learning project developed to automatically identify road conditions and road surface types using accelerometer-derived vibration features and vehicle speed data. The system analyzes accelerometer signals collected from moving vehicles, applies signal preprocessing and feature engineering techniques, and trains multiple machine learning models to classify road conditions and surface types with high accuracy.

The project is designed to support intelligent transportation systems, road quality assessment, predictive road maintenance, and smart city applications by providing an automated and data-driven approach to classifying road conditions and road surface types.

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
| Extracted ML Dataset | **1,125 × 20** |

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

# ⚙️ Methodology

### 📌 Data Processing Pipeline

📂 Data Collection (Accelerometer Vibration & Vehicle Speed Data)  
⬇️  
📥 Dataset Loading  
⬇️  
🧹 Data Preprocessing  
⬇️  
⚙️ Butterworth High-Pass Signal Filtering  
⬇️  
🪟 Sliding Window Segmentation  
⬇️  
📊 Feature Extraction  
⬇️  
🏷️ Label Encoding  
⬇️  
✂️ Train-Test Split (80:20)  
⬇️  
🤖 Machine Learning Model Training  
⬇️  
📈 Model Evaluation  
⬇️  
🛣️ Road Condition & Surface Type Classification

---



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

# ✨ Key Features

- Automatic road condition classification
- Automatic road surface type classification
- Vehicle sensor signal preprocessing
- Butterworth high-pass signal filtering
- Statistical feature extraction
- FFT-based feature extraction
- Multiple machine learning model comparison
- Performance evaluation using classification metrics
- Predicts road condition and surface type from sensor data

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
