# Anupam Patil

**🌐 Portfolio: [jarvisss007.github.io](https://jarvisss007.github.io)** — papers, code, and an interactive hidden-Markov regime explorer

Quantitative finance researcher — M.S. Finance (UC Riverside, Dec 2024). I build
trading research with an emphasis on **honest evaluation**: walk-forward testing,
realistic transaction costs, and significance testing before believing any backtest.
Three working papers and an open-source toolkit, all reproducible — CI re-verifies
every published number on each commit — plus a fleet of LLM-agent systems that run,
score and audit the research desk autonomously
([case study](https://jarvisss007.github.io/qbts-case-study.html)).

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

**[How Many Retail Trading Strategies Survive Honest Evaluation?](https://github.com/jarvisss007/strategy-lab)**
A systematic survey: 8 classic strategy families across full parameter grids on 15
years of data, judged by a pre-registered Deflated-Sharpe + PBO gate. Finding: no
market-neutral family survives; 12 frozen rules continue forward-testing daily in a
public paper-trading arena whose blotter commits to the repo on every run.

## 🧰 Open-source toolkit

**[backtest-overfitting](https://github.com/jarvisss007/backtest-overfitting)** —
tools for detecting when a backtest is fooling you: Deflated Sharpe Ratio,
Probability of Backtest Overfitting (CSCV), and minimum backtest length.
Case study included: I applied it to my own TradingView strategy and it
correctly convicted the strategy as overfit. Eating my own cooking.

## 🚚 Production systems — forward-deployed (private repos)

Since early 2026 I've been the sole technical person inside a Southern California
drayage carrier, building their operating stack end-to-end (private repos):

- **Dispatch automation platform** — 41,000+ lines of Python, 347 automated tests:
  broker-email classification → live-board load matching → human-approved draft
  replies. Human-in-the-loop by design; the code has no auto-send scope.
- **Driver channel & documents** — WhatsApp driver messaging (Playwright), mobile
  proof-of-delivery upload, automatic detention claims, rate-con PDF extraction
  with an LLM fallback for scanned documents.
- **Live operations dashboard** — 30-second GPS fleet map, per-load net-income
  ledger across 7,000+ annual loads, appointment board swept from Gmail, CPA-ready
  P&L reporting.
- **Verification culture, ported from my research** — weekly billing/payroll gates
  and a calibration scoreboard that scores every model prediction against ground
  truth before anything touches money.

Same discipline as the research above, pointed at a real business: automate the
workflow, keep a human on the trigger, and measure every promise the system makes.

## 🔬 Interests

- Backtest overfitting and multiple-testing discipline
- Regime detection; ML in asset pricing
- Event-based (intrinsic-time) representations of price series
- Market microstructure ([live order-flow dashboard](https://github.com/jarvisss007/crypto-microstructure))

## 📫 Contact

- Academic: apati077@ucr.edu
