# 🧠 Sex Classification with Neural Networks 🧠

Welcome to this project where we build and improve neural network models to **predict the sex** of individuals based on clinical and demographic data! 🚀

---

## 🎯 Project Overview

This project shows a step-by-step journey of creating smarter models for sex classification using Multi-Layer Perceptrons (MLPs), refining preprocessing and architectures to boost performance! 💪✨

### Baseline Solution

- Simple model: a single-layer perceptron with softmax output.  
- Uses `sklearn` preprocessing (not allowed for this assignment 😅).  
- Results in low accuracy due to:  
  - ❌ No feature normalization  
  - ❌ Too simple architecture (no hidden layers)  
  - ❌ Minimal tuning  

---

## 🚀 Objectives

1. **Preprocessing Improvements**  
   Use only **Pandas** to:  
   - 🔄 Normalize numerical features with z-score  
   - 🎨 One-hot encode categorical variables with `pd.get_dummies`  

2. **Model Architecture Enhancements**  
   Build MLPs with:  
   - 🏗️ At least one hidden layer  
   - ⚡ ReLU activations  
   - 🎯 Goal: improve accuracy and learning  

3. **Iterative Solutions**  
   - Solutions 1A & 1B: different preprocessing, same MLP baseline  
   - Solution 2: refined model with best preprocessing  

4. **Evaluation & Analysis**  
   - 📊 Train & test accuracy  
   - 🔍 Confusion matrix to analyze errors  
   - ⏳ Training runtime & loss curves  
   - 📈 Compare impact of preprocessing & model tweaks  

---

## 📊 Dataset

- Loaded from `cleaned_merged_heart_dataset.csv`  
- Features include:  
  - 🔢 Numerical: age, resting blood pressure, cholesterol, max heart rate, etc.  
  - 🏷️ Categorical: chest pain type, fasting blood sugar, rest ECG, exercise angina, ST slope, thalassemia  
- Target: **sex** (binary classification)  

---

## 🛠️ How to Run

1. **Install dependencies**  
   Make sure you have Python 3.x and the following packages:  
   - `pandas` 🐼  
   - `numpy` 🔢  
   - `torch` (PyTorch) 🔥  
   - `scikit-learn` (only for metrics and splitting) 🎯  

2. **Run the preprocessing and training scripts**  
   Follow the notebook or scripts in the repo to preprocess data, train models, and evaluate results.

---

## 📈 Results & Insights

- Clear improvement from baseline to refined models  
- Importance of proper normalization and encoding  
- Better architecture boosts accuracy and convergence speed  
- Confusion matrices reveal which classes are harder to predict  

---

## 🙌 Contributions & Credits

- Inspired by coursework and practical exercises on neural networks  
- Thanks to open source libraries: PyTorch, Pandas, NumPy, scikit-learn  

---

## 📫 Contact & Support

If you want to discuss or contribute, feel free to open an issue or reach out! ✉️

---

Thank you for checking out this project! 🚀  
Let's keep learning and building smarter AI together! 🤖💡
