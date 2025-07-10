# 📊 Task - Business Data Agent with LangGraph

This project is a simple AI agent built using **LangGraph**.  
It takes in daily business data (revenue, cost, number of customers), performs analysis, and produces actionable recommendations for business decisions.

---

## 🔧 Features

- ✅ Calculates daily **profit**
- 📈 Computes **CAC** (Customer Acquisition Cost) and detects significant changes (>20%)
- 🚨 Triggers **alerts** based on CAC fluctuations
- 💡 Generates **recommendations**:
  - Reduce costs if profit is negative
  - Review marketing campaigns if CAC increased significantly
  - Consider increasing ad budget if sales are growing
