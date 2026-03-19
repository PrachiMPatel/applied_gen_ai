# Applied Generative AI

**Graduate Syllabus | Spring 2025 | 3 Credits**

---

## Course Innovation & Impact

This course was designed around a single observation: **the gap in AI education is not technical skill — it is judgment.** Students graduate knowing how to build generative AI systems but lack the frameworks to evaluate, govern, or refuse to deploy them. This curriculum addresses that gap through three structural innovations:

1. **Evaluation as a First-Class Engineering Discipline.** Week 9 is dedicated entirely to LLM evaluation — automated metrics, human evaluation design, and LLM-as-a-judge frameworks. This is not an afterthought appendix; it is a core module with its own lab, exercises, and assessment weight. Students learn that building a system that produces outputs is easy; building one you can *trust* is the real challenge.

2. **Responsible AI as a Continuous Thread.** Responsible AI is not a standalone ethics lecture in Week 14. Every weekly lab includes a Responsible AI reflection that connects the technical topic to its societal implications. Students engage with bias, hallucination, safety, and governance *in the context of the systems they are building*, not in the abstract.

3. **The Judgment Memo.** Weighted at 20% — equal to the Midterm — this assessment asks students to articulate the deployment boundaries of the system they built, defend where they would choose *not* to deploy it, and identify failure modes that their evaluation suite did not catch. Knowing the limits of a system is valued as highly as building it.

---

## How This Course Uses AI

> **AI is not just the subject of this course — it is the pedagogy.**

| Dimension | How AI Is Applied |
|-----------|-------------------|
| **Assessment** | Students build LLM-as-a-judge pipelines in Week 9, then apply that same methodology to evaluate their own final projects |
| **Research** | Week 2 teaches AI-assisted academic research (ChatGPT Deep Research, Claude, Gemini) with verification workflows — students apply these skills all semester |
| **Lab Scaffolding** | Progressive TODO-based exercises where students verify and extend AI-generated starter code, learning to critically assess AI outputs |
| **Ethical Reasoning** | Every notebook shifts students from "Can I build this?" to "Should I deploy this?" through structured Responsible AI reflections |
| **Transparency** | Students use AI tools openly with mandatory disclosure, modeling responsible AI use in professional practice |

---

## Pedagogical Philosophy

This course is built on a single conviction: in generative AI, **technical capability and ethical judgment are inseparable**. You cannot build trustworthy AI systems without understanding both how they work and where they fail — and you cannot responsibly deploy them without the judgment to know when they should not be used at all.

Every technical module is paired with a responsible AI lens. Evaluation is treated not as an afterthought but as a first-class engineering discipline. The Judgment Memo asks you to do something harder than writing code: to articulate the boundaries of what you built, and to defend where you would choose not to deploy it.

---

## Course Description

This graduate-level course provides a rigorous, hands-on introduction to Generative AI — from foundational LLM architecture to the design of production-grade agentic systems. Students move beyond prompt engineering into AI-assisted research, fine-tuning, retrieval-augmented generation (RAG), systematic model evaluation, multimodal AI, deep research agents, and autonomous agent orchestration using modern frameworks.

A defining feature is the emphasis on evaluation as an engineering discipline. Building a system that produces outputs is easy. Building one you can trust — and knowing the limits of that trust — is the real challenge. Students learn to evaluate model outputs using benchmarks, human evaluation protocols, and LLM-as-a-judge frameworks, and connect those results directly to deployment decisions.

---

## Learning Outcomes

By the end of this course, students will be able to:

- Use AI tools for rigorous academic research with verification workflows and citation integrity
- Design and implement end-to-end generative AI pipelines including RAG, fine-tuning, and multi-agent systems
- Fine-tune open-source LLMs using parameter-efficient methods (LoRA, QLoRA) for domain-specific tasks
- Build agentic AI applications using LangChain, LangGraph, and tool-calling frameworks
- Design and deploy deep research agents and reasoning/planning agents
- Evaluate model outputs rigorously using benchmarks, human evaluation, and LLM-as-a-judge pipelines — identifying hallucinations, failure modes, and performance boundaries
- Design domain-specific evaluation suites and connect results to deployment decisions
- Apply responsible AI frameworks including bias auditing and governance to real-world deployment decisions
- Communicate the capabilities and limitations of AI systems to technical and non-technical stakeholders

