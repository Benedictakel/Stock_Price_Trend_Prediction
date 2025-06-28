

# 📈 Stock Price Trend Prediction

Predicting stock price trends (upward or downward movement) using historical stock market data and machine learning models.



## 📑 Table of Contents

* [Introduction](#introduction)
* [Dataset](#dataset)
* [Project Objectives](#project-objectives)
* [Technologies Used](#technologies-used)
* [Installation](#installation)
* [Usage](#usage)
* [Model Building](#model-building)
* [Results](#results)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)



## 📝 Introduction

The **Stock Price Trend Prediction** project leverages machine learning to predict future trends in stock prices (whether the price will go up or down) based on historical market data. Accurate predictions can assist investors and analysts in making informed trading decisions.



## 📊 Dataset

* **Source:**  financial APIs
* **Attributes:**

| Feature        | Description                                              |
| -------------- | -------------------------------------------------------- |
| Date           | Trading date                                             |
| Open           | Opening price                                            |
| High           | Highest price during the day                             |
| Low            | Lowest price during the day                              |
| Close          | Closing price                                            |
| Volume         | Number of shares traded                                  |
| Trend (Target) | Up (1) if next day's price is higher, Down (0) otherwise |

> **Note:** Data was fetched using `yfinance` or CSV downloads from Yahoo Finance for selected stocks.



## 🎯 Project Objectives

✅ Fetch and explore historical stock price data

✅ Perform data preprocessing (handle missing values, generate labels)

✅ Engineer features (moving averages, daily returns, volatility)

✅ Build classification models to predict price trends

✅ Evaluate model performance with accuracy, precision, recall, and F1-score

✅ Visualize trends, features, and prediction results



## 🛠️ Technologies Used

* Python 3.x
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* yfinance
* Jupyter Notebook



## ⚙️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/stock_price_trend_prediction.git
cd stock_price_trend_prediction
```

2. **Create virtual environment (optional but recommended)**

```bash
python -m venv venv
source venv/bin/activate      # On Linux/Mac
venv\Scripts\activate         # On Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```



## ▶️ Usage

1. **Run the Jupyter Notebook**

```bash
jupyter notebook Stock_Price_Trend_Prediction.ipynb
```

2. **Follow the notebook steps to:**

* Fetch and explore data using `yfinance`
* Engineer features such as:

  * 5-day and 10-day moving averages
  * Exponential moving averages
  * Daily returns
  * Volatility measures
* Prepare target labels (1 for upward trend, 0 for downward trend)
* Build and evaluate models for trend prediction
* Visualize predicted vs actual trends



## 🏗️ Model Building

The following classification models were implemented and compared:

| Model                            | Description                                  |
| -------------------------------- | -------------------------------------------- |
| **Logistic Regression**          | Baseline binary classifier                   |
| **Decision Tree**                | Tree-based model for interpretability        |
| **Random Forest**                | Ensemble method for improved accuracy        |
| **Support Vector Machine (SVM)** | Effective for non-linear decision boundaries |
| **K-Nearest Neighbors (KNN)**    | Instance-based learning                      |

**Evaluation Metrics:**

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix



## 📈 Results

* **Best performing model:** *Specify model name here*
* **Accuracy:** *Value here*
* **Precision:** *Value here*
* **Recall:** *Value here*
* **F1-Score:** *Value here*

> The Random Forest Classifier performed best due to its ability to handle feature interactions and reduce overfitting through ensemble learning.



## ⚠️ Disclaimer

This project is for educational purposes only and does not constitute financial advice. Stock market investments are subject to market risks.



## 🤝 Contributing

Contributions are welcome to improve feature engineering, incorporate deep learning models (e.g. LSTM), or deploy the predictor as an interactive web app.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request



## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more details.



## 📬 Contact

**Ugama Benedicta Kelechi**
[LinkedIn](www.linkedin.com/in/ugama-benedicta-kelechi-codergirl-103041300) | [Email](mailto:ugamakelechi501@gmail.com) | [Portfolio Website](#)



### ⭐️ If you find this project useful, please give it a star!

