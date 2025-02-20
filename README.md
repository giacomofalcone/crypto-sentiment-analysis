# 📊 Crypto Sentiment Analysis & Market Prediction

Analyzing social media sentiment to predict cryptocurrency crashes. This project examines Reddit discussions, Google Trends, and machine learning models to identify early warning signs of market downturns.

**My first Data Science project, focusing on sentiment analysis and market prediction.** It contains some errors and imperfections.

## 📌 Project Overview
Cryptocurrencies are highly volatile assets, with prices often influenced by social media sentiment. This project investigates whether analyzing Reddit discussions and Google search trends can help anticipate major cryptocurrency crashes, using **FTX** and **Terra** as case studies.

## 📁 Dataset
- **Reddit (CryptoCurrency subreddit)**: Extracted posts and comments using Pushshift.
- **Google Trends**: Search volume trends for FTX and Terra-related keywords.
- **Cryptocurrency Prices**: Collected from Binance to correlate with sentiment analysis.

## 🛠 Technologies Used
- **Python**
- **Pandas, Matplotlib, Seaborn** (Data preprocessing & visualization)
- **VADER Sentiment Analysis** (For sentiment scoring)
- **Scikit-Learn (Random Forest Regression)** (For price prediction)

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/giacomofalcone/crypto-sentiment-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd crypto-sentiment-analysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter notebooks:
   ```bash
   jupyter notebook
   ```

## 📊 Key Findings
- **Increased negative sentiment correlates with market crashes.**
- **Reddit discussions peak before major crashes**, indicating potential early warning signals.
- **Google Trends spikes align with market instability periods.**
- **Machine learning predictions** (Random Forest Regression) achieved:
  - R² ≈ **0.89** on internal tests
  - Moderate accuracy on unseen data (indicating potential for improvement)

## 📂 Repository Structure
```
/notebooks
    - sentiment_analysis.ipynb
    - market_prediction.ipynb
/data
    - reddit_data.csv
    - google_trends.csv
    - crypto_prices.csv
README.md
requirements.txt
```

## 🔍 Future Work
- Improve machine learning models for better generalization.
- Test on a broader range of cryptocurrencies.
- Explore deep learning approaches for sentiment analysis.

---

💡 *If you find this project useful, feel free to star the repository and contribute!* 🌟

