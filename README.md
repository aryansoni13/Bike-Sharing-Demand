
# 🚲 Bike Sharing Demand Prediction

A machine learning project that forecasts bike rental demand based on historical usage patterns, weather data, and time-related features. This project is inspired by a real-world Kaggle competition and aims to provide insights into user behavior in bike-sharing systems.

![bike-sharing](https://img.shields.io/badge/Python-3.10-blue?style=flat-square) ![ML](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-yellow?style=flat-square) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)

---

## 📂 Project Structure

```
├── bike-sharing-prediction.ipynb   # Main analysis and modeling notebook
├── README.md                       # Project documentation
└── dataset                         # Dataset files go here
```

---

## 📈 Problem Statement

Predict the **number of total bike rentals (casual + registered)** for each hour based on:

- Weather conditions
- Seasonal and time-based trends
- Holidays and working days
- Temperature, humidity, and wind speed

The goal is to **minimize RMSLE (Root Mean Squared Logarithmic Error)** between actual and predicted rental counts.

---

## 🛠️ Technologies Used

- **Python 3.10**
- **Pandas & NumPy** – Data manipulation
- **Matplotlib & Seaborn** – Exploratory Data Analysis
- **Scikit-learn** – Modeling and preprocessing
- **Gradient Boosting Regressor** – Main ML model
- **GridSearchCV** – Hyperparameter tuning

---

## 📊 Key Features

- 📌 Feature engineering on datetime, seasons, holidays
- 📌 Detailed EDA with comparative histograms and distributions
- 📌 Log transformation to stabilize skewed target
- 📌 Hyperparameter tuning using GridSearchCV
- 📌 RMSLE as the scoring metric

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/aryansoni13/Bike-Sharing-Demand.git
   cd Bike-Sharing-Demand
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```bash
   jupyter notebook bike-sharing-prediction.ipynb
   ```

---

## 📌 Results & Performance

- Final model used: **Gradient Boosting Regressor**
- Evaluation metric: **RMSLE**
- The model performed well on test data after careful preprocessing and tuning

---

## 🧠 Future Improvements

- Add neural network models using TensorFlow or PyTorch
- Include feature importance visualization
- Deploy the model using Streamlit or Flask

---

## 🙌 Acknowledgments

- Inspired by the [Kaggle Bike Sharing Demand Challenge](https://www.kaggle.com/competitions/bike-sharing-demand)
- Dataset originally provided by Capital Bikeshare

---

## 📬 Contact

**Aryan Soni**  
🔗 [GitHub](https://github.com/aryansoni13)  
📧 Reach out for collaboration or questions!

---

⭐ If you like this project, don't forget to star the repo!
