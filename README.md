# QuantX 🚀

QuantX is a **quantitative trading platform** developed at the **DJS Synapse HackNiche 2.0 Hackathon**, designed to **democratize sophisticated investment strategies**.  
Inspired by platforms like Smallcase, QuantX allows users to invest small amounts (e.g., ₹10,000) into **diversified, pre-built strategies** that maximize returns while managing risks.

---

## 📌 Features

- **📊 Strategy-based Investments** – Multiple trading strategies tailored for different risk appetites.  
- **📰 Sentiment Analysis (NLP)** – News-driven market sentiment analysis with NewsAPI.  
- **📈 Technical Stock Screener** – Identify bullish setups using RSI, EMA, VWAP, and ORB.  
- **⚡ Live Trading Execution** – Integrated with AngelOne’s SmartAPI for seamless order placement.  
- **⏳ Backtesting Engine** – Evaluate strategies with historical data from Yahoo Finance.  
- **🔄 Risk Management** – Stop-loss & profit target mechanisms embedded in all strategies.  

---

## 🛠️ Tech Stack

- **Programming:** Python (Pandas, NumPy, Matplotlib, Scikit-learn, TA-Lib)  
- **APIs Integrated:**  
  - [AngelOne SmartAPI](https://smartapi.angelbroking.com/) (trade execution)  
  - [Yahoo Finance](https://pypi.org/project/yfinance/) (historical data)  
  - [NewsAPI](https://newsapi.org/) (sentiment analysis)  
- **Environment:** Jupyter Notebook  

---

## 📌 Implemented Strategies

### 🔹 Momentum Trading
- **Indicators:** RSI & EMA  
- **Buy Signals:** RSI > 30/65, EMA(10) > EMA(20)  
- **Sell Signals:** RSI < 30/70 or EMA reversal  
- **Result:** Consistent cumulative returns with quick profits.  

---

### 🔹 Intraday Gap Strategy
- Targets **NIFTY 50 stocks** with price gaps ≥ 1.5% at open.  
- Uses **volume confirmation** + 5% profit target.  
- **Return:** 7.75% in 4 months.  

---

### 🔹 VWAP Trading Strategy
- Bullish setup if price > VWAP for 3 consecutive candles.  
- **Profit target:** 1% | **Stop-loss:** 0.5%  
- **Return:** 16.17% in 1 year.  

---

### 🔹 Bid-Ask Ratio Strategy
- Detects **buy/sell pressure** using order book volumes.  
- Bullish if ratio > 8 | Bearish if ratio < 0.125.  

---

### 🔹 Live ORB (Open Range Breakout)
- Monitors first **5-min candle** for price & volume breakouts.  
- Automates **stop-loss & profit targets** for disciplined trading.  

---

## 📊 Results & Insights

- **Momentum Strategy:** High accuracy in short-term trades.  
- **Intraday Gap Strategy:** Delivered **7.75% cumulative return in 4 months**.  
- **VWAP Strategy:** Achieved **16.17% annual return** with strict risk controls.  
- **Bid-Ask Ratio Strategy:** Effective in identifying market pressure.  
- **ORB Strategy:** Automated stop-loss & profit targets ensured disciplined trading.  

✅ These results prove that **quantitative methods + real-time data** can empower both beginners and seasoned traders with smarter investment decisions.  

---

## 📚 Learning Outcomes

- Bridged **academic theory** with **real-world trading**.  
- Built robust **backtesting pipelines** for strategy validation.  
- Hands-on experience with **API integration** & troubleshooting live market feeds.  
- Understood **market psychology** and adaptive trading mechanisms.  
- Enhanced collaboration skills while working in a **multidisciplinary team**.  

---

## 🙌 Acknowledgements

- Developed during **DJS Synapse HackNiche 2.0 Hackathon**.  
- Inspired by **Smallcase** and modern algorithmic trading platforms.  
- Special thanks to **AngelOne**, **Yahoo Finance**, and **NewsAPI** for providing APIs.  

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/QuantX.git
cd QuantX
```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the Notebook
```bash
jupyter notebook AngelOne.ipynb
```
### 📂 Repository Structure
```bash
QuantX/
│── AngelOne.ipynb        # Main Jupyter Notebook
│── requirements.txt       # Dependencies
│── README.md              # Project Documentation
│── data/                  # Historical data & backtesting files
│── strategies/            # Strategy implementations
```
