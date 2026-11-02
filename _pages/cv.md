---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Transportation Engineering, University of California, Los Angeles, Mar 2026 – present
  * Advisor: Prof. Youngseo Kim
* M.Eng. in Operations Research, University of California, Berkeley, Aug 2024 – May 2025
  * Advisor: Prof. Paul Grigas
* B.S. in Operations Management, University of Delaware, Sep 2020 – May 2024
* B.S. in Operations Management, Southwestern University of Finance and Economics, 2020 – 2024 (Dual Degree)

Research Experience
======
* **Traveler Choice-Aware Transit Operation with Frequency–Fare Coordination**, UCLA, Jan 2026 – present
  * Advisor: Prof. Youngseo Kim.
  * Joint design of transit fares and line frequencies as a bilevel Stackelberg program with traveler choice response and a funding cap.
* **Barrier-Metric First-Order Method for Linearly Constrained Bilevel Optimization**, UC Berkeley, Sep 2025 – present
  * Advisor: Prof. Paul Grigas. Supported in part by the NSF AI Institute for Advances in Optimization.
  * Log-barrier smoothing and a first-order method for bilevel programs with polyhedral lower-level feasible sets, validated on synthetic congestion-toll and constrained MNIST hypercleaning benchmarks.
* **Learning Behavioral Parameters of Network Equilibrium Models**, UCLA, May 2026 – Oct 2026
  * Funded by the University of California Institute of Transportation Studies (UC ITS). Advisor: Prof. Youngseo Kim.
  * Bi-level estimation of a combined destination, mode, and route choice equilibrium model with congestion, validated on Los Angeles County with public mobility data.

Project Experience
======
* **On-demand Food Delivery with a Smart Predict-then-Optimize Method**, UC Berkeley, Sep 2024 – present
  * Advisor: Prof. Paul Grigas.
  * Smart Predict-then-Optimize pipeline for on-demand food delivery dispatch under bandit feedback.
* **Robust Defibrillator Location Optimization and Satisficing under Uncertainty**, CUHK, Jul 2023 – Dec 2024
  * Advisor: Prof. Daniel Zhuoyu Long.
  * Distributionally robust optimization and robust satisficing models for siting automated external defibrillators under uncertainty.
* **Vehicle Routing Problem with Occasional Drivers under Uncertain Travel Costs**, University of Delaware, Sep 2022 – Jun 2023
  * Advisor: Prof. Yu Zhang.
  * Risk-averse certainty-equivalent model for last-mile routing, solved with a branch-and-price algorithm.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Professional Experience
======
* Operations Research Scientist, MathArt Inc., Shanghai, Jun 2024 – Aug 2024
  * Mixed-integer programming and genetic-algorithm methods for daily production scheduling across 1,000 SKUs.

Skills
======
* **Programming:** Python, R, SQL, MATLAB
* **Optimization:** Gurobi, CPLEX, MOSEK, IPOPT, CVXPY
* **Deep Learning & AI:** PyTorch, PyEPO, CvxpyLayers, Scikit-Learn
* **Data & Tools:** Pandas, Matplotlib, GeoPandas, Slurm, Git, LaTeX, Excel, Mathematica
