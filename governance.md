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

<div class="paper-card">
    <div class="paper-title">LLMs Meet Library Evolution</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-06</span>
        <a href="https://arxiv.org/abs/2406.09834" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Less is More</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-02</span>
        <a href="https://arxiv.org/abs/2502.14212" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Qwen</div>
    <div class="paper-meta">
        <span class="paper-tag">2023-09</span>
        <a href="https://arxiv.org/abs/2309.16609" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Qwen2</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-07</span>
        <a href="https://arxiv.org/abs/2407.10671" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">DataMan</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-02</span>
        <a href="https://arxiv.org/abs/2502.19363" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Phi-4</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-12</span>
        <a href="https://arxiv.org/abs/2412.08905" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title">package hallucinations</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-06</span>
        <a href="https://arxiv.org/abs/2406.10279" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Large Language Models for Code</div>
    <div class="paper-meta">
        <span class="paper-tag">2023-02</span>
        <a href="https://arxiv.org/abs/2302.05319" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">CloudAPIBench</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-07</span>
        <a href="https://arxiv.org/abs/2407.09726" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title">Codequal Analyzer</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-06</span>
        <a href="https://arxiv.org/abs/2506.02211" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">REAL</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://arxiv.org/abs/2505.22704" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title">Qwen3</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://arxiv.org/abs/2505.09388" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Qwen2.5</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-12</span>
        <a href="https://arxiv.org/abs/2412.15115" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">TeleChat</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-07</span>
        <a href="https://arxiv.org/abs/2507.18013" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Kimi K2</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-07</span>
        <a href="https://arxiv.org/abs/2507.20534" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">ReCode</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-06</span>
        <a href="https://arxiv.org/abs/2506.20495" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Seed-Coder</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-06</span>
        <a href="https://arxiv.org/abs/2506.03524" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Data-efficient Fine-tuning</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-04</span>
        <a href="https://arxiv.org/abs/2504.12687" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title">DeepSeek-Coder</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-01</span>
        <a href="https://arxiv.org/abs/2401.14196" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Code Pretraining</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-09</span>
        <a href="https://arxiv.org/abs/2409.04556" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title">Brevity is the soul of wit</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-07</span>
        <a href="https://arxiv.org/abs/2407.00434" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Benchmark Builders</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-04</span>
        <a href="https://arxiv.org/abs/2504.19444" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title">RedStone</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-12</span>
        <a href="https://arxiv.org/abs/2412.03398" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title">Codex</div>
    <div class="paper-meta">
        <span class="paper-tag">2021-07</span>
        <a href="https://arxiv.org/abs/2107.03374" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title">CODEJUDGE</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-01</span>
        <a href="https://aclanthology.org/2024.emnlp-main.1118.pdf?utm_source=chatgpt.com" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title">MG-Verilog</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-06</span>
        <a href="https://ieeexplore.ieee.org/document/10691738" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Code Generation Survey</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-08</span>
        <a href="https://dl.acm.org/doi/10.1145/3747588" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title">aiXcoder-7B</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-04</span>
        <a href="https://ieeexplore.ieee.org/document/11121702" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Imperfect Code Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-05</span>
        <a href="https://ieeexplore.ieee.org/document/10554837" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Inter-Dataset Code Duplication</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-01</span>
        <a href="https://ieeexplore.ieee.org/document/10759822" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">LLM-ProS</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://ieeexplore.ieee.org/document/11028406" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">UCD-Training</div>
    <div class="paper-meta">
        <span class="paper-tag">2026-02</span>
        <a href="https://arxiv.org/abs/2602.20799" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">ShortCoder</div>
    <div class="paper-meta">
        <span class="paper-tag">2026-01</span>
        <a href="https://arxiv.org/abs/2601.09703" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">APIKG4SYN</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-11</span>
        <a href="https://arxiv.org/abs/2512.00380" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">MultiCodeIF</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-07</span>
        <a href="https://arxiv.org/abs/2507.00699" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Beyond Functional Correctness</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-06</span>
        <a href="https://arxiv.org/abs/2407.00456" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Adadec</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-06</span>
        <a href="https://arxiv.org/html/2506.08980v1" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Code Copycat Conundrum</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-04</span>
        <a href="https://arxiv.org/abs/2504.12608" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">AllianceCoder</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-03</span>
        <a href="https://arxiv.org/abs/2503.20589" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">RustEvo^ 2</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-03</span>
        <a href="https://arxiv.org/abs/2503.16922" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">RobGen</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-03</span>
        <a href="https://arxiv.org/abs/2503.20197" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">Llm Hallucinations in Practical Code Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-09</span>
        <a href="https://arxiv.org/abs/2409.20550" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title">COFFE</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-02</span>
        <a href="https://arxiv.org/abs/2502.02827" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>