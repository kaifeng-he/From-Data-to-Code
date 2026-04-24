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

<div class="paper-card">
    <div class="paper-title"><strong>LLMs Meet Library Evolution</strong>: LLMs Meet Library Evolution: Evaluating Deprecated API Usage in LLM-based Code Completion</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-06</span>
        <a href="https://arxiv.org/abs/2406.09834" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Less is More</strong>: Less is More: On the Importance of Data Quality for Unit Test Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-02</span>
        <a href="https://arxiv.org/abs/2502.14212" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Qwen</strong>: Qwen Technical Report</div>
    <div class="paper-meta">
        <span class="paper-tag">2023-09</span>
        <a href="https://arxiv.org/abs/2309.16609" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Qwen2</strong>: Qwen2 Technical Report</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-07</span>
        <a href="https://arxiv.org/abs/2407.10671" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>DataMan</strong>: DataMan: Data Manager for Pre-training Large Language Models</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-02</span>
        <a href="https://arxiv.org/abs/2502.19363" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Phi-4</strong>: Phi-4 Technical Report</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-12</span>
        <a href="https://arxiv.org/abs/2412.08905" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Copilot Security</strong>: Is GitHub’s Copilot as Bad as Humans at Introducing Vulnerabilities in Code?</div>
    <div class="paper-meta">
        <span class="paper-tag">2022-04</span>
        <a href="https://arxiv.org/abs/2204.04741" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Copilot Evaluation</strong>: An Empirical Evaluation of GitHub Copilot’s Code Suggestions</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-01</span>
        <a href="https://doi.org/10.1145/3524842.3528470" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>HalluCode</strong>: Exploring and Evaluating Hallucinations in LLM-Powered Code Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-04</span>
        <a href="https://arxiv.org/abs/2404.00971" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>CodeHalu</strong>: CodeHalu: Investigating Code Hallucinations in LLMs via Execution-based Verification</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-05</span>
        <a href="https://arxiv.org/abs/2405.00253" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>EffiBench</strong>: EffiBench: Benchmarking the Efficiency of Automatically Generated Code</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-02</span>
        <a href="https://arxiv.org/abs/2402.02037" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Mercury</strong>: Mercury: A Code Efficiency Benchmark for Code Large Language Models</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-02</span>
        <a href="https://arxiv.org/abs/2402.07844" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>SStuBs</strong>: Large Language Models and Simple, Stupid Bugs</div>
    <div class="paper-meta">
        <span class="paper-tag">2023-03</span>
        <a href="https://arxiv.org/abs/2303.11455" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>package hallucinations</strong>: We Have a Package for You! A Comprehensive Analysis of Package Hallucinations by Code Generating LLMs</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-06</span>
        <a href="https://arxiv.org/abs/2406.10279" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>HallTrigger</strong>: Code Hallucination</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-07</span>
        <a href="https://arxiv.org/abs/2407.04831" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Large Language Models for Code</strong>: Large Language Models for Code: Security Hardening and Adversarial Testing</div>
    <div class="paper-meta">
        <span class="paper-tag">2023-02</span>
        <a href="https://arxiv.org/abs/2302.05319" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Purple Llama CYBERSECEVAL</strong>: Purple Llama CYBERSECEVAL: A Secure Coding Benchmark for Language Models</div>
    <div class="paper-meta">
        <span class="paper-tag">2023-12</span>
        <a href="https://arxiv.org/abs/2312.04724" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Lost at C</strong>: Lost at C: A User Study on the Security Implications of Large Language Model Code Assistants</div>
    <div class="paper-meta">
        <span class="paper-tag">2022-08</span>
        <a href="https://arxiv.org/abs/2208.09727" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>AI Assistants Security</strong>: Do Users Write More Insecure Code with AI Assistants?</div>
    <div class="paper-meta">
        <span class="paper-tag">2022-11</span>
        <a href="https://arxiv.org/abs/2211.03622" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>The Counterfeit Conundrum</strong>: The Counterfeit Conundrum: Can Code Language Models Grasp the Nuances of Their Incorrect Generations?</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-02</span>
        <a href="https://arxiv.org/abs/2402.19475" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Bugs in LLM-generated Code</strong>: Bugs in Large Language Models Generated Code: An Empirical Stud</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-03</span>
        <a href="https://arxiv.org/abs/2403.08937" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>GitHub Copilot, Amazon CodeWhisperer, ChatGPT</strong>: Evaluating the Code Quality of AI-Assisted Code Generation Tools: An Empirical Study on GitHub Copilot, Amazon CodeWhisperer, and ChatGPT</div>
    <div class="paper-meta">
        <span class="paper-tag">2023-04</span>
        <a href="https://arxiv.org/abs/2304.10778" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>ChatGPT Code Quality</strong>: No Need to Lift a Finger Anymore? Assessing the Quality of Code Generation by ChatGPT</div>
    <div class="paper-meta">
        <span class="paper-tag">2023-08</span>
        <a href="https://arxiv.org/abs/2308.04838" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>CloudAPIBench</strong>: On Mitigating Code LLM Hallucinations with API Documentation</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-07</span>
        <a href="https://arxiv.org/abs/2407.09726" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>CodeMirage</strong>: CodeMirage: Hallucinations in Code Generated by Large Language Models</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-08</span>
        <a href="https://arxiv.org/abs/2408.08333" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>LLM-generated Code Efficiency</strong>: On Evaluating the Efficiency of Source Code Generated by LLMs</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-04</span>
        <a href="https://arxiv.org/abs/2404.06041" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Syntactic Robustness</strong>: Syntactic Robustness for LLM-based Code Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-04</span>
        <a href="https://arxiv.org/abs/2404.01535" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>DeSec</strong>: Decoding Secret Memorization in Code LLMs Through Token-Level Characterization</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-10</span>
        <a href="https://arxiv.org/abs/2410.08858" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Bias Unveiled</strong>: Bias Unveiled: Investigating Social Bias in LLM-Generated Code</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-11</span>
        <a href="https://arxiv.org/abs/2411.10351" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>FairCoder</strong>: FairCoder: Evaluating Social Bias of LLMs in Code Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-01</span>
        <a href="https://arxiv.org/abs/2501.05396" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>From Effectiveness to Efficiency</strong>: From Effectiveness to Efficiency: Comparative Evaluation of Code Generated by LCGMs for Bilingual Programming Questions</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-06</span>
        <a href="https://arxiv.org/abs/2406.00602" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>ENAMEL</strong>: How Efficient is LLM-Generated Code? A Rigorous & High-Standard Benchmark</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-06</span>
        <a href="https://arxiv.org/abs/2406.06647" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>DeVAIC</strong>: DeVAIC: A Tool for Security Assessment of AI-generated Code</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-04</span>
        <a href="https://arxiv.org/abs/2404.07548" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>PTMs</strong>: Comparing Robustness Against Adversarial Attacks in Code Generation: LLM-Generated vs. Human-Written</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-11</span>
        <a href="https://arxiv.org/abs/2411.10565" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Codequal Analyzer</strong>: Improving LLM-Generated Code Quality with GRPO</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-06</span>
        <a href="https://arxiv.org/abs/2506.02211" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Artificial-Intelligence Generated Code Considered Harmful</strong>: Artificial-Intelligence Generated Code Considered Harmful: A Road Map for Secure and High-Quality Code Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-09</span>
        <a href="https://arxiv.org/abs/2409.19182" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Unveiling Inefficiencies in LLM-Generated Code</strong>: Unveiling Inefficiencies in LLM-Generated Code: Toward a Comprehensive Taxonomy</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-03</span>
        <a href="https://arxiv.org/abs/2503.06327" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Python Tests Quality</strong>: Quality Assessment of Python Tests Generated by Large Language Models</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-06</span>
        <a href="https://arxiv.org/abs/2506.14297" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>CoQuIR</strong>: CoQuIR: A Comprehensive Benchmark for Code Quality-Aware Information Retrieval</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-06</span>
        <a href="https://arxiv.org/abs/2506.11066" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>REAL</strong>: Training Language Models to Generate Quality Code with Program Analysis Feedback</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://arxiv.org/abs/2505.22704" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>CIDRe</strong>: CIDRe: A Reference-Free Multi-Aspect Criterion for Code Comment Quality Measurement</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://arxiv.org/abs/2505.19757" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Infinite-Instruct</strong>: Infinite-Instruct: Synthesizing Scaling Code instruction Data with Bidirectional Synthesis and Static Verification</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://arxiv.org/abs/2505.23177" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Quality In, Quality Out</strong>: Quality In, Quality Out: Investigating Training Data's Role in AI Code Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-03</span>
        <a href="https://arxiv.org/abs/2503.11402" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Security and Quality in LLM-Generated Code</strong>: Security and Quality in LLM-Generated Code: A Multi-Language, Multi-Model Analysis</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-02</span>
        <a href="https://arxiv.org/abs/2502.01853" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>SwallowCode</strong>: Rewriting Pre-Training Data Boosts LLM Performance in Math and Code</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://arxiv.org/abs/2505.02881" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>ROSE</strong>: ROSE: Transformer-Based Refactoring Recommendation for Architectural Smells</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-07</span>
        <a href="https://arxiv.org/abs/2507.12561" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Refining ChatGPT-Generated Code</strong>: Refining ChatGPT-Generated Code: Characterizing and Mitigating Code Quality Issues</div>
    <div class="paper-meta">
        <span class="paper-tag">2023-07</span>
        <a href="https://arxiv.org/abs/2307.12596" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Qwen3</strong>: Qwen3 Technical Report</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://arxiv.org/abs/2505.09388" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Qwen2.5</strong>: Qwen2.5 Technical Report</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-12</span>
        <a href="https://arxiv.org/abs/2412.15115" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>TeleChat</strong>: Technical Report of TeleChat2, TeleChat2.5 and T1</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-07</span>
        <a href="https://arxiv.org/abs/2507.18013" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Kimi K2</strong>: Kimi K2: Open Agentic Intelligence</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-07</span>
        <a href="https://arxiv.org/abs/2507.20534" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>ReCode</strong>: ReCode: Updating Code API Knowledge with Reinforcement Learning</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-06</span>
        <a href="https://arxiv.org/abs/2506.20495" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Seed-Coder</strong>: Seed-Coder: Let the Code Model Curate Data for Itself</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-06</span>
        <a href="https://arxiv.org/abs/2506.03524" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Data-efficient Fine-tuning</strong>: Data-efficient LLM Fine-tuning for Code Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-04</span>
        <a href="https://arxiv.org/abs/2504.12687" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>CRPE</strong>: CRPE: Expanding The Reasoning Capability of Large Language Model for Code Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://arxiv.org/abs/2505.10594" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>DeepSeek-Coder</strong>: DeepSeek-Coder: When the Large Language Model Meets Programming -- The Rise of Code Intelligence</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-01</span>
        <a href="https://arxiv.org/abs/2401.14196" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>StarCoder 2 and The Stack v2</strong>: StarCoder 2 and The Stack v2: The Next Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-02</span>
        <a href="https://arxiv.org/abs/2402.19173" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>CodeSmellEval</strong>: How Propense Are Large Language Models at Producing Code Smells? A Benchmarking Study</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-12</span>
        <a href="https://arxiv.org/abs/2412.18989" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>RPG</strong>: Rethinking Repetition Problems of LLMs in Code Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://arxiv.org/abs/2505.10402" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Repetition In Repetition Out</strong>: Repetition In Repetition Out: Towards Understanding Neural Text Degeneration from the Data Perspective</div>
    <div class="paper-meta">
        <span class="paper-tag">2023-10</span>
        <a href="https://arxiv.org/abs/2310.10226" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Every Sample Matters</strong>: Every Sample Matters: Leveraging Mixture-of-Experts and High-Quality Data for Efficient and Accurate Code LLM</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-03</span>
        <a href="https://arxiv.org/abs/2503.17793" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>WaveCoder</strong>: WaveCoder: Widespread And Versatile Enhancement For Code Large Language Models By Instruction Tuning</div>
    <div class="paper-meta">
        <span class="paper-tag">2023-12</span>
        <a href="https://arxiv.org/abs/2312.14187" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Brevity is the soul of wit</strong>: Brevity is the soul of wit: Pruning long files for code generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-07</span>
        <a href="https://arxiv.org/abs/2407.00434" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Benchmark Builders</strong>: Large Language Models are Qualified Benchmark Builders: Rebuilding Pre-Training Datasets for Advancing Code Intelligence Tasks</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-04</span>
        <a href="https://arxiv.org/abs/2504.19444" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Beyond Correctness</strong>: Beyond Correctness: Benchmarking Multi-dimensional Code Generation for Large Language Models</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-07</span>
        <a href="https://arxiv.org/abs/2407.11470" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Generated Code Diversity</strong>: Is Functional Correctness Enough to Evaluate Code Language Models? Exploring Diversity of Generated Codes</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-08</span>
        <a href="https://arxiv.org/abs/2408.14504" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>CodeMI</strong>: Does Your Neural Code Completion Model Use My Code? A Membership Inference Approach</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-04</span>
        <a href="https://arxiv.org/abs/2404.14296" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>DataComp-LM</strong>: DataComp-LM: In search of the next generation of training sets for language models</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-06</span>
        <a href="https://arxiv.org/abs/2406.11794" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Codex</strong>: Evaluating Large Language Models Trained on Code</div>
    <div class="paper-meta">
        <span class="paper-tag">2021-07</span>
        <a href="https://arxiv.org/abs/2107.03374" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Path Planning Evaluation</strong>: Assessing LLM code generation quality through path planning tasks</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-04</span>
        <a href="https://arxiv.org/abs/2504.21276" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>CODEJUDGE</strong>: CODEJUDGE : Evaluating Code Generation with Large Language Models</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-01</span>
        <a href="https://aclanthology.org/2024.emnlp-main.1118.pdf?utm_source=chatgpt.com" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Datasets for Large Language Models</strong>: Datasets for Large Language Models: A Comprehensive Survey</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-02</span>
        <a href="https://arxiv.org/abs/2402.18041" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Synthetic Data Generation</strong>: Synthetic Data Generation Using Large Language Models: Advances in Text and Code</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-01</span>
        <a href="https://ieeexplore.ieee.org/document/11080380" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Cracks in The Stack</strong>: Cracks in The Stack: Hidden Vulnerabilities and Licensing Risks in LLM Pre-Training Datasets</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://ieeexplore.ieee.org/document/11028470" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Unseen Horizons</strong>: Unseen Horizons: Unveiling the Real Capability of LLM Code Generation Beyond the Familiar</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-04</span>
        <a href="https://ieeexplore.ieee.org/document/11029836" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>MG-Verilog</strong>: MG-Verilog: Multi-grained Dataset Towards Enhanced LLM-assisted Verilog Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-06</span>
        <a href="https://ieeexplore.ieee.org/document/10691738" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Code Generation Survey</strong>: A Survey on Large Language Models for Code Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-08</span>
        <a href="https://dl.acm.org/doi/10.1145/3747588" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>DataRecipe</strong>: DataRecipe --- How to Cook the Data for CodeLLM?</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-10</span>
        <a href="https://dl.acm.org/doi/10.1145/3691620.3695593" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Training Data Extraction</strong>: Understanding Privacy Risks of Large Language Models in Japanese Based on Training Data Extraction Attacks</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-08</span>
        <a href="https://dl.acm.org/doi/10.1145/3709018.3736331" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>aiXcoder-7B</strong>: aiXcoder-7B: A Lightweight and Effective Large Language Model for Code Processing</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-04</span>
        <a href="https://ieeexplore.ieee.org/document/11121702" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Imperfect Code Generation</strong>: Imperfect Code Generation: Uncovering Weaknesses in Automatic Code Generation by Large Language Models</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-05</span>
        <a href="https://ieeexplore.ieee.org/document/10554837" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Inter-Dataset Code Duplication</strong>: On Inter-Dataset Code Duplication and Data Leakage in Large Language Models</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-01</span>
        <a href="https://ieeexplore.ieee.org/document/10759822" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>LLM-ProS</strong>: LLM-ProS: Analyzing Large Language Models’ Performance in Competitive Problem Solving</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-05</span>
        <a href="https://ieeexplore.ieee.org/document/11028406" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>ClassEval</strong>: Evaluating Large Language Models in Class-Level Code Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-6</span>
        <a href="https://ieeexplore.ieee.org/document/10549472" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Uncovering Pretraining Code in LLMs</strong>: Uncovering Pretraining Code in LLMs: A Syntax-Aware Attribution Approach</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-11</span>
        <a href="https://arxiv.org/abs/2511.07033" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>RealSec-Bench</strong>: RealSec-bench: A Benchmark for Evaluating Secure Code Generation in Real-World Repositories</div>
    <div class="paper-meta">
        <span class="paper-tag">2026-01</span>
        <a href="https://arxiv.org/abs/2601.22706" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>ShortCoder</strong>: ShortCoder: Knowledge-Augmented Syntax Optimization for Token-Efficient Code GenerationPreprint</div>
    <div class="paper-meta">
        <span class="paper-tag">2026-01</span>
        <a href="https://arxiv.org/abs/2601.09703" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>APIKG4SYN</strong>: Framework-Aware Code Generation with API Knowledge Graph-Constructed Data: A Study on HarmonyOS</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-11</span>
        <a href="https://arxiv.org/abs/2512.00380" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>MultiCodeIF</strong>: A hierarchical and evolvable benchmark for fine-grained code instruction following with multi-turn feedback</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-07</span>
        <a href="https://arxiv.org/abs/2507.00699" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Beyond Functional Correctness</strong>: Beyond functional correctness: Investigating coding style inconsistencies in large language models</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-06</span>
        <a href="https://arxiv.org/abs/2407.00456" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Adadec</strong>: Adadec: Uncertainty-guided adaptive decoding for llm-based code generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-06</span>
        <a href="https://arxiv.org/html/2506.08980v1" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Code Copycat Conundrum</strong>: Code Copycat Conundrum: Demystifying Repetition in LLM-based Code Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-04</span>
        <a href="https://arxiv.org/abs/2504.12608" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>AllianceCoder</strong>: What to retrieve for effective retrieval-augmented code generation? an empirical study and beyond</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-03</span>
        <a href="https://arxiv.org/abs/2503.20589" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>RustEvo^ 2</strong>: RustEvo^ 2: An Evolving Benchmark for API Evolution in LLM-based Rust Code Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-03</span>
        <a href="https://arxiv.org/abs/2503.16922" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>RobGen</strong>: A Preliminary Study on the Robustness of Code Generation by Large Language Models</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-03</span>
        <a href="https://arxiv.org/abs/2503.20197" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>Llm Hallucinations in Practical Code Generation</strong>: Llm hallucinations in practical code generation: Phenomena, mechanism, and mitigation</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-09</span>
        <a href="https://arxiv.org/abs/2409.20550" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>COFFE</strong>: COFFE: A Code Efficiency Benchmark for Code Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-02</span>
        <a href="https://arxiv.org/abs/2502.02827" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>

<div class="paper-card">
    <div class="paper-title"><strong>AATK Benchmark</strong>: Asleep at the keyboard? assessing the security of github copilot's code contributions</div>
    <div class="paper-meta">
        <span class="paper-tag">2021-08</span>
        <a href="https://dl.acm.org/doi/10.1145/3610721" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>