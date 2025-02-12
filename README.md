# 🚀 Regressify



**Regressify** is an intelligent, automated regression model selection tool that analyzes datasets and suggests the best-performing regression algorithm. Designed for **data analysts, ML engineers, and security enthusiasts**, it provides fast, accurate, and efficient model evaluation.

---

## ✨ Features

✅ **Smart Format Detection**: Supports `.csv`, `.xlsx`, `.json`, and `.parquet` files.\
✅ **Flexible Delimiter Parsing**: Automatically detects separators like `,`, `;`, `|`, etc.\
✅ **Auto Data Cleaning**: Handles missing values efficiently.\
✅ **Feature Engineering**: Converts categorical variables to numerical values.\
✅ **Comprehensive Model Testing**: Evaluates multiple regression models.\
✅ **Performance Insights**: Measures **R² Score, MSE, MAE, and Explained Variance Score**.\
✅ **Automated Best Model Selection**: Recommends the optimal model based on R² Score.

---

## 📦 Installation

Ensure **Python 3.x** is installed, then install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🔥 Quick Start

Run Regressify with a dataset:

```bash
python Regressify.py -d path/to/dataset.csv
```

### Example:

```bash
python Regressify.py -d housing_prices.csv
```

This will:

1. Load & preprocess data.
2. Apply multiple regression models.
3. Evaluate models using key metrics.
4. Suggest the best model.

---

## 📊 Supported Models

Regressify evaluates:

- **Linear Regression** 🔹 **Ridge** 🔹 **Lasso** 🔹 **ElasticNet**
- **Bayesian Ridge** 🔹 **SGD** 🔹 **Huber** 🔹 **Passive Aggressive**
- **Polynomial (Degree 2)** 🔹 **SVR** 🔹 **Decision Tree** 🔹 **Random Forest**
- **Gradient Boosting** 🔹 **AdaBoost** 🔹 **Extra Trees** 🔹 **HistGradientBoosting**
- **KNN** 🔹 **Neural Networks (MLP Regressor)**

---

## 📌 Sample Output

```plaintext
🚀 Best Model: Random Forest Regression
📈 R² Score: 0.9543
📉 MSE: 1.23e+04
📊 MAE: 105.67
📡 Explained Variance Score: 0.9571
```

---

## 🛠️ Contribute

1. **Fork** & **clone** the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make changes & commit:
   ```bash
   git commit -m "Your feature description"
   ```
4. Push & create a PR:
   ```bash
   git push origin feature-branch
   ```

---

## 📜 License

Licensed under the **MIT License**.

---

## 💬 Connect & Support

Found an issue or have an idea? Open an **Issue** or **Pull Request**!

🚀 **Happy Hacking, Security Enthusiasts!** 🔥

