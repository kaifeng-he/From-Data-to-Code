---
layout: default
title: Governance Strategies
nav_order: 5
---

# 🛠️ RQ5: Governance Strategies

We synthesize a **Multi-layered Governance Framework** spanning the data lifecycle and model inference stages.

---

## 💻 1. Code-Level Mitigation

- **Model-level**: SFT, RLHF/DPO, Reward-based optimization (execution correctness + static metrics).
- **Generation-level**:
  - _Pre-generation_: Prompt Engineering, RAG, and Agent-based workflows.
  - _In-generation_: Adaptive decoding constraints and Iterative Self-reflection.
  - _Post-generation_: Automated AST-level repairs and sandbox execution filtering.

<div align="center">
  <img src="images/generated_code_issues_detection.png" alt="Taxonomy of Code Issue Mitigation Strategies" width="100%" style="border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.3);">
  <p><em>Fig. 8. Taxonomy of Code Issue Mitigation Strategies</em></p>
</div>

---

## 📊 2. Data-Level Mitigation

- **Cleaning & Filtering**: Execution-feedback elimination and LLM-driven semantic cleaning.
- **Data Balancing**: Stratified resampling across languages and domains to mitigate bias.
- **Data Enhancement**: Refactoring, adding docstrings, and standardizing low-quality code.
- **Data Augmentation**: High-quality synthetic generation and integration of curated OS repos.

<div align="center">
  <img src="images/data_quality_issues_mitigation.png" alt="Taxonomy of Dataset Issue Mitigation Strategies" width="100%" style="border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.3);">
  <p><em>Fig. 9. Taxonomy of Training Data Issue Mitigation Strategies</em></p>
</div>


---

## 📄 Referenced Papers