---

## Course Schedule

The course runs 15 weeks. Week 9 is dedicated to LLM evaluation — a topic typically under-served in GenAI curricula. Responsible AI themes appear explicitly in Weeks 4 and 14 and are woven throughout every module.

| Wk | Topic | Key Concepts | Responsible AI Touchpoint | Notebook(s) |
|----|-------|-------------|--------------------------|-------------|
| 1 | **Foundations of Generative AI** | Transformer architecture, attention mechanisms, tokenization, generative AI landscape. What LLMs can and cannot do. | What LLMs should vs. should not do | [Week_01](notebooks/Week_01_Foundations_of_Generative_AI.ipynb) |
| 2 | **AI for Academic Research** | Using deep research tools (ChatGPT, Claude, Gemini) for literature review, synthesis, and research. Verification workflows, citation integrity, academic honesty. | False confidence in AI-generated research; citation hallucination | [Week_02](notebooks/Week_02_AI_for_Academic_Research.ipynb) |
| 3 | **Prompt Engineering** | Zero-shot, few-shot, chain-of-thought prompting. Prompt design patterns, system prompts, structured outputs. | Prompt injection, manipulation risks | [Week_03](notebooks/Week_03_Prompt_Engineering.ipynb) |
| 4 | **Responsible AI: Foundations** | Bias, hallucination, safety, fairness. Frameworks for harm and accountability. The Judgment Memo introduced. | *Dedicated module* | [Week_04](notebooks/Week_04_Responsible_AI_Foundations.ipynb) |
| 5 | **LLM APIs & Production Use** | OpenAI, Anthropic, open-source APIs. Rate limits, cost, latency, reliability. Data privacy and governance. | Data governance, vendor transparency | [Week_05](notebooks/Week_05_LLM_APIs_and_Production.ipynb) |
| 6 | **Fine-Tuning** | When and why to fine-tune. LoRA, QLoRA. Dataset curation. Hands-on fine-tuning with experiment tracking. | Bias amplification in fine-tuned models | [Week_06a](notebooks/Week_06a_Fine_Tuning_Theory.ipynb), [Week_06b](notebooks/Week_06b_Fine_Tuning_Practice.ipynb) |
| 7 | **Retrieval-Augmented Generation** | Vector databases, embedding models, chunking strategies, hybrid search. Production RAG pipelines. | When RAG is not the right tool | [Week_07](notebooks/Week_07_RAG.ipynb) |
| 8 | **Advanced RAG & Debugging** | Re-ranking, query transformation, multi-hop retrieval. RAG evaluation with RAGAS. Debugging retrieval failures. | Hallucination in RAG, attribution | [Week_08](notebooks/Week_08_Advanced_RAG.ipynb) |
| 9 | **LLM Evaluation & Judgment** | Benchmarks, human evaluation, LLM-as-a-judge frameworks. Eval suite design. Failure mode taxonomy. Calibrated uncertainty. | Evaluation itself as responsible practice | [Week_09a](notebooks/Week_09a_LLM_Evaluation_Metrics.ipynb), [Week_09b](notebooks/Week_09b_LLM_as_Judge.ipynb) |
| 10 | **Agentic AI I: Foundations** | Tool use, function calling, memory, planning. Introduction to LangChain. Safety in agentic design. | Unintended autonomous actions | [Week_10](notebooks/Week_10_Agentic_AI_Foundations.ipynb) |
| 11 | **Agentic AI II: LangGraph** | Stateful multi-step agents. Graph-based orchestration, conditional routing, human-in-the-loop design. | Human oversight in agent loops | [Week_11](notebooks/Week_11_Agentic_AI_LangGraph.ipynb) |
| 12 | **Multi-Agent Systems & Deep Agents** | Multi-agent architectures. Deep research agents. Reasoning and planning agents with ReAct. Self-reflection and error recovery. | Unbounded autonomy, trust verification | [Week_12a](notebooks/Week_12a_Multi_Agent_Systems.ipynb), [Week_12b](notebooks/Week_12b_Deep_Research_Agents.ipynb), [Week_12c](notebooks/Week_12c_Reasoning_Planning_Agents.ipynb) |
| 13 | **Multimodal AI** | Vision-language models, audio-language models, multimodal pipelines. Evaluation for multimodal outputs. | Bias in visual models, accessibility | [Week_13](notebooks/Week_13_Multimodal_AI.ipynb) |
| 14 | **Responsible AI & Governance** | Bias auditing, red-teaming, AI policy landscape, institutional governance. The limits of automation. | *Dedicated module* | [Week_14](notebooks/Week_14_Responsible_AI_Governance.ipynb) |
| 15 | **Final Project Presentations** | Student presentations. Peer review. Judgment Memos discussed as a cohort. Course retrospective. | Cohort reflection | — |

