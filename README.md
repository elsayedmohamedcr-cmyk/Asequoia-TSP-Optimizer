Asequoia Innovation Labs | Algebraic & Physics-Inspired Optimization Framework
Exploratory Continuous-Relaxation Heuristics for the Euclidean TSP

An exploratory continuous-relaxation framework designed to investigate the Traveling Salesperson Problem (TSP) using a degree-constrained 2-factor polytope, spectral connectivity regularization, and homotopy-based parameter continuation.

🚀 Overview
Traditional approaches to NP-hard combinatorial optimization rely on discrete search and branching, facing exponential complexity blowup ($O(n!)$). This project explores an alternative continuous-relaxation paradigm combining four core mechanisms:
1. Cost Normalization & Landscape Pre-conditioning: Bounded cost scaling to stabilize continuous optimization dynamics.
2. Degree-Constrained Relaxation & Lagrange Multipliers: Maintaining weighted degree-two constraints over the fractional 2-factor polytope.
3. Spectral Connectivity Regularization: Using the Fiedler eigenvalue ($\lambda_2$) of the graph Laplacian to encourage network connectivity.
4. Homotopy Continuation & Double-Well Freezing: A quartic double-well penalty schedule designed to encourage near-binary edge weights ($X_{ij} \in [0, 1]$).

⚠️ Scientific Scope & Status
- **Exploratory Prototype:** This repository provides an auditable reference implementation and preliminary analysis. It does not claim a proof of $P = NP$.
- **Reconstruction Required:** The continuous matrix $X$ is a fractional relaxation, not a tour. A separate reconstruction stage (weight-biased nearest-neighbour followed by 2-opt) is implemented to return valid Hamiltonian cycles.
- **Conditional Claims:** Convergence and complexity statements are conditional working hypotheses, not proven theorems.

📜 Licensing & Commercial Usage Policy
This project operates under a Dual-Licensing Model governed by Asequoia:
- Academic & Non-Commercial Use: Free to use, study, modify, and distribute for academic research, educational purposes, and personal experimentation.
- Commercial Use: Any enterprise or commercial entity seeking to integrate or leverage this optimization framework must acquire a formal Commercial License from Asequoia.

For commercial licensing inquiries or enterprise integrations, please contact:
Email: asequoia.innovation.hq@gmail.com

© 2026 ELSAYED MOHAMED @ Asequoia Innovation Labs. All rights reserved.
