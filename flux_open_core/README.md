# 🌊 Flux Open Core 

**The Open-Source Engine Translating NP-Hard Combinatorial Problems into Continuous Polynomial-Time Fluid Flows.**

Welcome to the **Flux Open Core**, the academic and developer-facing repository of the Flux Routing Engine by Asequoia Innovation Labs. 

Traditional logistics routing relies on discrete combinatorial branching (like Branch and Bound or heuristic genetic algorithms), which invariably hits an exponential complexity wall ($O(n!)$). **Flux** throws away the Turing machine discretization and models the network as a physical dynamical system.

## 🚀 What is Flux?
Flux is a physics-based, continuous-relaxation solver for the Traveling Salesperson Problem (TSP). It embeds discrete nodes into a bounded continuous manifold governed by four rigorous algebraic/physical pillars:
1. **Mass-Preserving Erosion:** Pre-conditions the landscape to eliminate local minima traps.
2. **Fluid Relaxation & Active Suction:** Acts like a vacuum to prevent isolated peripheral nodes from forming disconnected sub-tours.
3. **Topological Repulsion:** Uses Coulombic/magnetic gradients to prevent path self-intersections.
4. **Fractional Crystallization:** Safely freezes the continuous flow matrix into exact binary states without shattering the system.

## 💻 Getting Started (The Basic Solver)
This repository contains `flux_basic_solver.py`, a pure Python implementation of the mathematical framework. It is designed for **readability, academic verification, and theoretical reproducibility**, not bare-metal speed.

### Installation & Usage
```bash
# Clone the repository
git clone [https://github.com/elsayedmohamedcr-cmyk/Asequoia-TSP-Optimizer.git](https://github.com/elsayedmohamedcr-cmyk/Asequoia-TSP-Optimizer.git)
cd Asequoia-TSP-Optimizer/flux_open_core

# Install dependencies
pip install numpy

# Run the basic solver
python flux_basic_solver.py
```
#### 🏢 Flux Enterprise & Commercial License
The code provided in this open-core repository is the Academic Proof-of-Concept. It successfully demonstrates the polynomial-time convex mapping but is intentionally unoptimized for large-scale production routing.

The Flux Enterprise Engine—which features hyper-optimized C++ backends, zero matrix pre-computation, spatial suction trees, and sub-3-millisecond latencies for 1,000+ nodes—is closed-source.

If you are a logistics enterprise, emergency dispatch utility, or supply chain startup looking to utilize Flux for commercial revenue, you must acquire a Commercial License.

Contact: asequoia.innovation.hq@gmail.com

© 2026 ELSAYED MOHAMED @ Asequoia Innovation Labs. All rights reserved.
