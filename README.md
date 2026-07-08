<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=260&section=header&text=Akshay%20Mattoo&fontSize=52&fontColor=E0D6FF&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%7C%20AI%2FML%20Engineer%20%7C%20Quant%20Researcher&descAlignY=58&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=A855F7&center=true&vCenter=true&width=650&lines=Building+full-stack+systems+that+scale;Designing+ML+%26+quant+models+that+perform;Turning+data+into+decisions;Backend+%2B+AI+%2B+Markets" alt="Typing SVG" />

<br/>

![B.Tech ECE](https://img.shields.io/badge/B.Tech-Electronics%20%26%20Communication%20Engineering-6D28D9?style=flat-square)
![University](https://img.shields.io/badge/VIT%20Vellore-CGPA%208.2%2F10-7C3AED?style=flat-square)
![Location](https://img.shields.io/badge/📍-Vellore,%20India-8B5CF6?style=flat-square)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A0A1A?style=for-the-badge&logo=linkedin&logoColor=A855F7)](https://linkedin.com/in/akshay-mattoo-b0355224b)
[![Email](https://img.shields.io/badge/Email-0A0A1A?style=for-the-badge&logo=gmail&logoColor=A855F7)](mailto:akshay516mattoo@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-0A0A1A?style=for-the-badge&logo=github&logoColor=A855F7)](https://github.com/AkMattoo)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=AkMattoo&color=8B5CF6&style=for-the-badge&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/AkMattoo?label=FOLLOWERS&style=for-the-badge&color=6D28D9&labelColor=0A0A1A)
![Stars](https://img.shields.io/github/stars/AkMattoo?label=STARS&style=for-the-badge&color=7C3AED&labelColor=0A0A1A)

</div>

---

## About Me

I'm a third-year Electronics & Communication Engineering student at VIT Vellore who builds across the full stack — from production REST APIs and BI pipelines to deep learning research and quantitative trading systems. My engineering background shows up in how I work: I instrument everything, backtest before I trust a result, and ship with transaction costs, edge cases, and production reliability in mind rather than treating them as afterthoughts.

On the **software engineering** side, I've shipped a client-facing analytics dashboard at HPE consolidating three production data sources, deployed a full-stack ride-sharing platform serving 200+ users with JWT-authenticated multi-role APIs, and built real-time sensor-to-dashboard pipelines spanning Arduino, Rust, and live frontends.

On the **AI/ML** side, I work across the stack from classical ML (XGBoost, Random Forest) to deep learning (CNNs, ResNet, U-Net for medical image segmentation) to applied LLM systems (Anthropic Claude API with schema-validated, injection-safe output). In parallel, I run a self-directed track in **quantitative finance** — options pricing engines, GARCH volatility models, statistical arbitrage, and regime-adaptive trading systems benchmarked with full walk-forward rigor.

I approach every project with a product engineering mindset: define the measurable outcome first, then build the system that gets there.

<div align="center">

**Open To:** Software Engineering Internships/New-Grad Roles · Quantitative Research Roles · Applied AI/ML Engineering · Research Collaborations

</div>

---

## Tech Stack

**Languages**

<img src="https://skillicons.dev/icons?i=python,java,js,rust,c,cpp,r,matlab&theme=dark" />

**Frontend**

<img src="https://skillicons.dev/icons?i=html,css,js&theme=dark" />

![Streamlit](https://img.shields.io/badge/Streamlit-0A0A1A?style=flat-square&logo=streamlit&logoColor=FF4B4B)
![Tableau](https://img.shields.io/badge/Tableau-0A0A1A?style=flat-square&logo=tableau&logoColor=E97627)
![Power BI](https://img.shields.io/badge/Power%20BI-0A0A1A?style=flat-square&logo=powerbi&logoColor=F2C811)
![Plotly](https://img.shields.io/badge/Plotly-0A0A1A?style=flat-square&logo=plotly&logoColor=3F4F75)

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=nodejs,fastapi,postgres,firebase&theme=dark" />

![Pydantic](https://img.shields.io/badge/Pydantic-0A0A1A?style=flat-square&logo=pydantic&logoColor=E92063)

**Cloud, DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=git,github,docker,postman&theme=dark" />

![Oracle Cloud](https://img.shields.io/badge/Oracle%20Cloud%20Infrastructure-0A0A1A?style=flat-square&logo=oracle&logoColor=F80000)

---

## AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|---|---|---|
| **Deep Learning** | Advanced | CNNs, ResNet, U-Net — medical image segmentation (0.85–0.90 Dice on BraTS) |
| **Classical ML** | Proficient | XGBoost, Random Forest, Gradient Boosting, scikit-learn — production-style classification pipelines |
| **Quant / Statistical ML** | Advanced | GMM regime detection, cointegration testing, Fama-MacBeth regressions |
| **Time-Series & Volatility Modeling** | Advanced | GARCH(1,1), GJR-GARCH, EGARCH — VaR backtesting (Kupiec, Christoffersen) |
| **Applied LLM / Agentic Systems** | Proficient | Anthropic Claude API with Pydantic-validated, injection-safe structured output |
| **MLOps & Deployment** | Proficient | Streamlit dashboards, FastAPI services, pytest coverage, model cards |

</div>

---

## Featured Projects

<details>
<summary><b>🧮 Options Pricing Engine</b></summary>
<br/>

Monte Carlo, Black-Scholes, and CRR binomial-tree pricers for European, American, and path-dependent options, with a live implied-volatility surface built on real NSE options-chain data.

| | |
|---|---|
| **Stack** | Python, NumPy, SciPy, NSE India API, Plotly |
| **Scale** | 50,000 simulated paths per pricing run |
| **Performance** | Monte Carlo (antithetic variance reduction) within 0.5% of closed-form value; full Greeks (delta, gamma, vega, theta, rho) across all three pricing methods |
| **Security** | N/A — read-only market data pipeline |
| **Impact** | Live, tradeable NIFTY/BANKNIFTY vol smile and term-structure visualization via Brent's-method inversion of Black-Scholes |
| **Repository** | [github.com/AkMattoo](https://github.com/AkMattoo) |

Built to benchmark numerical pricing methods against closed-form solutions under realistic market conditions, this engine prioritizes correctness (cross-validated Greeks) over raw speed, making it a reliable reference implementation for derivatives pricing logic.

</details>

<details>
<summary><b>📊 Walk-Forward Regime-Adaptive Trading System</b></summary>
<br/>

A GMM-based regime detector on rolling volatility that adapts a trading strategy's behavior across bull, bear, and high-volatility regimes — refit every 63 days over a 504-day walk-forward window.

| | |
|---|---|
| **Stack** | Python, scikit-learn (GMM), yfinance, Streamlit, Plotly |
| **Scale** | 8-year backtest window (2018–2026) on SPY |
| **Performance** | 1.41 vs 0.89 Sharpe ratio; beat buy-and-hold by 2.4 points annualized return; max drawdown cut 75% (-8.3% vs -33.9%) |
| **Security** | Full transaction cost + slippage model to avoid backtest overfitting |
| **Impact** | Production-style live trading tool with a 24-hour inference loop wired to Alpaca/IBKR and a trade-level P&L ledger |
| **Repository** | [github.com/AkMattoo](https://github.com/AkMattoo) |

Designed to answer a practical question — does regime-awareness actually help — with a walk-forward methodology that avoids lookahead bias, backed by a real-time dashboard for regime visualization.

</details>

<details>
<summary><b>🏦 Credit Risk Markov Chain Simulator</b></summary>
<br/>

An 8-state (AAA→D) discrete-time Markov chain for portfolio-level expected credit loss, with AI-generated executive reporting layered on top.

| | |
|---|---|
| **Stack** | Python, NumPy, Pydantic, Anthropic Claude API, FastAPI |
| **Scale** | 100,000-path Monte Carlo engine |
| **Performance** | Cumulative PD, expected time-to-default, and EAD·LGD·PD aggregation calibrated via Laplace-smoothed migration counts |
| **Security** | Injection-safe, Pydantic schema-validated LLM output; full pytest coverage |
| **Impact** | Automated, audit-ready ECL reporting behind a Streamlit dashboard |
| **Repository** | [github.com/AkMattoo](https://github.com/AkMattoo) |

Combines classical credit-risk modeling with an LLM reporting layer that's constrained to validated, structured output — built specifically to avoid the hallucination risk that makes raw LLM output unsuitable for financial reporting.

</details>

<details>
<summary><b>🧠 Brain Tumor Segmentation — Deep Learning Research</b></summary>
<br/>

CNN/ResNet/U-Net architecture research for MRI tumor segmentation on the BraTS benchmark, with a paper in preparation.

| | |
|---|---|
| **Stack** | Python, PyTorch, CNN, ResNet, U-Net |
| **Scale** | BraTS validation dataset, 3 architecture variants |
| **Performance** | 0.85–0.90 Dice coefficient; ResNet encoder improved segmentation by 4 points over the U-Net baseline |
| **Security** | N/A — offline research pipeline |
| **Impact** | Full ownership of preprocessing (MRI normalization, skull-stripping, patch extraction) through architecture tuning |
| **Repository** | [github.com/AkMattoo](https://github.com/AkMattoo) |

Ongoing research at VIT Vellore comparing encoder architectures for medical image segmentation, with rigorous preprocessing to isolate architecture effects from data artifacts.

</details>

<details>
<summary><b>🚕 EasyCab — Full-Stack Ride-Sharing Platform</b></summary>
<br/>

A production ride-sharing platform for VIT Vellore students with multi-role access and real-time GPS tracking.

| | |
|---|---|
| **Stack** | Node.js, JavaScript, REST APIs, Pandas, PostgreSQL |
| **Scale** | 200+ active VIT students in production |
| **Performance** | Multi-role (Student / Parent / Admin) REST API backend with JWT auth, booking management, and real-time GPS endpoints |
| **Security** | JWT-authenticated routes; all endpoints validated via Postman before deployment |
| **Impact** | Booking data analysis (Pandas) identified peak demand windows, directly informing pre-booking UX optimizations |
| **Repository** | [github.com/AkMattoo](https://github.com/AkMattoo) |

A real, in-use system rather than a demo — built to production standards with role-based access control and data-driven UX iteration based on live usage patterns.

</details>

<details>
<summary><b>📈 Volatility Forecasting — GARCH Models</b></summary>
<br/>

Comparative volatility forecasting across GARCH(1,1), GJR-GARCH, and EGARCH on NIFTY 50 and SPY daily returns, with regulator-grade VaR backtesting.

| | |
|---|---|
| **Stack** | Python, arch library, pandas |
| **Scale** | Dual-index (NIFTY 50 + SPY) daily-returns dataset |
| **Performance** | Evaluated via MSE, QLIKE, and Mincer-Zarnowitz R² against realized volatility |
| **Security** | N/A — statistical modeling pipeline |
| **Impact** | 95% VaR forecasts passing Kupiec proportion-of-failures and Christoffersen independence tests |
| **Repository** | [github.com/AkMattoo](https://github.com/AkMattoo) |

Built to identify which GARCH variant best captures volatility clustering in high-volatility regimes — directly applicable to risk-management VaR pipelines.

</details>

<details>
<summary><b>⚙️ Pairs Trading / Statistical Arbitrage</b></summary>
<br/>

A cointegration-screened pairs trading strategy across the full Nifty 50 universe with a realistic, cost-adjusted backtest.

| | |
|---|---|
| **Stack** | Python, statsmodels, pandas, NSE India equities |
| **Scale** | Full Nifty 50 universe screened, 6-year walk-forward window (2019–2025) |
| **Performance** | Pairs validated via Engle-Granger and Johansen cointegration tests at 5% significance |
| **Security** | Full transaction-cost model (0.05%/leg, STT, brokerage) to avoid inflated backtest returns |
| **Impact** | Per-pair Sharpe ratio, max drawdown, and win-rate reporting for bias-free performance estimates |
| **Repository** | [github.com/AkMattoo](https://github.com/AkMattoo) |

Rolling-OLS hedge ratios with disciplined z-score entry/exit/stop-loss rules (|z|>2 entry, |z|<0.5 exit, |z|>3 stop-loss), stress-tested across a multi-year walk-forward window.

</details>

---

## Experience

### Data Analyst Intern — Hewlett Packard Enterprise (HPE)
**May 2026 – Jul 2026**

Delivered a client-facing analytics dashboard for India's Department of Post, consolidating three operational data sources into a single Power BI reporting layer, and owned backend deployment end-to-end.

**Scope of Work**
- Built and deployed an end-to-end analytics dashboard consolidating 3 operational data sources into a single Power BI reporting layer
- Assisted in deploying the backend service layer — configured endpoints, managed environment variables, coordinated staging-to-production handoff
- Tested and validated all API routes using Postman, writing test suites for data ingestion endpoints to catch schema mismatches and null-value edge cases pre-release
- Wrote optimized SQL queries to extract, clean, and aggregate postal operations data; automated KPI calculations that previously required manual reporting cycles

`Python` `Power BI` `SQL` `REST APIs` `Postman` `Backend Deployment`

<br/>

### Software & Data Intern — Enerktrek & Neptune India
**May 2025 – Jul 2025**

Built real-time sensor data pipelines tracking electricity meter KPIs across two different hardware environments.

**Scope of Work**
- Built real-time sensor data pipelines (Arduino → Rust backend → live frontend) across two hardware environments
- Standardized data schemas and calibration configs, reducing hardware setup time and enabling repeatable deployments across meter types

`Arduino` `Rust` `Python` `Embedded Systems`

---

## Achievements

<div align="center">

| Recognition | Details |
|---|---|
| 🏆 1st Place — Festember, NIT Trichy | Dramatics Society, VIT Vellore |
| 🏆 1st Place — BITS Hyderabad | Dramatics Society, VIT Vellore |
| 🥈 2nd Place — Saarang, IIT Madras | Dramatics Society, VIT Vellore |
| 🎯 Smart India Hackathon (SIH) Shortlist | National-level hackathon |
| 📊 1.41 Sharpe Ratio | Walk-Forward Regime-Adaptive Trading System vs. 0.89 buy-and-hold |
| 🧠 0.85–0.90 Dice Coefficient | Brain Tumor Segmentation, BraTS benchmark |

</div>

---

## Certifications

**Oracle**

![OCI GenAI](https://img.shields.io/badge/Oracle%20Cloud%20Infrastructure%202024-GenAI%20Professional-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Oracle Vector Search](https://img.shields.io/badge/Oracle-Vector%20Search%20%26%20AI%20Foundations-F80000?style=for-the-badge&logo=oracle&logoColor=white)

**IBM**

![IBM ML](https://img.shields.io/badge/IBM-Machine%20Learning%20with%20Python-052FAD?style=for-the-badge&logo=ibm&logoColor=white)

---

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=AkMattoo&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A855F7&icon_color=8B5CF6&text_color=C9D1D9" width="49%" />
<img src="https://streak-stats.demolab.com?user=AkMattoo&theme=tokyonight&hide_border=true&background=0D1117&stroke=8B5CF6&ring=A855F7&fire=8B5CF6&currStreakLabel=A855F7" width="49%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AkMattoo&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A855F7&text_color=C9D1D9" width="49%" />

</div>

---

## GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=AkMattoo&theme=algolia&no-frame=true&column=4&margin-w=15&margin-h=15" />

</div>

---

## Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=AkMattoo&theme=react-dark&hide_border=true&bg_color=0D1117&color=A855F7&line=8B5CF6&point=C9D1D9" width="100%" />

</div>

---

## Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/AkMattoo/AkMattoo/output/github-contribution-grid-snake-dark.svg" width="100%" />

</div>

---

## Current Focus

```yaml
current_focus:
  learning:
    - Advanced market microstructure and options market-making
    - Agentic LLM systems and structured-output reliability
  building:
    - Production-grade full-stack applications with real user bases
    - Quant research pipelines with full backtesting rigor
  exploring:
    - Rust for high-performance backend and trading infrastructure
    - MLOps patterns for deploying research models to production
  open_to:
    - Software Engineering Internships / New-Grad Roles
    - Quantitative Research Roles
    - Applied AI/ML Engineering Roles
    - Research Collaborations
```

---

## Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/akshay516mattoo@gmail.com-0A0A1A?style=for-the-badge&logo=gmail&logoColor=A855F7)](mailto:akshay516mattoo@gmail.com)
[![LinkedIn](https://img.shields.io/badge/akshay--mattoo-0A0A1A?style=for-the-badge&logo=linkedin&logoColor=A855F7)](https://linkedin.com/in/akshay-mattoo-b0355224b)
[![GitHub](https://img.shields.io/badge/AkMattoo-0A0A1A?style=for-the-badge&logo=github&logoColor=A855F7)](https://github.com/AkMattoo)

</div>

---

<div align="center">

*"Measure everything, backtest before you believe it, and ship like production is watching."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=150&section=footer" width="100%"/>

</div>
