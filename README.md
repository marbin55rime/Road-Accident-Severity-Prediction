# Road-Accident-Severity-Prediction
## This project is developed for academic and research purposes.

This repository contains the implementation of the course project developed for the **CSE437(Data Science) -** course at **BRAC University**.


## 📖 Project Overview

Road traffic accidents are one of the leading causes of death and injury worldwide. Predicting accident severity can help emergency services, traffic management authorities, and policymakers improve road safety.

This project implements and compares four machine learning models using a real-world accident dataset(secondary dataset).

- ✅ Random Forest
- ✅ Neural Network (MLP)
- ✅ Logistic Regression
- ✅ Naive Bayes

The complete preprocessing pipeline includes:

- Missing value handling
- Label Encoding
- Feature Scaling
- Model Training
- Performance Evaluation
- Data Visualization

---

## 🎯 Objectives

- Predict road accident severity using machine learning.
- Compare multiple ML algorithms.
- Analyze important accident-related features.
- Evaluate models using standard classification metrics.

---

## 📂 Project Structure

```
Road-Accident-Severity-Prediction/
│
├── Accident_Dataset final.csv        # Dataset
├── Colab Code.py     # Source Code
├── Machine Learning Based Road Accident Severity #Latex code
├── Machine Learning Based Road Accident Severity.pdf # IEEE Conference Format
├── README.md
│
├── Results/
│   ├── accuracy.png
│   ├── confusion_matrix.png
│   ├── precision_recall.png
│   ├── roc_curve.png
│   └── correlation_heatmap.png
```

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📊 Machine Learning Models

- Gaussian Naive Bayes
- Logistic Regression
- Multilayer Perceptron (MLP)
- Random Forest

---

## ⚙ Data Preprocessing

- Missing Value Imputation
- Label Encoding
- StandardScaler Normalization
- Train-Test Split (70%-30%)

---

## 📈 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

## 🏆 Results

The Random Forest classifier achieved the best overall performance among all tested models.

| Model | Accuracy |
|--------|----------|
| Naive Bayes | 11.53% |
| Logistic Regression | 39.97% |
| Neural Network (MLP) | 45.95% |
| **Random Forest** | **78.55%** |

Random Forest also achieved the highest Precision, Recall, F1-score, and ROC-AUC.

---

## 📊 Visualizations

The project generates:

- Correlation Heatmap
- Accuracy Comparison
- Precision vs Recall
- Confusion Matrix
- ROC Curve
- Feature Importance

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Road-Accident-Severity-Prediction.git
```

Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run

```bash
python final_project_group_41_437.py
```

---

## 📁 Dataset

The dataset contains accident-related information including:

- Weather Conditions
- Road Type
- Vehicle Type
- Junction Type
- Environmental Factors
- Traffic Features

Target Variable:

- Accident Severity (Weather_y)

---

## 📌 Future Improvements

- XGBoost
- LightGBM
- Explainable AI (SHAP/LIME)
- Deep Learning Models
- Real-time Accident Prediction
- GIS-based Accident Hotspot Detection

---

## 👨‍💻 Authors

**Sikder Marbin Rime**

Department of Computer Science and Engineering

BRAC University

---

**Deeanat Rahman**

Department of Computer Science and Engineering

BRAC University
