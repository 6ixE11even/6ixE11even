<h1 align="center">Tejas Pandya</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?lines=NYU+MSFE+(3.9)+%7C+ex-Nomura+Market+Risk;Front-office+quant+research+%2B+low-latency+C%2B%2B;Alpha+research+%E2%80%A2+Derivatives+pricing+%E2%80%A2+Risk&font=Fira+Code&center=true&width=620&height=45&color=06b6d4&vCenter=true&size=21&pause=1000" alt="headline">
</p>

<p align="center">
  <a href="https://linkedin.com/in/tejaspandya9598"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://leetcode.com/u/6ixE11even/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"></a>
  <a href="https://codeforces.com/profile/6ixE11even"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces"></a>
  <a href="mailto:tbp8777@nyu.edu"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://komarev.com/ghpvc/?username=6ixE11even&style=for-the-badge&color=06b6d4&label=PROFILE+VIEWS" alt="views">
</p>

I build quant research and trading infrastructure. Three years running market-risk
systems at Nomura (VaR, FRTB, multi-asset) taught me how production breaks; the
projects below are me building the research stack on top of that — signals,
pricing, backtests, and the low-latency plumbing underneath.

`CFA Level I` · `C++ for Financial Engineering (Baruch MFE)` · `Bloomberg Market Concepts` · `CFI FMVA`

---

### 📈 Alpha research & backtesting

| Project | What it does | Stack |
|---|---|---|
| [equity-xs-alpha](https://github.com/6ixE11even/equity-xs-alpha) | Cross-sectional signals → rank IC w/ Newey-West t-stats → cost-aware quintile portfolios → LightGBM combo under purged walk-forward CV. OOS net Sharpe 0.89 vs −0.63 naive baseline | Python, LightGBM |
| [stat-arb-backtester](https://github.com/6ixE11even/stat-arb-backtester) | Event-driven pairs backtester on live crypto: Engle-Granger cointegration, z-score signals, transaction costs, no look-ahead | Python |
| [macro-regime-allocation](https://github.com/6ixE11even/macro-regime-allocation) | PCA + K-Means regime classifier on 120+ macro indicators feeding mean-variance allocation; 2x equal-weight benchmark OOS | Python |
| [prediction-markets](https://github.com/6ixE11even/prediction-markets) | Live Polymarket scanner for cross-outcome arbitrage in multi-outcome (neg-risk) events | Python |

### 🧮 Derivatives pricing & rates

| Project | What it does | Stack |
|---|---|---|
| [sofr-swap-pnl-attribution](https://github.com/6ixE11even/sofr-swap-pnl-attribution) | SOFR curve bootstrap, 500+ swap portfolio, daily P&L attribution into carry / roll-down / curve via key-rate durations; par swaps reprice to <1e-9 | Python |
| [sabr-vol-calibration](https://github.com/6ixE11even/sabr-vol-calibration) | SABR (Hagan) calibrated to live Deribit BTC smiles; <0.04 vol-pt RMSE | Python |
| [options-pricing-engine](https://github.com/6ixE11even/options-pricing-engine) | European/American/barrier options via Black-Scholes, Monte Carlo, Crank-Nicolson FDM; projected SOR for early exercise | C++20 |

### ⚡ Market microstructure & low latency

| Project | What it does | Stack |
|---|---|---|
| [hft-matching-engine](https://github.com/6ixE11even/hft-matching-engine) | Deterministic limit-order-book engine, O(1) insert/cancel/execute, zero-allocation memory pool; ~35M msgs/sec synchronous path | C++20 |
| [lob-market-manipulation-detection](https://github.com/6ixE11even/lob-market-manipulation-detection) | Spoofing/layering detection over millions of L2 events; 27 microstructure features, IsolationForest/ECOD/autoencoder ensemble | Python |
| [optimal-execution](https://github.com/6ixE11even/optimal-execution) | Almgren-Chriss closed-form optimal liquidation + cost/risk frontier, impact params calibrated from Deribit data | Python |

### 🔬 ML foundations & commodities

| Project | What it does | Stack |
|---|---|---|
| [ml-algorithms-from-scratch](https://github.com/6ixE11even/ml-algorithms-from-scratch) | GBDT, random forest, SVM (SciPy dual), logistic regression, PCA from first principles, benchmarked vs scikit-learn | NumPy |
| [commodity_futures_settlement_price_analysis](https://github.com/6ixE11even/commodity_futures_settlement_price_analysis) | WTI/Henry Hub settlement anomaly detection + term-structure dashboard over 60+ contract months | Python, Streamlit |

---

### 🧰 Toolbox

`Python` `C++20` `SQL` &nbsp;|&nbsp; `pandas` `NumPy` `SciPy` `statsmodels` `scikit-learn` `LightGBM` `XGBoost` `PyTorch` `QuantLib` &nbsp;|&nbsp; `Bloomberg Terminal` `Git` `CMake` `pytest` `Linux`

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=6ixE11even&show_icons=true&hide_border=true&theme=tokyonight&count_private=true" alt="stats" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=6ixE11even&layout=compact&hide_border=true&theme=tokyonight&langs_count=8" alt="langs" height="165">
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=6ixE11even&hide_border=true&theme=tokyonight" alt="streak" height="165">
</p>

<p align="center">
  <img src="https://leetcard.jacoblin.cool/6ixE11even?theme=dark&font=Fira%20Code&ext=contest" alt="leetcode" height="200">
</p>
