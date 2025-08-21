# 🎮 CS2 Skin Trading

This project is about **analyzing and simulating trading** in the Counter-Strike 2 skin market.  
The aim is to collect data, study market patterns, and build simple trading strategies.

---

## 📌 Goals
- Collect skin market data (Steam, Buff.163, CSGOFloat)
- Study price trends and liquidity
- Build and test trading strategies
- Create a paper-trading bot (simulate trades without real money)

---

## 📂 Structure
- **data/** → scraped data files  
- **notebooks/** → Jupyter notebooks for experiments  
- **src/** → source code (scraper, trading bot, etc.)  
- **README.md** → project guide  

---

## 🛠️ Tools
- Python 3  
- Libraries: requests, pandas, matplotlib  
- Jupyter Notebook  

---

## 🚀 Roadmap
1. Setup repo ✅  
2. Collect data (Steam Market first)  
3. Analyze prices & trends  
4. Build trading strategies  
5. Simulate trades with a bot  

---
## 🛠️ API Plan (MVP)

### Endpoints
- GET /skins → list all skins with name + price
- GET /skins/{name} → details of one skin

### Data fields
- skin_name
- price
- volume
- market_url