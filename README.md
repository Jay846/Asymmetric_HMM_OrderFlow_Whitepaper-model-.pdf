# Asymmetric HMM for Order Flow Imbalance

# Overview

This white paper introduces an asymmetric Hidden Markov Model (HMM) framework for detecting latent market regimes using tick-level Order Flow Imbalance (OFI) data.

Unlike traditional HMM applications focused on asset returns, this model incorporates directional asymmetry in transition dynamics and adjusts signal weighting based on local microstructure (spread-driven certainty). It’s designed for high-frequency applications like breakout filtering and adaptive order execution.

---

# Paper

Download PDF:  
[Asymmetric_HMM_OrderFlow_JaySalvi.pdf](./Asymmetric_HMM_OrderFlow_JaySalvi.pdf)

Author: 
Jay Salvi  
jay85salvi@gmail.com  
[LinkedIn](https://www.linkedin.com/in/jay-salvi-0787aa245)

---

# Highlights

- Tick-level regime modeling using OFI
- Asymmetric transition matrix constraints
- Spread-adjusted trade certainty weighting
- Entropy-based confidence scaling for sizing
- Empirical results show:
  - +17% signal precision improvement
  - −9bps VWAP cost
  - ~4.3 min regime duration

---

# Status

Implementation code and data available upon request for academic or collaborative review.

---

# Contact

If you are a researcher, quant, or microstructure enthusiast and want to discuss this model further — feel free to reach out.
