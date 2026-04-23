---
layout: default
title: Taxonomy
nav_order: 2
has_children: true
---

# 📚 Taxonomy of Quality Issues

We establish a unified taxonomy encompassing two core dimensions: **Generated Code Quality Issues** and **Training Data Quality Issues**.

---

## 💻 RQ1: Generated Code Quality Issues

We categorize quality issues in LLM-generated code into **9 core dimensions**:

| Dimension | Description | Typical Manifestations |
|:---|:---|:---|
| **Correctness** | Functional accuracy and executability | Syntax errors, logical flaws, API misuse |
| **Security** | Resilience against malicious exploitation | Inherent design flaws, external vulnerabilities |
| **Compliance** | Adherence to legal, ethical, and safety standards | Copyright infringement, privacy leakage, malicious code |
| **Robustness** | Ability to handle abnormal inputs gracefully | Inadequate error handling, boundary condition failures |
| **Maintainability** | Ease of long-term code modification | Disorganized structure, low reusability |
| **Understandability**| Human-readability and clarity | Poor naming conventions, lack of documentation |
| **Efficiency** | Optimal system resource utilization | Suboptimal time complexity, improper memory management |
| **Parsimony** | Conciseness of generated results | Redundant logic, useless loops, extreme verbosity |
| **Miscellaneous** | Anomalies outside core dimensions | Instruction-following failures |

<br>

<div align="center">
  <img src="images/generated_code_issues.png" alt="Taxonomy of Generated Code Quality Issues" width="100%" style="border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.3);">
  <p><em>Fig. 3. Taxonomy of Generated Code Quality Issues</em></p>
</div>

---

## 📊 RQ2: Training Data Quality Issues

We categorize intrinsic flaws within pre-training and fine-tuning corpora:

### 1. Code Attribute Quality Issues
Inherent defects within individual code samples that models explicitly learn (correctness, security, etc.).

### 2. Non-Code Attribute Quality Issues
Non-code textual noise and macro-level dataset flaws:
- **Compliance & Security**: Illegal/harmful, copyright-infringing, privacy-leaking text.
- **Distribution Imbalance**: Skewed proportions across languages, domains, or types.
- **Redundancy**: Excessive repetition or synthetic data degradation.
- **Diversity**: Insufficient coverage of real-world scenarios.
- **Contamination**: Leakage of evaluation data into training sets.
- **Low-Value Data**: Meaningless text, format noise, low-information density.

<br>

<div align="center">
  <img src="images/data_quality_issues.png" alt="Taxonomy of Dataset Quality Issues" width="100%" style="border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.3);">
  <p><em>Fig. 4. Taxonomy of Training Data Quality Issues</em></p>
</div>
