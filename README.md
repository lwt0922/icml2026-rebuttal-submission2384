# icml2026-rebuttal-submission2384
# Supplemental Figures for Submission 2384 Rebuttal

We provide the high-resolution figures and tables referenced in our author response below to address the reviewers' questions comprehensively.

### Table R1: Empirical Comparison with Traditional Baselines
*Referenced in response to Reviewer H8X7 (Q1). Traditional methods degrade severely in high-dimensional, multi-treatment regimes.*

| Method | Medium-Scale ($K=4$) | Large-Scale ($K=20$) |
| :--- | :--- | :--- |
| KNN Matching | 2.612 | 16.844 |
| IPW (Multinomial) | 1.012 | 2.478 |
| Base Model (Unadjusted) | 0.796 | 1.029 |
| **Ours (Aggregation, $\alpha^*$)** | **0.722** | **0.989** |

### Figure R6: Empirical Proof of Convergence (Gradient Descent vs. Grid Search)
*Referenced in response to Reviewer H8X7 (Q2).*
![Figure R6](fig_r6_gd.png)
*Caption: Continuous GD trajectory successfully descending the validation landscape and converging to exactly α* = 0.50, matching our discrete Grid Search optimum.*

---

### Figure R7: Strict Optimal α* Comparison at Extreme Scale (K=100)
*Referenced in response to Reviewer H8X7 (Q4).*
![Figure R7](fig_r7_k100.png)
*Caption: At K=100, the Pairwise strategy suffers severe gradient conflicts, while our Aggregation method decisively wins at a gentle α* = 0.45.*
