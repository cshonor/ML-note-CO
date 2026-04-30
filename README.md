# My Quant & AI Learning Repo

This repo contains the math and CS fundamentals for three main tracks:
1. Stock Multi-Factor Quant
2. AI Agent Development
3. Option & Futures Quant (Stochastic Finance)

---

## Repo Structure
| Folder | Description |
| :--- | :--- |
| `Alg` | Linear Algebra, Numerical Methods, Basic Algorithms |
| `CO` | Convex Optimization |
| `ML` | Machine Learning / Deep Learning (in separate repo) |
| `ODE` | Ordinary Differential Equations |
| `PSTAT` | Probability & Mathematical Statistics (Mao Shisong) |
| `RFA` | Real Analysis & Functional Analysis |
| `TS` | Time Series Analysis |

---

## Track 1: Stock Multi-Factor Quant
**Core**: Statistics + Linear Models + Convex Optimization + Time Series

1. `PSTAT`: Complete Chapters 3-6 (Multivariate Distributions, LLN, Parameter Estimation, Hypothesis Testing)
2. `Alg`: Matrix Operations, PCA, Linear/Ridge Regression
3. `CO`: Lasso for Factor Selection, Quadratic Programming for Portfolio Optimization
4. `TS`: Factor Stability, Decay Analysis, Time-Series Properties of Returns

---

## Track 2: AI Agent Development
**Core**: Linear Algebra + Convex Optimization + LLM + Algorithms

1. `Alg`: Vector Representations, Similarity, Graph Search/Planning
2. `CO`: Optimization Basics (Loss Functions, Regularization, Optimizers)
3. `ML`: Transformer Basics, Prompt Engineering, RAG
4. Implement Tool Calling, Memory Modules, Task Decomposition
5. `RFA` (optional): Functional-analysis perspective on function approximation

---

## Track 3: Option & Futures Quant (Stochastic Finance)
**Core**: Measure Theory + Probability + ODE + Convex Optimization

1. `RFA`: Real Analysis (Measure, Measurable Functions, Lebesgue Integral)
2. `PSTAT`: Probability Foundations + Advanced Measure-Theoretic Probability
3. `ODE`: ODE Basics for SDE/PDE Numerical Methods
4. `CO`: Model Calibration, Volatility Surface Fitting
5. Stochastic Finance (Shiryaev): Martingale Pricing, Risk-Neutral Measure

---

## Suggested Order by Goal
- Multi-factor quant: `PSTAT -> Alg -> CO -> TS`
- AI agent development: `Alg -> CO -> ML -> RFA(optional)`
- Derivatives quant: `RFA -> PSTAT -> ODE -> CO`
