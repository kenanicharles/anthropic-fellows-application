# Anthropic Fellows Program Application – Dr. Ken Charles

**Location:** South Africa (Remote)

## 📌 Research Proposal

**Title:** Empirical Evaluation of Safety Steering Techniques in Open-Source LLMs Across Low-Resource Languages

**Abstract:** 
Purpose: The global deployment of large language models (LLMs) is severely undermined by English-centric safety guardrails. Harmful prompts translated into low-resource languages frequently evade refusal mechanisms, creating a dangerous reliability gap. This proposal synthesizes literature across AI safety, cross-lingual NLP, and adversarial steering to propose a rigorous empirical evaluation framework for cross-lingual safety steering in open-source LLMs.
Design/methodology/approach: A systematic, empirical research design is proposed. The study will use three open-source models (Llama-3.1-8B-Instruct, Mistral-7B-Instruct-v0.3, Qwen2.5-7B-Instruct) and the SafetyPrompts benchmark. A parallel corpus of 1,000 harmful prompts will be translated into 5 languages (English, Spanish, French, Bengali, Maltese). Three safety steering techniques, baseline (no steering), standard English-only safety prompt, and explicit chain-of-thought reasoning in the target language, were tested across each condition. The study will measure Attack Success Rate (ASR), Refusal Rate, and Confidence Score as primary metrics.
Findings: The proposal identifies a fundamental safety gap: current open-source models exhibit a 20–40% drop in safety refusal rates when prompts are translated into low-resource languages. To address this, the proposed study will empirically quantify the effectiveness of three steering techniques and identify whether language representation depth (measured via tokenizer coverage and perplexity) correlates with steering failure.
Originality/value: This proposal provides the first systematic empirical evaluation of cross-lingual safety steering in open-source LLMs, directly addressing Anthropic's core mission of creating reliable, interpretable, and steerable AI systems. The findings will produce a public technical paper and an open-source evaluation pipeline.

Paper Type: Empirical Research Proposal

## 📁 Repository Structure
anthropic-fellows-application/
├── README.md
├── Research_Proposal_KenCharles.pdf
├── pilot_script/
│   └── pilot_llm_safety.py
└── preliminary_results/
    └── pilot_results.json

## 🧪 Pilot Experiment Summary   <-- THIS IS WHERE IT GOES

- **Model:** `microsoft/phi-2`
- **Languages:** English and Spanish
- **Conditions:** Baseline (no steering), English safety prompt, Chain-of-thought reasoning
- **Key result:** The pilot demonstrates measurable differences in refusal rates across conditions, validating the experimental design for the full study.

🔗 Links
- [Full Proposal PDF](Research_Proposal_KenCharles.pdf)
- [Pilot Code](pilot_script/pilot_llm_safety.py)
- [Pilot Results](preliminary_results/pilot_results.json)

## 📧 Contact

Dr. Ken Charles  
kencharles@hotmail.com
South Africa (Remote)