---

## Assessment & Grading

Grading evaluates both technical competence and responsible AI judgment. The Judgment Memo is weighted at 20% — equal to the Midterm — reflecting the conviction that knowing the limits and risks of a system is as important as building it.

| Component | Weight | Description |
|-----------|--------|-------------|
| Weekly Labs | 20% | Hands-on coding exercises for each lecture. Graded on completion, code quality, and a brief written reflection connecting technical choices to responsible AI considerations. |
| Midterm Project | 20% | Build and evaluate a fine-tuned or RAG-based system. Report must include performance analysis, failure mode documentation, and a clear evaluation methodology section. |
| Responsible AI Assignments (x3) | 15% | Structured analysis of real-world AI failures and governance frameworks. Each targets a different domain: bias, safety, and institutional accountability. |
| Final Project — Technical | 25% | End-to-end generative AI application demonstrating mastery of course concepts. Must include a rigorous evaluation suite (automated + human or LLM-as-judge). |
| Final Project — Judgment Memo | 20% | Written reflection on deployment boundaries, failure modes, and ethical considerations of the final system. Evaluated on depth of reasoning, not just completion. |

---

## Responsible AI: A Core Thread

This course treats responsible AI not as a standalone module but as a continuous thread woven through every technical topic. Students engage with the ethical, social, and institutional dimensions of each technology studied.

- **Hallucination and calibrated uncertainty** — when to trust model outputs and how to design evaluations that surface failures
- **Bias in training data, embeddings, and fine-tuned models**
- **Safety in agentic systems** — preventing unintended autonomous actions
- **Transparency and explainability** in AI-assisted decisions
- **Institutional governance**: policies, auditing, and accountability frameworks
- **The limits of automation** — decisions that should remain human
- **Citation integrity** — verifying AI-generated research claims and references

---

## Module Spotlight: LLM Evaluation (Week 9)

Evaluation is one of the most underrated and undertaught skills in applied AI. This dedicated module covers the full evaluation stack:

- Automated metrics and standard benchmarks (MMLU, HellaSwag, BIG-Bench)
- Human evaluation design — annotation guidelines, inter-rater reliability, and bias in human judges
- LLM-as-a-judge frameworks — when and why they work, failure modes, and calibration against human judgment
- Building custom eval suites for domain-specific tasks
- Connecting evaluation results to deployment decisions and failure thresholds

**Lab:** Students build an end-to-end LLM-as-judge pipeline, including judge prompt design, scoring rubric development, and analysis of judge disagreement patterns.

---

## Module Spotlight: AI for Academic Research (Week 2)

Placed early in the course so students apply AI research skills to their own academic work for the entire semester. This module teaches:

- Using deep research tools (ChatGPT Deep Research, Claude, Gemini, Perplexity, Elicit) for literature review and synthesis
- Verification workflows for AI-generated citations — identifying hallucinated references
- Cross-validating research findings across multiple AI tools
- Academic integrity and disclosure practices for AI-assisted research
- When AI research tools help vs. when they create false confidence

**Lab:** Students investigate the same research question with 2-3 different AI research tools, compare outputs, identify hallucinated citations, and produce a verified research brief.

---

## Tools & Frameworks

