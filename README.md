# Master-Degree-Projects
# 🛒 Kompy AI  

> AI-powered supermarket optimization system that minimizes cost, time, and congestion.

---

## 📌 Overview  

**Kompy AI** is an Artificial Intelligence system designed to optimize grocery shopping decisions by analyzing:

- 📍 User location  
- 👥 Real-time or predicted store occupancy  
- 💰 Product-level prices  
- ⏱ Travel time  
- 🛒 Personalized shopping list  

The system generates the most efficient purchasing strategy by minimizing:

```
Total Cost + Travel Time + Congestion Exposure
```

---

## 🎯 Problem Statement  

Consumers face several inefficiencies when grocery shopping:

- Price variation between supermarkets  
- Overcrowded stores during peak hours  
- Lack of integrated decision-support tools  
- Suboptimal multi-store shopping decisions  

Most existing tools optimize **only one variable** (price comparison OR navigation OR discounts).  

**Kompy AI integrates price, distance, occupancy, and time into a unified optimization model.**

---

## 🚀 Features  

- 🧠 Multi-objective optimization engine  
- 📊 Supermarket ranking system  
- 🛣 Route optimization  
- 👥 Crowd-aware recommendations  
- 🛒 Single-store or multi-store strategy generation  
- ⚙️ Personalized weighting system  

---

## 🧠 How It Works  

### 1️⃣ Data Collection  

The system gathers:

- Supermarket locations  
- Product-level pricing data  
- Store occupancy data (real-time or historical)  
- Travel distance and time  
- User shopping list  

---

### 2️⃣ Data Normalization  

All variables are normalized to ensure comparability:

- Price score  
- Distance score  
- Occupancy score  
- Time score  

---

### 3️⃣ Optimization Function  

The system computes a weighted score:

```
Score = w1(Price) + w2(Distance) + w3(Occupancy) + w4(Time)
```

Weights can be customized depending on user preferences.

---

### 4️⃣ Strategy Generation  

Kompy AI determines:

- ✅ Best single supermarket  
- ✅ Optimal multi-store combination  
- ✅ Estimated savings (money & time)  

---

## 🏗 System Architecture  

User Input  
↓  
Data Aggregation Layer  
↓  
Feature Engineering  
↓  
Optimization Engine  
↓  
Recommendation Output  

---

## 🛠 Tech Stack  

- Python  
- Pandas / NumPy  
- Scikit-learn  
- Google Maps API  
- Streamlit / Flask / React  

---

## 📈 Expected Impact  

- Reduced grocery expenses  
- Lower time investment  
- Smarter consumer decisions  
- Improved shopping experience  

---

## 🔮 Future Improvements  

- Reinforcement learning for adaptive weighting  
- Real-time re-optimization  
- Carbon footprint optimization  
- Loyalty program integration  

---

## 👤 Author  
Ricardo Garcés Hidalgo
Master’s in Artificial Intelligence  
Kompy AI Project
