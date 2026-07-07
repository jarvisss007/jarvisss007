# Anupam Patil

**🌐 Portfolio: [jarvisss007.github.io](https://jarvisss007.github.io)** — papers, code, and an interactive hidden-Markov regime explorer

Quantitative finance researcher — M.S. Finance (UC Riverside, Dec 2024). I build
trading research with an emphasis on **honest evaluation**: walk-forward testing,
realistic transaction costs, and significance testing before believing any backtest.
Two working papers and an open-source toolkit, all reproducible — CI re-verifies
every published number on each commit.

## 📄 Working papers

**[Do Hidden Markov Regimes Add Out-of-Sample Value?](https://github.com/jarvisss007/regime-monte-carlo)**
Regime-switching Monte Carlo vs. fat tails for market risk. Student-t HMM and
GARCH-t estimated from scratch; VaR/ES backtests (Kupiec, Christoffersen,
Berkowitz) over 5,600–8,900 out-of-sample days spanning 2008 and COVID.
Finding: fat tails — not hidden states — drive tail-risk calibration.

**[Do Machine-Learning Filters on Directional-Change Events Survive Out-of-Sample?](https://github.com/jarvisss007/dc-ml-trading)**
A cautionary study across equities and commodities (S&P 500, NASDAQ, WTI crude).
Every number reproduces from public data with two commands. Headline finding: the
popular DC+ML trading edge does **not** survive rigorous out-of-sample testing.

## 🧰 Open-source toolkit

**[backtest-overfitting](https://github.com/jarvisss007/backtest-overfitting)** —
tools for detecting when a backtest is fooling you: Deflated Sharpe Ratio,
Probability of Backtest Overfitting (CSCV), and minimum backtest length.
Case study included: I applied it to my own TradingView strategy and it
correctly convicted the strategy as overfit. Eating my own cooking.

## 🔬 Interests

- Backtest overfitting and multiple-testing discipline
- Regime detection; ML in asset pricing
- Event-based (intrinsic-time) representations of price series
- Market microstructure ([live order-flow dashboard](https://github.com/jarvisss007/crypto-microstructure))

## 📫 Contact

- Academic: apati077@ucr.edu
