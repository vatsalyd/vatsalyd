<p align="center">
  <img src="https://raw.githubusercontent.com/vatsalyd/vatsalyd/main/assets/banner.svg" width="100%" alt="Vatsal Yadav"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vatsal-yadav"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=flat-square&logo=linkedin&logoColor=2DD4BF" alt="LinkedIn"/></a>
  <a href="https://vatsalyd.github.io/Portfolio"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=flat-square&logo=google-chrome&logoColor=2DD4BF" alt="Portfolio"/></a>
  <a href="mailto:vatsal.y.official@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=flat-square&logo=gmail&logoColor=2DD4BF" alt="Email"/></a>
  <a href="https://medium.com/@vatsal.y.official"><img src="https://img.shields.io/badge/Medium-0D1117?style=flat-square&logo=medium&logoColor=2DD4BF" alt="Medium"/></a>
  <a href="https://x.com/fixedbyvatsal"><img src="https://img.shields.io/badge/X-0D1117?style=flat-square&logo=x&logoColor=2DD4BF" alt="X"/></a>
  <a href="https://github.com/vatsalyd"><img src="https://img.shields.io/badge/GitHub-0D1117?style=flat-square&logo=github&logoColor=2DD4BF" alt="GitHub"/></a>
  <a href="https://leetcode.com/u/vatsalyd/"><img src="https://img.shields.io/badge/LeetCode-0D1117?style=flat-square&logo=leetcode&logoColor=2DD4BF" alt="LeetCode"/></a>
</p>

```
STATUS   : PRODUCTION_ACTIVE
ROLE     : AI Systems & Infrastructure Engineer
BASE     : IIT Bhilai — B.Tech, Data Science & AI (2024–2028, GPA 8/10)
CONTACT  : vatsal.y.official@gmail.com · +91 7983709173
```

---

### `$ whoami`

Undergrad at IIT Bhilai focused on backend AI systems and multi-agent coordination. I build the state machines, confidence-gated handoffs, and deterministic routing DAGs that sit between client requests and agent swarms.

- **Current**: AI/ML Intern at **Incrivelsoft**, owning the Nutritionist Lite Agent in the **NUMAA.ai** multi-agent platform (3-layer hybrid: ICMR-NIN clinical rules, Qdrant retrieval, Gemini 2.5 Flash router).
- **Core Focus**: Sub-second agent routing, MCP virtual memory paging for document context, and production latency optimization.

---

### `$ ps aux --systems`

