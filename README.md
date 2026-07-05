# KO JONG HAN

### Quant Research · Trading Infrastructure · Financial Data Engineering

CSE @ Korea University

I build quantitative research pipelines and trading-system infrastructure around crypto and ETF markets.

My current focus is on turning market ideas into reproducible research artifacts, separating statistical evidence from execution quality, and building safer operations layers for automated trading systems.

[![GitHub](https://img.shields.io/badge/GitHub-rhwhdgks-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rhwhdgks)

---

## Research & Engineering Projects

### Trading Infrastructure

<table>
  <tr>
    <td width="40" height="40">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="24" height="24" alt="Python">
    </td>
    <td>
      <strong><a href="https://github.com/rhwhdgks/funding-arb-engine">funding-arb-engine</a> — Funding-rate arbitrage execution engine</strong>
    </td>
  </tr>
</table>

- Built a hedged perpetual-futures trading infrastructure around exchange adapters, order execution, hedge completion, shutdown safety, and operational reporting.
- Designed runtime controls for manual order, cancel, hedge, flatten, pause, and resume flows.
- Separated strategy profitability from execution/OMS/ops-layer reliability.

### Quant Research

<table>
  <tr>
    <td width="40" height="40">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="24" height="24" alt="Python">
    </td>
    <td>
      <strong><a href="https://github.com/rhwhdgks/etf-image-alpha-ode">etf-image-alpha-ode</a> — Image-based ETF alpha signals for ODE portfolio optimization</strong>
    </td>
  </tr>
</table>

- Generated cross-sectional ETF alpha candidates from chart-image representations.
- Packaged `mu(t)`, `Sigma(t)`, and realized returns for downstream ODE optimizer experiments.
- Documented leakage checks, bootstrap validation, covariance shrinkage, and negative-result notes.

<table>
  <tr>
    <td width="40" height="40">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="24" height="24" alt="Python">
    </td>
    <td>
      <strong><a href="https://github.com/rhwhdgks/crypto-herding-research">crypto-herding-research</a> — Crypto herding and market microstructure research</strong>
    </td>
  </tr>
</table>

- Tested CSAD/SCSAD herding hypotheses, tick-level event studies, lead-lag robustness, and sentiment extensions.
- Applied multiple-testing control, stability splits, permutation tests, and CCF checks.
- Reported limitations explicitly, including weak broad-herding evidence and lag-0 co-movement.

<table>
  <tr>
    <td width="40" height="40">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" width="24" height="24" alt="Jupyter">
    </td>
    <td>
      <strong><a href="https://github.com/rhwhdgks/Covariance-Trading-in-crypto-market">Covariance-Trading-in-crypto-market</a> — Crypto cointegration and statistical arbitrage sprint</strong>
    </td>
  </tr>
</table>

- Built a sprint research workflow for pair screening, Johansen testing, z-score backtesting, and slippage sensitivity.
- Organized presentation artifacts, result tables, figures, and reproducibility notes.

---

## Education

<table>
  <tr>
    <td width="40" height="40">
      <img src="https://img.shields.io/badge/KU-CSE-A41D33?style=flat-square" alt="Korea University CSE">
    </td>
    <td>
      <strong>Korea University — Computer Science and Engineering</strong>
    </td>
  </tr>
</table>

---

## Activities

<table>
  <tr>
    <td width="40" height="40">
      <img src="https://img.shields.io/badge/Find--A-Quant-111827?style=flat-square" alt="Find-A">
    </td>
    <td>
      <strong>Find-A — Member (2026.01 ~ Present)</strong>
    </td>
  </tr>
</table>

- Working on quant research and trading-infrastructure projects.
- Built research artifacts around crypto covariance/statistical arbitrage and funding-rate arbitrage infrastructure.

---

## Tech Skills

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=JavaScript&logoColor=black)

**Quant / ML**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=NumPy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6.svg?style=for-the-badge&logo=scipy&logoColor=white)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

**Backend / Data / Infra**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688.svg?style=for-the-badge&logo=FastAPI&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545.svg?style=for-the-badge&logo=mariadb&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624.svg?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032.svg?style=for-the-badge&logo=git&logoColor=white)

---

## Current Direction

- Research pipelines that are reproducible and auditable
- Trading systems with explicit risk gates, control paths, and shutdown behavior
- Statistical validation that separates signal evidence from execution quality
- Clear documentation of assumptions, limitations, and negative results
