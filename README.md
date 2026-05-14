# Stochastic Calculus & Barrier Options: A Black-Scholes Extension

![Format](https://img.shields.io/badge/Format-PDF_Report-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

## Overview

This project builds upon the foundational Black-Scholes model to explore the valuation of complex, path-dependent derivatives, specifically **Barrier Options** (Up-and-Out, Down-and-Out). 

It bridges the gap between pure probability theory and financial engineering, establishing the duality between two quantitative approaches:
1.  **Stochastic Calculus:** Leveraging the Strong Markov Property, Girsanov's Theorem, and the **Reflection Principle** to determine the joint distribution of Brownian motion and its running maximum.
2.  **Partial Differential Equations (PDEs):** Using the Feynman-Kac theorem to derive the pricing equations and specific boundary conditions for knock-out events.

## Key Concepts Explored

* **The Reflection Principle:** Mathematical determination of stopping times and the law of the maximum for standard and drifted Brownian motions.
* **Risk-Neutral Valuation:** Closed-form analytical pricing formulas for Up-and-Out (UAO) and Down-and-Out (DAO) call options.
* **Model Limitations:** Critical analysis of the constant volatility assumption (volatility smile), discrete price jumps, and Delta-hedging challenges near the barrier (Pin Risk).
* **Real Market Application:** Theoretical findings are confronted with real market dynamics using LVMH option data.

## Visualizations

### Asset Dynamics: Breaching the Barrier
<img width="1784" height="884" alt="barrier_option_simulation" src="https://github.com/user-attachments/assets/287adca5-458f-444f-9265-ad7054de0d02" />

## Project Structure

```bash
├── PRI_Barrier_Options_Report.pdf  # Full mathematical and quantitative report (
└── README.md

## 👥 Authors

* **Eliott Oster**
* **Addi Raphaël**
* **Tirard Thomas**

---

*Developed as part of the GMM Department curriculum at INSA Toulouse.*

sachant que je vais également mettre une image en plein milieu et dans le repo juste le pdf du projet