| System | Description | Stack | Status |
|:---|:---|:---|:---:|
| [**`numaa-nutrition-agent`**](https://numaa.ai) | Clinical domain engine inside NUMAA.ai; 5 FastAPI microservices; token-bucket rate limiter (300 RPM) | Gemini 2.5 · FastAPI · Qdrant · MongoDB | `prod` |
| [**`context-pager`**](https://github.com/vatsalyd/context_pager) | MCP virtual memory for LLMs — pages compressed doc slices on demand (4–10x token reduction) | MCP · Vector Search · FastAPI · Python | `active` |
| [**`helixdesk`**](https://github.com/vatsalyd/helixdesk) | 3-agent LangGraph state machine (Triage → Retrieval → Resolution) with Llama-3.3-70b (~1.8s latency) | LangGraph · ChromaDB · FastAPI · Docker · AWS | `active` |
| [**`finsight-ai`**](https://github.com/vatsalyd/FinSightAI) | 4-stage financial pipeline (Rate Limiter → Safety Guard → Intent Classifier → Router) | FastAPI · SSE · yfinance · Python | `active` |
| [**`jobfit-ai`**](https://github.com/vatsalyd/JobFit-AI) | 3-model resume-JD matching engine (spaCy NER + XGBoost + fine-tuned SBERT on 13k+ pairs) | XGBoost · PyTorch · SBERT · Streamlit | `active` |
| [**`claimsure-ai`**](https://github.com/vatsalyd/ClaimSure) | Insurance claim verification agent with multi-modal OCR invoice intake and validation gates | Python · Document OCR · FastAPI | `active` |

<details>
<summary>Additional Repositories</summary>

| Project | Overview | Stack |
|:---|:---|:---|
| [**influencer-search**](https://github.com/vatsalyd/influencer-search) | Creator discovery platform with multi-dimensional filtering | React 19 · TypeScript · Vite · Framer Motion |
| [**ReAct Paper Implementation**](https://github.com/vatsalyd/ReAct-Paper-Implementation) | From-scratch ReAct (ICLR 2023) autonomous Thought-Action-Observation loop | Python · LangChain · Groq |
| [**RawAccel-Studio**](https://github.com/vatsalyd/RawAccel-Studio) | ML pipeline predicting mouse acceleration curves from telemetry | Python · Scikit-learn · Curve Fitting |
| [**AI-OCR Receipt Extraction**](https://github.com/vatsalyd/AI-OCR-Receipt-Extraction) | 4-stage computer vision and NER pipeline for structured receipt parsing | OpenCV · Tesseract · NER · Python |
| [**PGAGI Screening Portal**](https://github.com/vatsalyd/AI-powered-role-based-candidate-screening-system) | Role-based technical interview simulator and evaluation engine | LLMs · Prompt Engineering · FastAPI |
| [**Maven**](https://github.com/vatsalyd/Maven) | Local desktop assistant with AES-256 encrypted smart field autofill | Python · Windows API · Security |
| [**ShiftSync**](https://github.com/vatsalyd/ShiftSync) | Cross-platform shift scheduling application with real-time state sync | React Native · Expo · TypeScript |

</details>

---

### `$ cat upstream_contributions.log`

<!-- START_SECTION:activity -->
| Repository | Contribution / Pull Request | Status |
|:---|:---|:---:|
| [`kubeflow/pipelines`](https://github.com/kubeflow/pipelines) | [test(sdk): add unit tests for CLI experiment, recurring_run, diagnose_me, and __main__ modules](https://github.com/kubeflow/pipelines/pull/14200) | `open` |
| [`deepchem/deepchem`](https://github.com/deepchem/deepchem) | [fix(imports): use explicit relative imports for Pylance/Pyright namespace recognition — Closes #5117](https://github.com/deepchem/deepchem/pull/5118) | `open` |
| [`dsai-iitbhilai/dsai-foundry`](https://github.com/dsai-iitbhilai/dsai-foundry) | [feat: add leaderboard and recognition system](https://github.com/dsai-iitbhilai/dsai-foundry/pull/4) | `merged` |
| [`dsai-iitbhilai/dsai-foundry`](https://github.com/dsai-iitbhilai/dsai-foundry) | [chore: add PR template and issue templates](https://github.com/dsai-iitbhilai/dsai-foundry/pull/3) | `merged` |
| [`dsai-iitbhilai/dsai-foundry`](https://github.com/dsai-iitbhilai/dsai-foundry) | [feat: add category folders and entry templates](https://github.com/dsai-iitbhilai/dsai-foundry/pull/2) | `merged` |
| [`dsai-iitbhilai/dsai-foundry`](https://github.com/dsai-iitbhilai/dsai-foundry) | [docs: add root README, CONTRIBUTING guide, and MIT LICENSE](https://github.com/dsai-iitbhilai/dsai-foundry/pull/1) | `merged` |
<!-- END_SECTION:activity -->

---

### `$ cat activity_graph`

<p align="center">
  <img src="https://raw.githubusercontent.com/vatsalyd/vatsalyd/main/assets/github-contribution-grid-snake.svg" width="100%" alt="GitHub Contribution Graph"/>
</p>

---

### `$ cat routing_table.yaml`

```yaml
orchestration : [LangGraph, LangChain, Multi-Agent Systems, MCP, RAG, Function Calling]
machine_learning: [PyTorch, Scikit-learn, XGBoost, Sentence-BERT, Hugging Face, spaCy]
infrastructure: [FastAPI, Docker, AWS EC2/ECR, GitHub Actions, Qdrant, ChromaDB, MongoDB]
languages     : [Python, C++, TypeScript, JavaScript, SQL, Bash]
```

---

### `$ cat published_notes.md`

- [**Your AI Agent Is Reading the Whole Book. You're Paying for Every Word**](https://medium.com/@vatsal.y.official/your-ai-agent-is-reading-the-whole-book-youre-paying-for-every-word-1193f3dec6df)  
  Token cost optimization via virtual memory and semantic page indexing with Context Pager.
- [**I Refactored My AI Agent System and Deleted Half the Complexity**](https://medium.com/@vatsal.y.official/i-refactored-my-ai-agent-system-and-deleted-half-the-complexity-heres-what-i-changed-and-why-687154b1602f)  
  Flattening multi-agent state machines into explicit deterministic routing DAGs.
- [**I Built a Pregnancy Nutrition AI at My Internship — The LLM Was the Last Thing I Worried About**](https://medium.com/@vatsal.y.official/i-built-a-pregnancy-nutrition-ai-at-my-internship-the-llm-was-the-last-thing-i-worried-about-7c9200fd1782)  
  Clinical safety guardrails, state handoffs, and medical quality loops in production.

---

### `$ connect`

```
email    : vatsal.y.official@gmail.com
web      : https://vatsalyd.github.io/Portfolio
github   : https://github.com/vatsalyd
linkedin : https://linkedin.com/in/vatsal-yadav
x        : https://x.com/fixedbyvatsal
```
