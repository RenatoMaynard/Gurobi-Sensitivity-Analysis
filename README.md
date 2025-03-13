# Gurobi Sensitivity Analysis

This repository demonstrates how to perform **Sensitivity Analysis** in Gurobi for **Linear Programming (LP)** and **Mixed-Integer Programming (MIP)** models. The focus is on extracting and interpreting:
- **Objective coefficient ranges** (how much you can change profit/cost coefficients before the solution changes).
- **Right-hand side (RHS) ranges** (how much you can change resource limits before the shadow price/dual value changes).
- **Dual values (Shadow prices)** for constraints.
- **Reduced costs** for decision variables.

---

## 📊 Features

- **General framework** for performing Sensitivity Analysis on any LP/MIP model.
- Prints **allowable increases and decreases** for:
  - Objective function coefficients.
  - RHS of constraints.
- Computes and displays **dual values (shadow prices)**.
- Computes **reduced costs** for variables.
- Fully compatible with **Gurobi** and Python.
