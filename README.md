# 🌤️ Weather Prediction

> A machine learning model that forecasts weather conditions using historical meteorological data — applying classification and regression techniques for accurate predictions.

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

---

## 📌 Project Overview

This project builds a weather prediction system using supervised machine learning. By training on historical meteorological data (temperature, humidity, wind speed, pressure, etc.), the model learns to forecast future weather conditions — whether it will rain, the expected temperature, or weather category classification.

---

## ✨ Features

- 🌡️ Weather feature analysis (temperature, humidity, wind, pressure)
- 🧹 Data preprocessing — handling missing values and feature encoding
- 📊 Exploratory Data Analysis (EDA) with visualizations
- 🤖 Multiple ML models compared (Decision Tree, Random Forest, KNN, SVM)
- 🎯 Classification and regression support
- 📈 Model evaluation with accuracy, F1-score, and RMSE
- 📓 Clean, well-documented Jupyter Notebook

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Language | Python 3.x |
| ML Library | Scikit-learn |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Notebook | Jupyter Notebook |

---

## 📁 Project Structure

```
weather_prediction/
├── weather_prediction.ipynb   # Main Jupyter Notebook
├── README.md                  # Project documentation
└── data/                      # Meteorological dataset files
```

---

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.8+
pip
```

### Installation

```bash
# Clone the repository
git clone https://github.com/apoorvai-ai/weather_prediction.git
cd weather_prediction

# Install dependencies
pip install numpy pandas scikit-learn matplotlib seaborn jupyter

# Launch the notebook
jupyter notebook weather_prediction.ipynb
```

---

## 📊 How It Works

1. **Data Loading** — Import historical weather dataset (temperature, humidity, wind speed, etc.)
2. **EDA** — Visualize distributions, correlations, and seasonal trends
3. **Preprocessing** — Handle missing values, encode categoricals, scale features
4. **Model Training** — Train and compare multiple ML classifiers/regressors
5. **Evaluation** — Measure performance using accuracy, F1, RMSE metrics
6. **Prediction** — Forecast weather based on new input features

---

## 🧪 Models Compared

| Model | Task | Notes |
|---|---|---|
| Decision Tree | Classification | Fast, interpretable |
| Random Forest | Classification | High accuracy, ensemble |
| K-Nearest Neighbors | Classification | Simple, effective |
| Linear Regression | Regression | Baseline for temp prediction |
| Support Vector Machine | Classification | Robust on small datasets |

---

## 🎯 Key Learnings

- Handling real-world meteorological datasets
- Feature correlation analysis for weather variables
- Comparing classification and regression approaches
- Model selection and evaluation best practices

---

## 👨‍💻 Author

**Apoorv Sinha**
- GitHub: [@apoorvai-ai](https://github.com/apoorvai-ai)
- Email: apoorvsinha509@gmail.com

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

⭐ If you found this helpful, please consider giving it a star!

</div>
