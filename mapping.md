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




---

## 📄 Referenced Papers

<div class="paper-card">
    <div class="paper-title">LLMs Meet Library Evolution</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-06</span>
        <a href="https://arxiv.org/abs/2406.09834" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">SStuBs</div>
    <div class="paper-meta">
        <span class="paper-tag">2023-03</span>
        <a href="https://arxiv.org/abs/2303.11455" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">AutoAPIEval</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-09</span>
        <a href="https://arxiv.org/abs/2409.15228" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">CodeIP</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-04</span>
        <a href="https://arxiv.org/abs/2404.15639" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">CIDRe</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://arxiv.org/abs/2505.19757" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Infinite-Instruct</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://arxiv.org/abs/2505.23177" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Quality In, Quality Out</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-03</span>
        <a href="https://arxiv.org/abs/2503.11402" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">SwallowCode</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://arxiv.org/abs/2505.02881" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Refining ChatGPT-Generated Code</div>
    <div class="paper-meta">
        <span class="paper-tag">2023-07</span>
        <a href="https://arxiv.org/abs/2307.12596" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">CRPE</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://arxiv.org/abs/2505.10594" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">StarCoder 2 and The Stack v2</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-02</span>
        <a href="https://arxiv.org/abs/2402.19173" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">CodeSmellEval</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-12</span>
        <a href="https://arxiv.org/abs/2412.18989" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">RPG</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://arxiv.org/abs/2505.10402" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Repetition In Repetition Out</div>
    <div class="paper-meta">
        <span class="paper-tag">2023-10</span>
        <a href="https://arxiv.org/abs/2310.10226" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">CodeMI</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-04</span>
        <a href="https://arxiv.org/abs/2404.14296" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">CodeCipher</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-10</span>
        <a href="https://arxiv.org/abs/2410.05797" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">DataComp-LM</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-06</span>
        <a href="https://arxiv.org/abs/2406.11794" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Code Llama</div>
    <div class="paper-meta">
        <span class="paper-tag">2023-08</span>
        <a href="https://arxiv.org/abs/2308.12950" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Path Planning Evaluation</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-04</span>
        <a href="https://arxiv.org/abs/2504.21276" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Datasets for Large Language Models</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-02</span>
        <a href="https://arxiv.org/abs/2402.18041" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Synthetic Data Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-01</span>
        <a href="https://ieeexplore.ieee.org/document/11080380" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Cracks in The Stack</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://ieeexplore.ieee.org/document/11028470" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Unseen Horizons</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-04</span>
        <a href="https://ieeexplore.ieee.org/document/11029836" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">DataRecipe</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-10</span>
        <a href="https://dl.acm.org/doi/10.1145/3691620.3695593" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">LLM-ProS</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://ieeexplore.ieee.org/document/11028406" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>