<h1 align="center">Tejas Pandya</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?lines=NYU+MSFE+(3.9)+%7C+ex-Nomura+Market+Risk;Alpha+research+%E2%80%A2+Derivatives+pricing+%E2%80%A2+Low-latency+C%2B%2B;Seeking+2027+full-time+quant+roles+(NYC);&font=Fira+Code&center=true&width=720&height=45&color=06b6d4&vCenter=true&size=19&pause=1000" alt="headline">
</p>

<p align="center">
  <a href="https://linkedin.com/in/tejaspandya9598"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:tbp8777@nyu.edu"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://leetcode.com/u/6ixE11even/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"></a>
  <a href="https://codeforces.com/profile/6ixE11even"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CFA-Level%20I-1B365D?style=flat-square" alt="CFA L1">
  <img src="https://img.shields.io/badge/Baruch%20MFE-C%2B%2B%20for%20Financial%20Engineering-2E5E4E?style=flat-square" alt="Baruch C++">
  <img src="https://img.shields.io/badge/Bloomberg-Market%20Concepts-000000?style=flat-square" alt="BMC">
  <img src="https://img.shields.io/badge/CFI-FMVA-4B8BBE?style=flat-square" alt="FMVA">
</p>

I build quant research and trading infrastructure. Three years running market-risk
systems at Nomura (VaR, FRTB, multi-asset) taught me how production breaks; the
projects below are me building the research stack on top of that — signals, pricing,
backtests, and the low-latency plumbing underneath. Every repo ships with tests,
CI, and a README that explains the math, not just the code.

---

### 📈 Alpha research & backtesting

| Project | What it does | Stack |
|---|---|---|
| **[equity-xs-alpha](https://github.com/6ixE11even/equity-xs-alpha)** | Cross-sectional signals → rank IC with Newey-West t-stats → cost-aware quintile portfolios → LightGBM combo under purged walk-forward CV. OOS net Sharpe 0.89 vs −0.63 naive baseline | Python · LightGBM |
| **[stat-arb-backtester](https://github.com/6ixE11even/stat-arb-backtester)** | Event-driven pairs backtester on live crypto: Engle-Granger cointegration, z-score signals, transaction costs, no look-ahead | Python |
| **[macro-regime-allocation](https://github.com/6ixE11even/macro-regime-allocation)** | PCA + K-Means regime classifier on 120+ macro indicators feeding mean-variance allocation; 2× equal-weight benchmark OOS | Python |
| **[prediction-markets](https://github.com/6ixE11even/prediction-markets)** | Live Polymarket scanner for cross-outcome arbitrage in multi-outcome (neg-risk) events | Python |

### 🧮 Derivatives pricing & rates

| Project | What it does | Stack |
|---|---|---|
| **[sofr-swap-pnl-attribution](https://github.com/6ixE11even/sofr-swap-pnl-attribution)** | SOFR curve bootstrap, 500+ swap portfolio, daily P&L attribution into carry / roll-down / curve via key-rate durations; par swaps reprice to <1e-9 | Python |
| **[sabr-vol-calibration](https://github.com/6ixE11even/sabr-vol-calibration)** | SABR (Hagan) calibrated to live Deribit BTC smiles; <0.04 vol-pt RMSE | Python |
| **[options-pricing-engine](https://github.com/6ixE11even/options-pricing-engine)** | European/American/barrier options via Black-Scholes, Monte Carlo, Crank-Nicolson FDM; projected SOR for early exercise | C++20 |

### ⚡ Market microstructure & low latency

| Project | What it does | Stack |
|---|---|---|
| **[hft-matching-engine](https://github.com/6ixE11even/hft-matching-engine)** | Deterministic limit-order-book engine, O(1) insert/cancel/execute, zero-allocation memory pool; ~35M msgs/sec synchronous path | C++20 |
| **[lob-market-manipulation-detection](https://github.com/6ixE11even/lob-market-manipulation-detection)** | Spoofing/layering detection over millions of L2 events; 27 microstructure features, IsolationForest/ECOD/autoencoder ensemble | Python |
| **[optimal-execution](https://github.com/6ixE11even/optimal-execution)** | Almgren-Chriss closed-form optimal liquidation + cost/risk efficient frontier, impact params calibrated from Deribit data | Python |

### 🔬 ML foundations & commodities

| Project | What it does | Stack |
|---|---|---|
| **[ml-algorithms-from-scratch](https://github.com/6ixE11even/ml-algorithms-from-scratch)** | GBDT, random forest, SVM (SciPy dual), logistic regression, PCA from first principles, benchmarked vs scikit-learn | NumPy |
| **[commodity_futures_settlement_price_analysis](https://github.com/6ixE11even/commodity_futures_settlement_price_analysis)** | WTI/Henry Hub settlement anomaly detection + term-structure dashboard over 60+ contract months | Python · Streamlit |

---

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/C%2B%2B20-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="sklearn">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white" alt="CMake">
  <img src="https://img.shields.io/badge/Bloomberg-Terminal-000000?style=for-the-badge" alt="Bloomberg">
</p>

<p align="center">
  <i>Risk-desk production rigor + ML research + low-latency C++ — most candidates have one; the combination is the edge.</i>
</p>
