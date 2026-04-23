---
layout: default
title: Detection Methods
nav_order: 4
---

# 🔍 RQ4: Detection Methods

Detection techniques are evolving from rigid static analysis to dynamic, model-driven, and hybrid evaluation frameworks. They form the diagnostic foundation of LLM quality governance.

---

## 💻 1. Code-Level Detection

Identifies defects in generated code using three main paradigms:

- **Dynamic Analysis**: Test-based execution and runtime monitoring to assess accuracy and efficiency.
- **Static Analysis**: Rule-based detection (SonarQube, Semgrep) for syntax errors and vulnerabilities.
- **Model-based Detection**: "LLM-as-a-judge" techniques and ML classifiers for semantic filtering.

<div align="center">
  <img src="images/generated_code_issues_detection.png" alt="Taxonomy of Code Issue Detection Methods" width="100%" style="border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.3);">
  <p><em>Fig. 6. Taxonomy of Code Issue Detection Techniques</em></p>
</div>

---

## 📊 2. Data-Level Detection

Targets the integrity, provenance, and representativeness of training data:

- **Dynamic Analysis**: Execution-based validation and metric drift monitoring (detecting data leakage).
- **Static Analysis**: Rule-based detection and provenance tracing using file hashes.
- **Model-based Detection**: Semantic screening using LLMs to evaluate readability and hazards.

<div align="center">
  <img src="images/data_quality_issues_detection.png" alt="Taxonomy of Dataset Issue Detection Methods" width="100%" style="border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.3);">
  <p><em>Fig. 7. Taxonomy of Training Data Issue Detection Techniques</em></p>
</div>




---

## 📄 Referenced Papers