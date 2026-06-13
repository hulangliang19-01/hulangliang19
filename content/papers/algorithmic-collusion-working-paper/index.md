---
title: "Information Obfuscation and Algorithmic Collusion: Theory, Simulation, and Dual Empirical Evidence" #
authors:
  - Liang Hulang # 代表作者 Liang[cite: 1]
date: "2026-03-01" #[cite: 1]
doi: ""

# 3 代表 Working Paper / Preprint
publication_types: ["3"]
publication: "Working Paper"
publication_short: "WP"

abstract: "This paper investigates how changes in the informational environment, specifically observation noise induced by platform mechanisms or infrastructure constraints, affect the stability of algorithmic tacit collusion. By constructing a continuous-time stochastic differential game me and solving the associated Riccati equations, we analyze how obfuscation impacts the Bayesian learning capabilities of autonomous pricing algorithms. Our analytical model and multi-agent reinforcement learning (MARL) simulations characterize a non-monotonic relationship: while moderate demand smoothing can deter unilateral deviations, extreme observation noise forces an exponential decay in the optimal learning rate, triggering a structural collapse into competitive pricing. Welfare analysis further demonstrates that this platform-induced collusion generates a dual deadweight loss, comprising both allocative inefficiency and technological waste. To empirically validate this mechanism, we employ a dual-identification strategy. First, to test the pro-collusive left-tail effect, we utilize a Regression Discontinuity in Time (RDiT) design on algorithmic lifecycle pricing. demonstrating that the deterministic withdrawal of platform traffic subsidies abruptly restores cross-price elasticity and triggers a Nash reversion. Second, to validate the right-tail breakdown under extreme noise, we exploit an exogenous API latency shock in the cryptocurrency market. By contrasting the variance expansion of Bayesian algorithms in a Limit Order Book (LOB) against the structural stability of a deterministic Automated Market Maker (AMM), we provide microstructural evidence consistent with our theoretical prediction: severe information obfuscation blinds algorithmic monitoring, causing an immediate adverse selection defense and a subsequent liquidity withdrawal." #[cite: 1]

tags:
  - Algorithmic Collusion #[cite: 1]
  - Information Obfuscation #[cite: 1]
  - High-Frequency Data #[cite: 1]
  - Stochastic Games #[cite: 1]
  - Multi-Agent Reinforcement Learning #[cite: 1]

url_pdf: "/index.pdf"
---