# Autonomous Trading using CMM + RL

An AI-driven autonomous trading system that combines Contrastive Multi-Modal (CMM) learning with Reinforcement Learning (RL) to perform dynamic portfolio allocation and optimize trading strategies.

---

## 🚀 Overview

This project integrates market data and financial news using contrastive learning to generate meaningful representations. A PPO-based reinforcement learning agent then utilizes these representations to make intelligent trading decisions and allocate portfolio weights dynamically.

---

## 🧠 Key Features

- Multi-modal learning using market data + financial news  
- Contrastive learning with NT-Xent loss for joint representation  
- Reinforcement learning-based trading strategy (PPO)  
- Real-time data processing using APIs  
- Performance evaluation using financial metrics  

---

## 🛠️ Tech Stack

- Python  
- Temporal CNN  
- Transformers (FinBERT)  
- Reinforcement Learning (PPO)  
- Twelve Data API  
- EODHD API  

---

## ⚙️ Architecture

1. **Data Collection**
   - Market data from APIs (Twelve Data, EODHD)  
   - Financial news for sentiment analysis  

2. **Feature Engineering**
   - Temporal CNN for time-series market data  
   - FinBERT for news embeddings  

3. **Contrastive Learning**
   - NT-Xent loss to align multi-modal features  

4. **Reinforcement Learning Agent**
   - PPO agent for portfolio allocation  
   - Learns optimal trading strategy over time  

---

## 📊 Performance Metrics

- Sharpe Ratio  
- Sortino Ratio  
- Maximum Drawdown  
- Achieved **~16% profit** over 3 months of data  

---

## 🔮 Future Improvements

- Real-time live trading deployment  
- Risk-aware portfolio optimization  
- Enhanced sentiment analysis models  
- Integration with more diverse financial data sources  

---

## 📌 Conclusion

This project demonstrates how combining contrastive learning with reinforcement learning can significantly improve trading strategies by leveraging both numerical and textual financial data.

---

## 👤 Author

Your Name
