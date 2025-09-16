# 📊 NFT Market Analysis & Forecasting

A **comprehensive analysis of NFT market trends** with **interactive visualizations** and **time series forecasting** of daily NFT sales. This project leverages **Prophet** and **ARIMA** models to predict future NFT sales and compares their performance using statistical evaluation metrics.

---

## 🚀 Project Highlights

* 🔎 **Exploratory Data Analysis (EDA):** Trends, distributions, and correlation insights into the NFT market.
* 📈 **Visualizations:**

  * Daily & cumulative NFT sales (USD)
  * Primary vs Secondary sales (cumulative)
  * Daily number of transactions
  * Distribution of daily sales & number of sales 
  * Correlation matrix of market metrics
* 🤖 **Forecasting Models:**

  * **Prophet** (seasonality-aware forecasting)
  * **ARIMA** (classic time series approach)
* 📊 **Model Evaluation:**

  * Mean Absolute Error (MAE)
  * Root Mean Squared Error (RMSE)
* 🔮 **Forecast Horizon:**

  * Historical validation on test data
  * 30-day future forecast of NFT sales

---

## 🛠️ Tech Stack

* **Languages & Environment:** Python, Jupyter Notebook
* **Libraries & Tools:**

  * Data Handling: `pandas`, `numpy`
  * Visualization: `matplotlib`, `seaborn`
  * Forecasting: `prophet`, `statsmodels`
  * ML & Evaluation: `scikit-learn`

---

## 📂 Repository Structure

```bash
NFT-Market-Analysis/
│
├── data/                  # Dataset (not uploaded, add CSV here)
├── notebooks/             # Jupyter notebooks with analysis
│   └── NFT_analysis.ipynb # Main analysis notebook
├── README.md              # Project documentation
├── requirements.txt       # Python dependencies
└── LICENSE                # License (MIT recommended)
```

---

## 📊 Results

📌 **Model Performance (on test data):**

| Model   | MAE (↓)       | RMSE (↓)       |
| ------- | ------------- | -------------- |
| Prophet | 82,563,784.10 | 102,851,268.75 |
| ARIMA   | 38,181,526.72 | 64,367,333.41  |

✅ ARIMA outperformed Prophet on this dataset, showing better accuracy for NFT sales forecasting.

📌 **Visual Insights:**

* NFT sales show strong volatility and spikes across the market.
* Secondary sales dominate cumulative volumes compared to primary sales.
* Forecasts suggest **continued market fluctuation** with potential growth trends.

---

## 📦 Installation & Usage

1️⃣ Clone the repository:

```bash
git clone https://github.com/<your-username>/NFT-Market-Analysis.git
cd NFT-Market-Analysis
```

2️⃣ Install dependencies:

```bash
pip install -r requirements.txt
```

3️⃣ Launch Jupyter Notebook:

```bash
jupyter notebook notebooks/NFT_analysis.ipynb
```

---

## 📑 Dataset

The dataset contains **daily NFT sales data** with features including:

* `Date`
* `Sales_USD`
* `Number_of_Sales`
* `Primary_Sales`

> 📌 Dataset not included in the repo. Please place your dataset CSV in the `data/` directory.

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use, modify, and share with attribution.

---

⚡ *This project showcases advanced data analysis, visualization, and forecasting – designed to highlight strong analytical & technical skills in Python for real-world datasets.*

---

## Author
[Ayush Aman](www.linkedin.com/in/ayush-aman-039817161)





