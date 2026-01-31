## Online Pricing under Budget Constraints

This project studies online pricing problems under production and budget constraints, using the fundamental ideas of online learning and bandits.<br/>

The goal is to design learning algorithms that dynamically select prices in order to maximize cumulative profit while respecting global and per-round budget constraints, in both stationary and non-stationary environments.

## Problem Setting

We consider an online seller interacting with a stream of buyers over a finite time horizon. At each round, the seller chooses prices for one or more products, observes the realized demand, and collects revenue while consuming a limited production budget.<br/>

Key challenges addressed in this project include:
- Budget-aware decision making under uncertainty
- Exploration–exploitation trade-offs
- Extension from single-product to multi-product pricing
- Learning in highly non-stationary environments
- Definition of appropriate baselines

Performance is evaluated through pseudo-regret, and computed against suitable budget-aware clairvoyant baselines.

## Methods and Strategies

While designing and implementing our solution, we explored:

- Budget-aware UCB extensions
- Mixed pricing policies selected via Linear Programming
- Primal–Dual algorithms with Lagrange multipliers for non-stationary settings
- Sliding-window techniques to track abrupt changes in demand

# Acknowledgements

I thank my colleagues and friends [Francesco Allegrini](not-found) and [Mattia Repetti](https://github.com/MattiaRepetti) who worked with me on this project.
