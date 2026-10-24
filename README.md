<h1 align="center">Anupam Patil</h1>

<p align="center">
  <b>AI engineer &middot; quantitative researcher</b><br>
  I build LLM-agent systems and research pipelines with the checking built in:<br>
  the model proposes, a deterministic layer decides, and every claim is scored against a baseline before anyone acts on it.
</p>

<p align="center">
  <a href="https://jarvisss007.github.io"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-jarvisss007.github.io-1f6feb?style=flat-square&logo=githubpages&logoColor=white"></a>
  <a href="https://linkedin.com/in/anupam-p-patil"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-anupam--p--patil-0a66c2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:apati077@ucr.edu"><img alt="Email" src="https://img.shields.io/badge/Email-apati077%40ucr.edu-444c56?style=flat-square"></a>
</p>

<p align="center">
  Master of Finance, UC Riverside &middot; B.E. Medical Electronics, BMS College of Engineering
</p>

---

## What I work on

- **Agent governance.** Guardrails that bound what an LLM agent may execute, reviewer agents whose only job is to break the first agent's result, and append-only ledgers that make every trial count.
- **Production automation in a messy domain.** The sole engineer inside a freight carrier, running its dispatch, documents and operations on software I wrote.
- **Honest quantitative research.** Walk-forward tests, real costs, Deflated Sharpe, pre-registration. Null results get published like positive ones.

## AI agents with guardrails

| Project | What it shows |
|---|---|
| **[signal-audit](https://github.com/jarvisss007/signal-audit)** | A trading indicator tested by AI agents under rules they could not bend. A reviewer agent killed a false positive with a placebo test before the one-shot holdout was scored, and the study ends in an honest null. Ships a reusable scorer, placebo gate, freeze check and hash-chained trial ledger, plus an MCP server that lets any AI agent run the audit as tools while refusing every shortcut in code. |
| **[agent-verification-lab](https://github.com/jarvisss007/agent-verification-lab)** | Four runtime primitives that put a deterministic guardrail around an LLM's decisions: a state guard, an idempotent executor, a default-deny policy gate, and a hash-chained event log with crash replay. 18 tests, CI on Python 3.11 to 3.13. |
| **[Case study: One Wrong Price](https://jarvisss007.github.io/qbts-case-study.html)** | A stale price feed slipped one wrong fill past about 50 green automated checks. The diagnosis, the correction (including the mistake I made making it), and the input check the system was missing. |

## Research: working papers, reproducible from public data

| Paper | Finding |
|---|---|
| **[Do Hidden Markov Regimes Add Out-of-Sample Value?](https://github.com/jarvisss007/regime-monte-carlo)** | Fat tails, not hidden states, drive tail-risk calibration. Student-t HMM, GARCH-t and MS-GARCH estimated from scratch; VaR/ES backtests over 5,600 to 8,900 out-of-sample days spanning 2008 and COVID. |
| **[Do ML Filters on Directional-Change Events Survive Out-of-Sample?](https://github.com/jarvisss007/dc-ml-trading)** | No. A published edge fails walk-forward testing with costs and block-bootstrap inference on the S&P 500, NASDAQ and WTI crude. Every number reproduces with two commands. |
| **[How Many Retail Trading Strategies Survive Honest Evaluation?](https://github.com/jarvisss007/strategy-lab)** | Eight strategy families across full parameter grids on 15 years of data, judged by a pre-registered Deflated Sharpe and PBO gate. No market-neutral family survives. |

CI re-runs the tests behind the first two papers on every commit, so a published number that drifts fails the build.

## Open-source toolkit

**[backtest-overfitting](https://github.com/jarvisss007/backtest-overfitting)**: tools for detecting when a backtest is fooling you. Deflated Sharpe Ratio, Probability of Backtest Overfitting (CSCV) and minimum backtest length, with case studies where I turned it on my own strategies. It convicted one of them as overfit.

## Live apps: public data, no API keys

| App | What it does |
|---|---|
| **[Crypto order-flow lab](https://jarvisss007.github.io/crypto-microstructure/)** &middot; [code](https://github.com/jarvisss007/crypto-microstructure) | Coinbase order-flow dashboard with a self-learning 15-minute forecaster that scores itself against a baseline. |
| **[Insider Radar](https://jarvisss007.github.io/insider-radar/)** &middot; [code](https://github.com/jarvisss007/insider-radar) | Live SEC Form 4 open-market purchase feed with buy-cluster detection. |
| **[Live events map](https://jarvisss007.github.io/live-events-tracker/)** &middot; [code](https://github.com/jarvisss007/live-events-tracker) | Earthquakes (USGS) and the ISS on a live map, with a self-learning seismic module. |
| **[zero-dte-lab](https://github.com/jarvisss007/zero-dte-lab)** | SPY same-day options: a live chain recorder and an implied-versus-realised move study. A research lab, not a strategy. |

## Production work (private code)

Since early 2026 I have been the sole technical person inside a Southern California drayage carrier, building its operating stack end to end:

- **Dispatch automation platform.** 47,000+ lines of Python across 226 modules, 72 test suites in CI. Broker emails are classified, matched to loads on the live dispatch board, and answered with drafts a human approves. The code has no auto-send scope.
- **Driver channel and documents.** WhatsApp driver messaging, mobile proof-of-delivery upload, automatic detention claims, and rate-confirmation extraction with an LLM fallback for scanned PDFs.
- **Backhaul optimizer.** Live GPS positions, broker load offers and Google Routes mileage combined to recommend the return load that minimises empty miles for each truck.
- **Operations dashboard.** A fleet map on 30-second GPS updates, per-load net income across 7,000+ annual loads, and CPA-ready P&L, behind weekly billing and payroll verification gates.

## Also built

- **[janani-english](https://github.com/jarvisss007/janani-english)**: an offline English-learning app I built for my mother, from Kannada to confident English. No account, no API. [Open it](https://jarvisss007.github.io/janani-english/).
- **[panchatantra-storybook](https://github.com/jarvisss007/panchatantra-storybook)**: an illustrated, offline course in the Panchatantra: five books, 48 tales, all art in inline SVG. [Open it](https://jarvisss007.github.io/panchatantra-storybook/).

<details>
<summary><b>Earlier coursework</b></summary>
<br>

- **[Investment-and-portfolio-project](https://github.com/jarvisss007/Investment-and-portfolio-project)**: a winning StockTrak portfolio, followed by the CAPM post-mortem that showed it was leverage (beta 7.5), not skill.
- **[Stock-analysis](https://github.com/jarvisss007/Stock-analysis)** and **[Option-analysis](https://github.com/jarvisss007/Option-analysis)**: early Python experiments in feature engineering, reinforcement learning and options Greeks.

</details>

## Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=claude&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-111111?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
