# iris-ml-horizon-task1


# 🌸 Iris Flower Classification System

A comprehensive Machine Learning project demonstrating data exploration, visualization, model training, and evaluation on the classic Iris dataset using Python and Scikit-Learn.

---

## 📊 Overview & Pipeline

This repository implements a supervised Machine Learning pipeline to classify Iris flowers into three target species:
1. **Setosa** (Class 0)
2. **Versicolor** (Class 1)
3. **Virginica** (Class 2)

### Workflow Steps:
1. **Data Ingestion & Summary:** Inspected data structure using Pandas. Verified $150$ total entries with zero null values.
2. **Exploratory Data Analysis (EDA):** Plotted pairplots using Seaborn to visualize relationships between Sepal Length/Width and Petal Length/Width.
3. **Model Training:** Split data into training and test sets and trained a classifier model.
4. **Evaluation:** Generated accuracy metrics and a full classification matrix.

---

## 📈 Model Performance & Results

- **Accuracy Score:** `1.0` ($100\%$)
- **Classification Report:**

| Class | Precision | Recall | F1-Score | Support |
| :--- | :---: | :---: | :---: | :---: |
| **0 (Setosa)** | 1.00 | 1.00 | 1.00 | 10 |
| **1 (Versicolor)** | 1.00 | 1.00 | 1.00 | 9 |
| **2 (Virginica)** | 1.00 | 1.00 | 1.00 | 11 |
| **Overall Accuracy** | | | **1.00** | **30** |

---

## 🛠️ Requirements & Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/mhm5430/iris-flower-classification.git](https://github.com/mhm5430/iris-flower-classification.git)
   cd iris-flower-classification
