---
layout: default
title: Data-to-Code Mapping
nav_order: 3
---

# 🔗 RQ3: Mapping Data Issues to Code Defects

How do data defects cause code generation failures? We formalize a causal framework detailing **18 propagation mapping mechanisms**.

---

## Propagation Mechanisms

We identify two primary types of propagation:

1.  **Direct Mappings (10 types)**: The classic "garbage in, garbage out" replication. The model explicitly memorizes dataset flaws (e.g., outdated APIs, security vulnerabilities) and replicates them in the output.
2.  **Indirect Mappings (8 types)**: Insidious propagation. Non-code defects do not inject explicit errors but disrupt the model's internal representations via mechanisms such as:
    *   **Entropy Collapse**: Redundancy leading to deterministic but incorrect outputs.
    *   **Representation Bias**: Skewed distributions causing the model to over-rely on common but suboptimal patterns.
    *   **Semantic Drift**: Low-value text confusing the model's understanding of code intent.

---

## Visualizing the Propagation

<div align="center">
  <img src="images/sankey.png" alt="Sankey Diagram of Mapping from Data Issues to Code Issues" width="100%" style="border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.3);">
  <p><em>Fig. 5. Mapping mechanisms from Training Data Issues to Generated Code Issues.</em></p>
</div>
