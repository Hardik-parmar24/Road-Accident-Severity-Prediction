# 🚗 Road Accident Severity Prediction using Machine Learning

## 📌 Overview

This project focuses on predicting the **severity of road accidents** using Machine Learning techniques on the **US Accidents March 2023** dataset. By analyzing environmental, weather, location, and traffic-related factors, the models can classify accident severity and help identify high-risk conditions.

Road accidents are a major public safety concern worldwide. Accurate severity prediction can support traffic management authorities, emergency response teams, and policymakers in improving road safety and reducing accident-related casualties.

---

## 🚀 Features

- 📊 Large-scale accident data analysis
- 🧹 Data preprocessing and cleaning
- 🔍 Exploratory Data Analysis (EDA)
- ⚙️ Feature engineering and selection
- 🤖 Machine Learning models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - LightGBM
  - XGBoost
- 📈 Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC
- 📉 Confusion Matrix Visualization
- 📊 Feature Importance Analysis

---

## 🛠️ Tech Stack

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- LightGBM
- XGBoost

### Machine Learning Models

- Logistic Regression
- Decision Tree
- Random Forest
- LightGBM
- XGBoost

### Development Platform

- Google Colab

---

## 📂 Project Structure

```text
Road-Accident-Severity-Prediction/
│
├── data/                  # Dataset files
├── notebooks/             # Jupyter notebooks
├── models/                # Saved ML models
├── outputs/               # Graphs & evaluation results
├── src/                   # Training & preprocessing scripts
├── README.md
└── requirements.txt
```

---

## 📊 Dataset

**Dataset:** US Accidents (March 2023)

**Source:** Kaggle – US Accidents Dataset

### Important Features

- Temperature
- Humidity
- Pressure
- Visibility
- Wind Speed
- Weather Condition
- Start Latitude
- Start Longitude
- Time-based Features
- Traffic-related Indicators

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Hardik-parmar24/Road-Accident-Severity-Prediction.git
cd Road-Accident-Severity-Prediction
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Project

```bash
python main.py
```

Or open the notebook in **Jupyter Notebook** or **Google Colab**.

---

## 📈 Models Used

| Model | Description |
|--------|-------------|
| Logistic Regression | Baseline classification model |
| Decision Tree | Best-performing model for severity prediction |
| Random Forest | Ensemble learning model |
| LightGBM | Gradient boosting framework |
| XGBoost | High-performance boosting algorithm |

---

## 📊 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

---

## 📈 Results

- Decision Tree achieved strong performance for multiclass severity prediction.
- LightGBM and XGBoost provided competitive results for binary classification.
- Feature importance analysis identified the most influential factors affecting accident severity.
- Data visualization provided meaningful insights into accident trends and contributing factors.

---

## 📷 Outputs

- 📊 Exploratory Data Analysis (EDA) Charts
- 📉 Confusion Matrix
- 📈 ROC Curve
- 🌳 Feature Importance Graphs
- 📋 Model Performance Comparison

---

## 🔮 Future Improvements

- 🌐 Real-time accident severity prediction
- 📍 Integration with live traffic and weather APIs
- 📱 Web or mobile dashboard for visualization
- 🧠 Deep Learning models for improved accuracy
- ☁️ Cloud deployment using AWS or GCP

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push to your branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

## 👨‍💻 Author

**Hardik Parmar**

🎓 B.Tech Computer Engineering

🔗 GitHub: https://github.com/Hardik-parmar24

---

## ⭐ Support

If you found this project helpful:

⭐ Star this repository

🍴 Fork it

📢 Share it with others
