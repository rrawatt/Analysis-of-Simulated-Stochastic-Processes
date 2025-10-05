# Stochastic Process Simulator

This repository provides a suite of Python simulations designed to visually demonstrate the behavior of fundamental stochastic processes. Its primary goal is to bridge the gap between abstract probability theory and tangible, intuitive results, serving as a computational companion to the theoretical report, "A Rigorous Analysis of Simulated Stochastic Processes."

## Simulated Processes

The codebase includes simulations for the following twelve processes:

### 🎲 Martingales (Fair Games)

* **Gambler's Ruin:** A simple symmetric random walk modeling a gambler's fortune.
* **De Moivre's Martingale:** The compensated process $S_n^2 - n$ for a random walk $S_n$.
* **Bernoulli Exponential Martingale:** A family of martingales constructed from the moment-generating function of Bernoulli trials.
* **Pólya's Urn:** Simulates the evolution of the proportion of colored balls in an urn with reinforcement.
* **Critical Branching Process:** Models population size where the expected number of offspring is one.
* **Likelihood Ratio Martingale:** Simulates the evolution of the likelihood ratio between two competing statistical models.

### 📈 Submartingales (Favorable Games)

* **Biased Random Walk:** A random walk with a positive drift.
* **Absolute Value of a Martingale:** The process $|M_n|$ where $M_n$ is a martingale, demonstrating Jensen's inequality.
* **Maximum of a Random Walk:** The running maximum of a random walk, $M_n = \max(S_0, \dots, S_n)$.

### 📉 Supermartingales (Unfavorable Games)

* **Wealth in a Sub-Fair Game:** Models wealth decay when betting with a "house edge."
* **Coupon Collector's Problem:** Simulates the number of unique coupons remaining to be collected.
* **Fair Game with a Transaction Cost:** Models a martingale subject to a fixed cost at each step.
