# 🌱 Bayesian Plant Growth Analysis with PyMC

![Trace Plot](notebooks/figures/trace_plot.png)
![Forest Plot](notebooks/figures/forest_plot.png)

## 🌟 Project Overview
This project demonstrates Bayesian modeling of plant growth factors using PyMC. We analyze how sunlight hours, water amount, and soil nitrogen affect plant growth through:

- Synthetic data generation
- Bayesian linear regression
- Posterior predictive checks
- Parameter estimation with uncertainty quantification

## 📊 Key Visualizations

### 1. MCMC Trace Diagnostics
![Trace Plot](notebooks/figures/trace_plot.png)
*Verifies Markov chain convergence - our "hairy caterpillars" show good mixing*

### 2. Parameter Estimates
![Forest Plot](notebooks/figures/forest_plot.png)
*95% credible intervals for our beta coefficients - water amount shows strongest effect*

### 3. Model Validation
![PPC Plot](notebooks/figures/ppc_plot.png)
*Posterior predictive checks show good agreement between model and synthetic data*

### 4. Parameter Relationships
![Pair Plot](notebooks/figures/pair_plot.png)
*Joint distributions reveal no problematic correlations between parameters*

## 🚀 Getting Started

### 1. Setup Environment
```bash
cd c:\repo\pymc_project
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt