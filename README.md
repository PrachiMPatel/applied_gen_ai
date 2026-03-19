# Applied Generative AI

### Graduate Course | Applied Generative AI

**A course that treats evaluation and responsible AI as first-class engineering disciplines and not afterthoughts.**

---

## Why This Course Exists

Most generative AI courses teach students to build systems. This one teaches them to **evaluate, govern, and know when not to deploy them**. The gap in AI education is not technical skill, it is judgment.

---

## Three Pillars

### 1. Evaluation-First Pedagogy
Week 9 is dedicated entirely to LLM evaluation: automated metrics, human evaluation design, and LLM-as-a-judge frameworks. Students don't just build systems, instead, they build the tools to measure whether those systems should be trusted.

### 2. Responsible AI as a Continuous Thread
Every weekly lab includes a Responsible AI reflection connecting technical work to societal impact. This is not a standalone ethics lecture but it is woven into every module from tokenization to multi-agent systems.

### 3. The Judgment Memo
Weighted at 20% (equal to the Midterm), this assessment asks students to defend the deployment boundaries of their system and articulate where they would choose *not* to deploy it. Knowing the limits of a system is valued as highly as building it.

---

## Curriculum Map

| Week | Module | Notebooks | Responsible AI Focus |
|------|--------|-----------|---------------------|
| 1 | Foundations of Generative AI | [Week 01](notebooks/Week_01_Foundations_of_Generative_AI.ipynb) | What LLMs should vs. should not do |
| 2 | AI for Academic Research | [Week 02](notebooks/Week_02_AI_for_Academic_Research.ipynb) | Citation integrity, false confidence |
| 3 | Prompt Engineering | [Week 03](notebooks/Week_03_Prompt_Engineering.ipynb) | Prompt injection and manipulation |
| 4 | Responsible AI: Foundations | [Week 04](notebooks/Week_04_Responsible_AI_Foundations.ipynb) | **Dedicated module** |
| 5 | LLM APIs & Production | [Week 05](notebooks/Week_05_LLM_APIs_and_Production.ipynb) | Data governance, vendor transparency |
| 6 | Fine-Tuning | [Theory](notebooks/Week_06a_Fine_Tuning_Theory.ipynb) / [Practice](notebooks/Week_06b_Fine_Tuning_Practice.ipynb) | Bias amplification |
| 7 | RAG | [Week 07](notebooks/Week_07_RAG.ipynb) | When RAG is not the right tool |
| 8 | Advanced RAG & Debugging | [Week 08](notebooks/Week_08_Advanced_RAG.ipynb) | Hallucination in RAG, attribution |
| 9 | LLM Evaluation | [Metrics](notebooks/Week_09a_LLM_Evaluation_Metrics.ipynb) / [LLM-as-Judge](notebooks/Week_09b_LLM_as_Judge.ipynb) | Evaluation as responsible practice |
| 10 | Agentic AI: Foundations | [Week 10](notebooks/Week_10_Agentic_AI_Foundations.ipynb) | Unintended autonomous actions |
| 11 | Agentic AI: LangGraph | [Week 11](notebooks/Week_11_Agentic_AI_LangGraph.ipynb) | Human oversight in agent loops |
| 12 | Multi-Agent & Deep Agents | [Multi-Agent](notebooks/Week_12a_Multi_Agent_Systems.ipynb) / [Deep Research](notebooks/Week_12b_Deep_Research_Agents.ipynb) / [Reasoning](notebooks/Week_12c_Reasoning_Planning_Agents.ipynb) | Unbounded autonomy, trust |
| 13 | Multimodal AI | [Week 13](notebooks/Week_13_Multimodal_AI.ipynb) | Bias in visual models, accessibility |
| 14 | Responsible AI & Governance | [Week 14](notebooks/Week_14_Responsible_AI_Governance.ipynb) | **Dedicated module** |
| 15 | Final Presentations | — | Cohort reflection |

---

## Quick Start

### For Students

Every notebook runs on Google Colab with no setup required.

1. Click any notebook link above
2. Open in Google Colab (badge at top of each notebook)
3. Run cells sequentially
4. Complete the exercises and Responsible AI reflections


**Pacing options:** 15-week semester, 8-week intensive, or 4-week workshop.

---

## What Makes This Course Different

| Feature | Typical GenAI Course | This Course |
|---------|---------------------|-------------|
| Evaluation | Brief mention in final weeks | Dedicated Week 9 module with full lab |
| Responsible AI | Standalone ethics lecture | Reflection embedded in every weekly lab |
| Assessment of judgment | Not assessed | Judgment Memo at 20% (equal to Midterm) |
| AI for research | Not taught | Week 2 — applied all semester |
| Deep agents | Surface-level demo | Three dedicated notebooks (Week 12) |
| Reproducibility | Requires institutional infra | Every notebook runs on free Google Colab |
| Adaptability | Fixed curriculum | Instructor Guide with 3 pacing formats |

---

## Supplementary Materials

Deep-dive notebooks for additional exploration:

| Notebook | Topic | Supports |
|----------|-------|----------|
| [Probability Foundations](notebooks/supplementary/Supplementary_Probability_Foundations.ipynb) | Bayesian reasoning, posterior updates | Week 1 |
| [Word Sampling & N-grams](notebooks/supplementary/Supplementary_Word_Sampling_Ngrams.ipynb) | Bigram models, text generation | Week 1 |
| [Word Embeddings](notebooks/supplementary/Supplementary_Word_Embeddings.ipynb) | spaCy embeddings, similarity | Week 1 |
| [Transformer/GPT from Scratch](notebooks/supplementary/Supplementary_Transformer_GPT_From_Scratch.ipynb) | Full GPT implementation in PyTorch | Week 1 |
| [Seq2Seq Translation](notebooks/supplementary/Supplementary_Seq2Seq_Translation.ipynb) | T5 translation pipeline | Week 6 |

---

## About the Instructor

**Prachi Patel, PhD, Columbia University**

Prachi bridges neuroscience research, industry AI, and education. Her PhD applied machine learning to human speech processing (publications in *Current Biology*, *Journal of Neuroscience*, *Cell Reports*). Her industry career spans Amazon, Microsoft and Splunk/Cisco (5 patents across wearable AI, empathetic LLMs, conversational AI, and agentic security). She is a Senior Applied Scientist on the GitHub Copilot team at Microsoft.

She has taught at the university level since 2017 and was selected as Lead Teaching Fellow among the Columbia University doctoral cohort. Through the BRAINyac program, she develops AI curriculum for high school students from underserved communities.

---

## License

This curriculum is shared under **CC BY 4.0**. Instructors are encouraged to adapt with attribution.

**Prachi Patel | pmpatel4593@gmail.com**
