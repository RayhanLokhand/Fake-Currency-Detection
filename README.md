# Fake Currency Detection System

This project builds a machine-learning pipeline to classify whether a banknote is genuine or fake using statistical features.

---

## 📦 Dataset

- Source: [Kaggle - Banknote Authentication UCI](https://www.kaggle.com/datasets/andrewmvd/banknote-authentication-uci)
- Features:
  - Variance of Wavelet Transformed image
  - Skewness of Wavelet Transformed image
  - Curtosis of Wavelet Transformed image
  - Entropy of image
- Target:
  - Class 0 → genuine
  - Class 1 → fake

---

## 🚀 Project Steps

1. Data loading and exploration (EDA)
2. Feature correlation analysis (heatmap)
3. Train/test split and feature scaling
4. Logistic Regression model training
5. Model evaluation: accuracy, precision, recall, F1-score, confusion matrix

---

## 🔍 Results

- Achieved ~98% accuracy on the test set.
- Strong predictive power, especially from variance and skewness features.
- Visualized model performance with a confusion matrix heatmap.

---

## 🛠 Tools & Libraries

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Files Included

- `fakecurrencydetectionsystem_project.ipynb` → Main notebook.
- `data_banknote_authentication.csv` → Dataset.
- `README.md` → Project documentation.

---

## 💻 How to Run

1. Clone this repository.
2. Open the Jupyter notebook.
3. Run cells step by step.
4. Review outputs and visualizations.

---

## 👤 Author

Rayhan Lokhandwala
