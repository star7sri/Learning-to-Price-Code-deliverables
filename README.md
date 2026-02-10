# Learning to Price: Code Deliverables

This repository contains the complete **code deliverables and experimental notebooks** corresponding to the paper:

> **Learning to Price: Interpretable Attribute-level Demand Models for Dynamic Markets - accepted as a full paper in AAMAS 2026.**

The goal of this repository is to provide **reproducible experiments, simulation pipelines, and algorithmic implementations** used in the paper, with a focus on **interpretable, attribute-level dynamic pricing under uncertainty**.

---

## 📌 Repository Overview

Dynamic pricing in modern markets involves:
- High-dimensional product attributes  
- Unknown and evolving demand functions  
- Strong substitution and cross-price effects  

This repository demonstrates how **attribute-level demand decomposition** enables:
- Scalability to high-dimensional pricing problems  
- Interpretability of learned demand parameters  
- Improved regret performance compared to black-box methods  

All experiments are implemented as **Jupyter notebooks** for clarity and ease of reproducibility.

---

## 📂 Repository Structure
1. Regret_comp_ADEPT_EE_GDG_v1 - contains the regret comparison of the ADEPT algorithm with the baselines
2. Slopefit_cumregret - illustrates the empirical slope - regret rate calculation
3. HnM_price_decomp_analysis - contains the AFD validation on HnM data
4. CJ_pricedecompose - contains the AFD validation on Complete Journey data

## Key Concepts Implemented:

- Attribute-level price decomposition
- Interpretable demand modeling
- Online learning under bandit feedback
- Stationary and non-stationary demand environments
- Regret minimization
- Cross-price and substitution effects

## Algorithms Covered:

The repository includes implementations and comparisons of:
- Proposed Attribute-level Dynamic Pricing Algorithm
- Explore–Exploit baselines
- Gradient-based pricing methods
- Bandit optimization techniques under:
- Stationary demand
- Demand shocks
- Drifting demand
- Model misspecification

## ⚙️ How to Run
1. Clone the repository
git clone https://github.com/star7sri/Learning-to-Price-Code-deliverables.git
cd Learning-to-Price-Code-deliverables

2. Install dependencies
pip install numpy pandas matplotlib scipy jupyter

3. Launch Jupyter Notebook
jupyter notebook

## 📄 Citation
If you use this code in your research, please cite:
```text
@article{learning_to_price,
  title={Learning to Price: Interpretable Attribute-level Demand Models for Dynamic Markets},
  author={Sethuraman, Srividhya, Lakshminarayanan, Chandrashekar},
  year={2026}
}
```

## 🤝 Contact

For questions, feedback, or collaboration:
Author: Srividhya Sethuraman
GitHub: https://github.com/star7sri


