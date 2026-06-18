# 🌲 Handwritten Digit Recognition — Random Forest Classifier

A machine learning project that recognizes **handwritten digits (0–9)** using a **Random Forest Classifier** trained on the scikit-learn Digits dataset.

## 📌 What It Does
- Loads the built-in **Digits dataset** (1,797 samples, 64 features, 10 classes)
- Visualizes digit images using Matplotlib
- Splits data: **80% train / 20% test** (1,437 train, 360 test samples)
- Trains a **Random Forest** with `n_estimators=100`
- Achieves **~97.2% accuracy** on test data
- Evaluates performance with a **Confusion Matrix heatmap** using Seaborn

## 📊 Model Performance
| Metric | Score |
|--------|-------|
| Accuracy | **0.9722 (97.22%)** |
| Train size | 1,437 samples |
| Test size | 360 samples |
| Trees | 100 estimators |

## 🔢 Target Classes
Digits **0 through 9** — 10-class multiclass classification

## 🚀 Run It
```bash
pip install pandas matplotlib seaborn scikit-learn
jupyter notebook 10Random_Forest.ipynb
```

## 🛠️ Built With
Python · Pandas · Matplotlib · Seaborn · Scikit-learn · Jupyter Notebook
