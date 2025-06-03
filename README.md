# Types-of-regression-models-
# 📈 Regression Models Visualization and Plot Saving

This project demonstrates **7 different regression models** using a synthetic dataset and saves their predictions as **high-resolution images** for analysis or printing.

## 🔍 Overview

The following regression models are implemented:

1. **Linear Regression**
2. **Polynomial Regression (degree=3)**
3. **Ridge Regression**
4. **Lasso Regression**
5. **ElasticNet Regression**
6. **Support Vector Regression (SVR)**
7. **Decision Tree Regression**

Each model is trained on the same synthetic dataset (a noisy sine wave) and its predictions are visualized and saved as `.png` images automatically.

---

## 🧪 Dataset

A synthetic 1D dataset is generated using `numpy`:

```python
X = np.sort(5 * np.random.rand(100, 1), axis=0)
y = np.sin(X).ravel() + noise
