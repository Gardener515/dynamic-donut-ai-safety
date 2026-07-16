# WIP:dynamic-donut-ai-safety
This is an independent research draft. No institutional affiliation. Feedback and collaboration welcome.
# WIP: Dynamic Donut Safety Framework

**This is an independent research draft.**  
No institutional affiliation. Feedback and collaboration welcome.

## Abstract

We present a revised formulation of the Dynamic Donut Safety Framework for layered AI safety. The framework realizes safety as an intrinsic, time-varying annular viability tube in state space, equipped with:

- A discrete-time robust invariance theorem with explicit recursive feasibility (viability rate condition)
- Controlled topological surgery for irreversible actions (pinch events) with lead-time evacuation
- Codimension-2 topological protection via order-parameter reduction, enabling extension to high dimensions
- Risk-warped metric and action fibers driven by the aggregate signal Ξ(t)
- A homotopy-class-preserving isotopy-style filter
- Probabilistic invariance under stochastic exposure
- Two-timescale analysis of the slow memory loop M(t) with Goodhart robustness and adiabatic invariance

The result is a mathematically rigorous, simulatable interface in which recoverable risks are handled by continuous geometric deformation and irreversible risks are handled by monotone topological exclusion.

## Core Contributions (v3)

- Discrete-time Main Theorem with recursive feasibility and homotopy preservation (pre-pinch)
- Formalization of pinch events as controlled topological surgeries (S1–S2 assumptions)
- Codimension-2 analysis and order-parameter construction for high-dimensional generalization
- Systematic comparison with HJ reachability, CBFs, Tube MPC, safety filters, etc. (see Table 1)
- Stochastic wind: chance-constrained and supermartingale invariance
- Slow loop M(t): averaging stability + Goodhart-robust design + adiabatic invariant
- 2D simulations demonstrating warped asymmetric donuts and controller behavior

## Repository Contents

- `donut revision sections v3.pdf` — Main revision document (12 pages)
- `simulation/` — 2D toy model code (symmetric + asymmetric warped versions)
- `README.md` & `LICENSE`

## Status

**Work in Progress / Preprint Draft** (July 2026)

Actively iterating. The framework is conceptual but supported by formal theorems and numerical validation in 2D. High-dimensional implementation and further empirical evaluation are ongoing.

## How to Cite (temporary)
 Yuzhou LI “The Dynamic Donut Safety Framework”, GitHub preprint, July 2026
