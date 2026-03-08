# Hi there, I'm Tingting (Arya) Chen 👋

🎓 **Ph.D. Candidate in Management Science & Engineering at Tongji University**
🔭 **Visiting Researcher at Université Paris-Saclay (IBISC Lab)**

I specialize in **Operations Research (OR)** with **Reinforcement Learning (RL)**, focusing on intelligent decision-making in network design and optimization, order fulfillment management, and sequential decision processes.

---

## 🚀 Key Research Projects

### 1. 🤖 [RLHF Project] LLM-Aligned Dynamic Pricing & Dispatch for Hybrid Fulfillment Fleets
> **Role:** Project Lead | **Status:** *Manuscript in Preparation*
- **Scenario:** Engineered an RL environment for a Hybrid Fleet (Autonomous Vehicles + Crowdsourced), tackling the high-dimensional dual-decision bottleneck: continuous AV spatial rebalancing vs. discrete crowdsourced surge pricing.
- **Method:** Built a decoupled** LLM-RLHF pipeline** to overcome the "alignment tax" seen in traditional online PPO+RM:
  - Trained an expert prior via Behavior Cloning (BC), followed by unconstrained PPO to explore the theoretical profit upper bound.
  - Designed an adversarial LLM preference sampling strategy (Qwen-based), utilizing hard-negative mining and focus-state sampling (targeting peak hours and remote zones) to heavily penalize "price whiplash" and remote crowdsourced worker fatigue.
- **Outcome:** The DPO-aligned policy successfully bypassed the profit collapse of traditional PPO+RM. It achieved Pareto optimality with **+17.08%** total reward and **-6.30%** relocation cost vs. BC. Crucially, it suppressed malignant price surges and proactively dispatched AVs to remote areas, actively reducing crowdsourced rider stress while maintaining a stable timeout rate.
- 🔗 **Links:** [💻 View Code](https://github.com/Arya-t/RLHF-Autonomous-Fleet)

---

### 2. 📈 [Journal Paper] Sequential Investment Decision via Deep Reinforcement Learning
> **Role:** First Author | **Status:** *Accepted by INFORMS TSL conference 2026 / Submitted to TRB*
- **Scenario:** Solving sequential network expansion problems considering dynamic spatial spillovers and parallel investment quantity constraints.
- **Method:** Formulated the problem as a **Markov Decision Process (MDP)** and proposed **TPPO (Transformer-based PPO)**:
  - Designed **Dual-head Decoding** and **Residual Feature Fusion** for topology perception.
  - Integrated **Real Option Analysis (ROA)** framework for reward shaping to quantify long-term value and address sparse feedback.
- **Outcome:** Improved NPV by **34.7%** compared to all-in deployment policy and Option Value by **51.6%** compared to heuristics in NYC MoD experiments.
- 🔗 **Links:** [💻 View Code](https://github.com/Arya-t/TPPO-Sequential-Investment) | [📄 Read Paper (PDF)](LINK_HERE)

---

### 3. 📦 [Journal Paper] Multi-Objective Reinforcement Learning for Order Fulfillment with Postponement
> **Role:** First Author | **Status:** *Major Revision at EJOR (JCR Q1)*
- **Scenario:** Balancing the high-dimensional trade-off between operational costs and multi-dimensional workload balance (intra/inter-period).
- **Method:** Proposed **GMORL-PSL** (Graph-based Multi-Objective RL with Pareto Set Learning):
  - Coupled **MOMDP** (Multi-objective MDP) with **MOVRPTW** (Multi-objective Vehicle Routing Problem with Time Windows).
  - Utilized **Hypernetwork** for dynamic policy generation approximating the continuous Pareto Front.
- **Outcome:** Outperformed scalarized MORL and static rules. Compared to the no-postponement baseline, reduced total cost by **6.92%**, intra-period workload imbalance by **13.55%**, and inter-period imbalance by **21.43%**, while boosting fleet utilization by **12.00%**.
- 🔗 **Links:** [💻 View Code](https://github.com/Arya-t/GMORL-Order-Fulfillment) | [📄 Read Paper (Preprint)](http://dx.doi.org/10.2139/ssrn.4889746)

---

### 4. 💊 [Journal Paper] Balanced Pharmaceutical Logistics Routing with Hybrid Heuristics
> **Role:** First Author | **Status:** *Published in IJPR (JCR Q1)*
- **Scenario:** Addressing transport resource imbalance and "tide effects" in multi-depot cold chain collaboration.
- **Method:** Modeled as **MDVRPTW** (Multi-depot Vehicle Routing Problem with Time Windows) with explicit vehicle flow balance constraints:
  - Solved using **Hybrid SAVNS** (Simulated Annealing + Variable Neighborhood Search).
- **Outcome:** Achieved **98.13%** fleet loading rate and **37.29%** average cost reduction compared to stand-alone scenarios.
- 🔗 **Links:** [💻 View Code](https://github.com/Arya-t/Balanced-Pharma-Logistics) | [📄 Read Paper (DOI)](https://doi.org/10.1080/00207543.2023.2283566)

---

### 🛠️ Tech Stack & Tools
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Gurobi](https://img.shields.io/badge/Solver-Gurobi-red)
![MATLAB](https://img.shields.io/badge/Code-MATLAB-blue)
![LaTeX](https://img.shields.io/badge/Tools-LaTeX-008080)

---

### 📫 Contact Me
- **Email:** [aryatt120999@gmail.com](mailto:aryatt120999@gmail.com)
- **Location:** Shanghai, China / Paris, France