| Category | Tools & Frameworks |
|----------|-------------------|
| Languages & Libraries | Python, PyTorch, Hugging Face Transformers, LangChain, LangGraph |
| Fine-Tuning | LoRA / QLoRA via PEFT, WandB for experiment tracking |
| RAG & Vector Search | FAISS, ChromaDB, LlamaIndex |
| Evaluation | RAGAS, OpenAI Evals, custom LLM-as-judge pipelines |
| AI Research Tools | ChatGPT Deep Research, Claude, Gemini, Perplexity, Elicit, Semantic Scholar |
| APIs | OpenAI, Anthropic Claude, Google Gemini, open-source models via HuggingFace Hub |
| Cloud / Compute | Google Colab (free tier sufficient for all labs), GitHub |

---

## AI-Integrated Pedagogy

This course does not merely teach AI — it uses AI as a pedagogical tool:

**AI-Assisted Research (Week 2):** Students learn to use deep research tools for academic work with rigorous verification practices. They apply these skills to literature reviews and research for the entire semester, developing critical evaluation habits from day one.

**LLM-as-Judge for Assessment (Week 9):** Students build LLM-as-judge evaluation pipelines, then apply that same methodology to evaluate their own final projects. This creates a feedback loop where the technical skill (building evaluators) directly serves the assessment process.

**Progressive Lab Scaffolding:** Weekly labs use TODO-based exercises where students build on AI-generated starter code. This teaches a critical professional skill: verifying, extending, and critically assessing AI-generated outputs rather than accepting them uncritically.

**Transparent AI Use Policy:** Students may use AI tools with mandatory disclosure. This models responsible professional practice and creates a semester-long dataset of how AI tools are actually used in learning — itself a contribution to AI education research.

---

## Open Curriculum & Reproducibility

This syllabus and all accompanying materials are shared publicly to support open curriculum development in Applied Generative AI education.

**What is shared openly:**
- This syllabus (CC BY 4.0)
- 18 executable Jupyter notebooks covering all 14 content weeks
- 5 supplementary deep-dive notebooks
- An [Instructor Adaptation Guide](INSTRUCTOR_GUIDE.md) with module dependencies, pacing options, and customization guidance

**Zero-infrastructure requirement:** Every notebook runs on Google Colab's free tier. No institutional GPUs, cloud accounts, or special infrastructure needed. Any instructor can fork this curriculum and teach it tomorrow.

**Designed for adaptation:** Modules are independent where possible. The Instructor Guide provides 15-week, 8-week, and 4-week pacing options. Domain-specific customization guidance covers healthcare, law, finance, and education.

Instructors at other institutions are encouraged to fork, modify, and build on this curriculum with attribution.

---

## Course Policies

### AI Use Policy

Students may use AI tools (including LLMs) to assist with coding, drafting, and ideation. **All AI-assisted work must be disclosed** with a brief note describing how the tool was used. Students are fully responsible for the accuracy, integrity, and reasoning of all submitted work. Using AI to complete Judgment Memos without genuine personal reflection defeats the purpose of the assignment and will be treated as academic dishonesty.

### Academic Integrity

All work submitted must reflect the student's own understanding. Code copied from external sources must be cited. Collaboration is encouraged in lab sessions; individual assignments must be completed independently unless otherwise specified.

### Accessibility

Students requiring academic accommodations should contact the university's Disability Services and notify the instructor within the first two weeks of the semester. We are committed to making this course accessible to all students.

---

## About the Instructor

**Prachi Patel, PhD** bridges neuroscience research, industry AI, and education.

**Research:** PhD in Electrical Engineering, where she spent six years applying machine learning and signal processing to uncover the neural mechanisms of human speech processing. Peer-reviewed publications in *Current Biology*, *Journal of Neuroscience*, and *Cell Reports*.

**Industry:** Amazon (wearable physiological AI, 3 patents), Microsoft (empathetic LLM prompting, 1 patent), Lightbird (conversational AI, ASR fine-tuning), Splunk/Cisco (agentic security AI, 1 patent). Incoming Senior Applied Scientist at Microsoft on the GitHub Copilot team.

**Teaching:** University instructor since 2017 across Brain-Computer Interfaces, Sensory Neuroscience, and Physics and Technologies of the Future. Selected as Lead Teaching Fellow (2019-2020) among the doctoral cohort. Developed and delivered AI and neuroscience curriculum for high school students from underserved communities through the BRAINyac program.

---

**Prachi Patel | pmpatel4593@gmail.com**

*This curriculum is shared under CC BY 4.0. Instructors are encouraged to adapt with attribution.*
