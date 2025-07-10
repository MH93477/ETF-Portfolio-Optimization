#  Sector-Based ETF Portfolio Optimization

###  Role: Registered Investment Advisor (RIA)  
**Client Profile:** Conservative | Diversification-Focused  
**Objective:** Design an optimal ETF portfolio with strong risk-adjusted returns and sector diversification.

---

##  Tools & Libraries
- `pandas`, `numpy`, `matplotlib`, `scipy`, `statsmodels`
- `yfinance` (for historical financial data)

---

##  Analysis Period
**Jan 1, 2015 – Oct 31, 2024**  
Monthly data from 5 sector ETFs + SPY benchmark + NDQ benchmark.

---

## 🚀 Portfolio Strategies Modeled

| Portfolio Type        | Description                               |
|-----------------------|-------------------------------------------|
| Port 1                |      Equal-weighted Portfolio             |
| Port 1a               |      Max Return Portfolio                 |
| Port 1b               |      Min Risk Portfolio                   |
| Port 2                |  Equal-weighted Portfolio (SPY included)  |
| Port 2a               |      Max Return (SPY included)            |
| Port 2b               |      Min Risk (SPY included)              |
| Port 2c ✅            |     Max Sharpe Ratio (SPY included) ✅   |

---

## ✅ Final Recommendation

### 📈 **Portfolio 2c (Max Sharpe Ratio w/ SPY)**
- **Sharpe Ratio:** 0.951  
- **Annualized Return:** 16.01%  
- **Downside Risk:** 0.0919  
- **Treynor Ratio:** 0.0995  

 This portfolio balances growth and protection — ideal for a conservative investor who values diversification, consistent returns, and minimized downside exposure.

---

##  Key Insights

- Including SPY improved overall diversification and boosted portfolio efficiency.
- Max Sharpe portfolios consistently outperformed others on a risk-adjusted basis.
- Minimum risk portfolios sacrificed too much return for the client profile.
- Negative Information Ratios across all portfolios highlight potential for further alpha-seeking strategies or smarter benchmarks.

---


