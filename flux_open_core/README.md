🌊 Flux Open Core
Exploratory Continuous-Relaxation Heuristics for Combinatorial Optimization.

Welcome to Flux Open Core, the academic and developer-facing repository of the Flux project by Asequoia Innovation Labs. 

Traditional logistics routing relies on discrete combinatorial branching (like Branch and Bound or genetic algorithms), which hits an exponential complexity wall ($O(n!)$). This project explores an alternative continuous-relaxation paradigm, embedding decision spaces into a bounded continuous manifold to investigate tractable heuristic approximations.

🚀 What is Flux?
Flux is an exploratory, continuous-relaxation solver for the Euclidean Traveling Salesperson Problem (TSP). It frames the optimization landscape through four core algebraic and physical mechanisms:
1. Landscape Pre-conditioning & Normalization: Bounded cost scaling to stabilize continuous optimization dynamics.
2. Degree-Constrained Relaxation & Lagrange Multipliers: Maintaining weighted degree-two constraints over the fractional 2-factor polytope to discourage disconnected components.
3. Spectral Connectivity Regularization: Using the Fiedler eigenvalue ($\lambda_2$) of the graph Laplacian to encourage network connectivity.
4. Homotopy Continuation & Double-Well Freezing: A quartic double-well penalty schedule designed to encourage near-binary edge weights ($X_{ij} \in [0, 1]$).

💻 Getting Started (The Basic Solver)
This repository contains `flux_basic_solver.py`, a pure Python implementation of the mathematical framework. It is designed for readability, academic verification, and theoretical reproducibility.

### Installation & Usage
```bash
# Clone the repository
git clone [https://github.com/elsayedmohamedcr-cmyk/Asequoia-TSP-Optimizer.git](https://github.com/elsayedmohamedcr-cmyk/Asequoia-TSP-Optimizer.git)
cd Asequoia-TSP-Optimizer/flux_open_core

# Install dependencies
pip install numpy scipy

# Run the basic solver
python flux_basic_solver.py
```
⚠️ Scientific Scope & Status:
The code in this repository provides an auditable reference implementation of a continuous-relaxation heuristic. The continuous matrix $X$ is a fractional relaxation, not a final tour; a separate reconstruction stage is utilized to return valid Hamiltonian cycles. Convergence and complexity claims are conditional working hypotheses, not proven theorems. This project does not claim a proof of $P = NP$.🏢 Flux Enterprise & Commercial Solutions
The code provided in this open-core repository serves as an academic proof-of-concept. It demonstrates the continuous-relaxation framework but is structured for auditability rather than hyper-optimized production throughput.The Flux Enterprise Engine—featuring optimized backends, advanced spatial routing structures, and production-grade latencies—is available commercially.If you are a logistics enterprise, emergency dispatch utility, or supply chain startup looking to utilize Flux for commercial operations, please contact us to acquire a Commercial License.Contact: asequoia.innovation.hq@gmail.com© 2026 ELSAYED MOHAMED @ Asequoia Innovation Labs. All rights reserved.
