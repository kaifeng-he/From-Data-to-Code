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
    <div class="paper-title"><strong>Syntactic Robustness</strong>: Syntactic Robustness for LLM-based Code Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-04</span>
        <a href="https://arxiv.org/abs/2404.01535" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>
<div class="paper-card">
    <div class="paper-title"><strong>NLPerturbator</strong>: NLPerturbator: Studying the Robustness of Code LLMs to Natural Language Variations</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-06</span>
        <a href="https://arxiv.org/abs/2406.19783" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>
<div class="paper-card">
    <div class="paper-title"><strong>AutoAPIEval</strong>: A Comprehensive Framework for Evaluating API-oriented Code Generation in Large Language Models</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-09</span>
        <a href="https://arxiv.org/abs/2409.15228" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title"><strong>When Fine-Tuning LLMs Meets Data Privacy</strong>: When Fine-Tuning LLMs Meets Data Privacy: An Empirical Study of Federated Learning in LLM-Based Program Repair</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-12</span>
        <a href="https://arxiv.org/abs/2412.01072" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title"><strong>CodeIP</strong>: CodeIP: A Grammar-Guided Multi-Bit Watermark for Large Language Models of Code</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-04</span>
        <a href="https://arxiv.org/abs/2404.15639" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title"><strong>Software Librarian</strong>: Is ChatGPT a Good Software Librarian? An Exploratory Study on the Use of ChatGPT for Software Library Recommendations</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-08</span>
        <a href="https://arxiv.org/abs/2408.05128" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title"><strong>Qwen2.5</strong>: Qwen2.5 Technical Report</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-12</span>
        <a href="https://arxiv.org/abs/2412.15115" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title"><strong>GPT-4</strong>: GPT-4 Technical Report</div>
    <div class="paper-meta">
        <span class="paper-tag">2023-03</span>
        <a href="https://arxiv.org/abs/2303.08774" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>
<div class="paper-card">
    <div class="paper-title"><strong>Code Pretraining</strong>: How Does Code Pretraining Affect Language Model Task Performance?</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-09</span>
        <a href="https://arxiv.org/abs/2409.04556" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title"><strong>Code Data Training Stage</strong>: At Which Training Stage Does Code Data Help LLMs Reasoning?</div>
    <div class="paper-meta">
        <span class="paper-tag">2023-09</span>
        <a href="https://arxiv.org/abs/2309.16298" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title"><strong>CodeCipher</strong>: CodeCipher: Learning to Obfuscate Source Code Against LLMs</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-10</span>
        <a href="https://arxiv.org/abs/2410.05797" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>
<div class="paper-card">
    <div class="paper-title"><strong>Code Pre-training Impact</strong>: To Code, or Not To Code? Exploring Impact of Code in Pre-training</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-08</span>
        <a href="https://arxiv.org/abs/2408.10914" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title"><strong>RedStone</strong>: RedStone: Curating General, Code, Math, and QA Data for Large Language Models</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-12</span>
        <a href="https://arxiv.org/abs/2412.03398" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>
<div class="paper-card">
    <div class="paper-title"><strong>Code Llama</strong>: Code Llama: Open Foundation Models for Code</div>
    <div class="paper-meta">
        <span class="paper-tag">2023-08</span>
        <a href="https://arxiv.org/abs/2308.12950" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title"><strong>RTL-Breaker</strong>: RTL-Breaker: Assessing the Security of LLMs Against Backdoor Attacks on HDL Code Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-03</span>
        <a href="https://ieeexplore.ieee.org/document/10993260" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title"><strong>UCD-Training</strong>: Unseen-Codebases-Domain Data Synthesis and Training Based on Code Graphs</div>
    <div class="paper-meta">
        <span class="paper-tag">2026-02</span>
        <a href="https://arxiv.org/abs/2602.20799" class="paper-link" target="_blank">View Paper ↗</a>
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
    <div class="paper-title"><strong>Beyond Functional Correctness</strong>: Beyond functional correctness: Investigating coding style inconsistencies in large language models</div>
    <div class="paper-meta">
        <span class="paper-tag">2024-06</span>
        <a href="https://arxiv.org/abs/2407.00456" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>
<div class="paper-card">
    <div class="paper-title"><strong>RustEvo^ 2</strong>: RustEvo^ 2: An Evolving Benchmark for API Evolution in LLM-based Rust Code Generation</div>
    <div class="paper-meta">
        <span class="paper-tag">2025-03</span>
        <a href="https://arxiv.org/abs/2503.16922" class="paper-link" target="_blank">View Paper ↗</a>
    </div>
</div>