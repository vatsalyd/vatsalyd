<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:115e59&height=200&section=header&text=VATSAL%20YADAV&fontSize=48&fontColor=5eead4&fontAlignY=35&desc=Agentic%20Systems%20%26%20Orchestration%20Layer%20Engineer&descAlignY=55&descSize=18&animation=fadeIn" width="100%"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=18&pause=1500&color=5EEAD4&background=00000000&center=true&vCenter=true&width=650&lines=Orchestrating+multi-agent+systems%2C+one+state+machine+at+a+time;LangGraph+%C2%B7+RAG+%C2%B7+Multi-Agent+Pipelines;Currently+routing+production+traffic+at+NUMAA.ai" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vatsal-yadav"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=5EEAD4"/></a>
  <a href="https://vatsalyd.github.io/Portfolio"><img src="https://img.shields.io/badge/Portfolio-0d1117?style=for-the-badge&logo=googlechrome&logoColor=5EEAD4"/></a>
  <a href="mailto:vatsal.y.official@gmail.com"><img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=5EEAD4"/></a>
  <a href="https://medium.com/@vatsal.y.official"><img src="https://img.shields.io/badge/Medium-0d1117?style=for-the-badge&logo=medium&logoColor=5EEAD4"/></a>
</p>

---

```
ORCHESTRATOR STATUS  : ONLINE
ROLE                 : Agentic Systems & Orchestration Layer Engineer
BASE                 : IIT Bhilai — B.Tech, Data Science & AI (2024–2028)  ·  GPA 7.34
ROUTING TO           : NUMAA.ai — Nutrition Agent (Production)
CONTACT              : vatsal.y.official@gmail.com
```

<br>

### `$ whoami`

Third-year Data Science & AI undergrad at **IIT Bhilai** focused on one problem: getting multiple specialized agents to behave like one coherent system instead of three confused ones talking past each other. I design the state machines, confidence-based escalation logic, and handoff protocols that sit between a user's request and a swarm of agents trying to answer it.

Currently doing this in production as an **AI/ML Intern at Incrivelsoft**, where I own the Nutrition Agent inside the **NUMAA.ai** multi-agent health platform — enforcing clinical guardrails, orchestrating inter-agent handoffs, and keeping Gemini 2.5 Flash from prescribing pizza for diabetes.

<br>

### `$ ps aux --agents`

| Agent | Status | What It Does | Stack |
|:---|:---:|:---|:---|
| **`numaa-nutrition-agent`** | 🔵 `prod` | Nutrition domain logic inside NUMAA.ai; 3-layer hybrid system (ICMR-NIN clinical engine → guideline retrieval → Gemini router); 5 FastAPI microservices | Gemini 2.5 Flash · FastAPI · Qdrant · MongoDB |
| **`context-pager`** | 🟢 `active` | MCP virtual memory for LLMs — semantically pages compressed doc slices on demand instead of dumping full documents into context; **4–10× token cost reduction** | MCP · Vector Search · FastAPI · Python |
| **`helixdesk`** | 🟢 `active` | 3-agent LangGraph state machine (Triage → Retrieval → Resolution); auto-escalates low-confidence tickets; **~1.8s avg resolution** | LangGraph · Llama-3.3-70b · ChromaDB · Docker · AWS |
| **`finsight-ai`** | 🟢 `active` | 4-stage financial pipeline (Rate Limiter → Safety Guard → Intent Classifier → Agent Router); 10 domains, 100% classification accuracy, **166ms latency** | FastAPI · SSE · yfinance |
| **`jobfit-ai`** | 🟢 `active` | 3-model resume↔JD matching (spaCy NER + XGBoost + fine-tuned SBERT); trained on 13k+ pairs across 24 job categories | XGBoost · PyTorch · SBERT · Streamlit |

**Links:**
[`context-pager`](https://github.com/vatsalyd/context_pager) ·
[`helixdesk`](https://github.com/vatsalyd/helixdesk) — [Live](https://helixdesk.onrender.com/) ·
[`finsight-ai`](https://github.com/vatsalyd/FinSightAI) ·
[`jobfit-ai`](https://github.com/vatsalyd/JobFit-AI) — [Live](http://54.211.51.42:8501/) ·
[`claimsure-ai`](https://github.com/vatsalyd/ClaimSure) ·
[`influencer-search`](https://github.com/vatsalyd/influencer-search)

<br>

### `$ cat upstream_contributions.log`

Merged PRs and issues on repositories I don't own:

| Repository | PR / Issue | Status |
|:---|:---|:---:|
| [`mlflow/mlflow`](https://github.com/mlflow/mlflow) | [Fix async trace export dropping workspace context](https://github.com/mlflow/mlflow/pull/24275) | ✅ Merged |
| [`mlflow/mlflow`](https://github.com/mlflow/mlflow) | [Support Gemini thought signature in AI Gateway](https://github.com/mlflow/mlflow/pull/24051) | ✅ Merged |
| [`mlflow/mlflow`](https://github.com/mlflow/mlflow) | [Warn when search_runs() silently truncates results](https://github.com/mlflow/mlflow/pull/22215) | ✅ Merged |
| [`ansible/ansible`](https://github.com/ansible/ansible) | [Fix role lookup from ansible-playbook cwd](https://github.com/ansible/ansible/pull/87112) | ✅ Merged |
| [`deepchem/deepchem`](https://github.com/deepchem/deepchem) | [Fix DTNNEmbedding parameter misspelled](https://github.com/deepchem/deepchem/pull/5025) | 🟡 Open |
| [`fossasia/eventyay`](https://github.com/fossasia/eventyay) | [CI tests workflow references removed path](https://github.com/fossasia/eventyay/issues/4133) | 🔴 Issue (Closed) |

> Full live feed with auto-sync → [Portfolio Open Source Section](https://vatsalyd.github.io/Portfolio/#opensource)

<br>

### `$ cat routing_table.yaml`

**orchestration_and_agents**
<p align="left">
<img src="https://img.shields.io/badge/LangGraph-134e4a?style=for-the-badge&logoColor=5EEAD4"/>
<img src="https://img.shields.io/badge/LangChain-134e4a?style=for-the-badge&logo=langchain&logoColor=5EEAD4"/>
<img src="https://img.shields.io/badge/Multi--Agent%20Systems-134e4a?style=for-the-badge&logoColor=5EEAD4"/>
<img src="https://img.shields.io/badge/RAG-134e4a?style=for-the-badge&logoColor=5EEAD4"/>
<img src="https://img.shields.io/badge/MCP-134e4a?style=for-the-badge&logoColor=5EEAD4"/>
<img src="https://img.shields.io/badge/OpenAI%20API-134e4a?style=for-the-badge&logo=openai&logoColor=5EEAD4"/>
</p>

**ml_and_deep_learning**
<p align="left">
<img src="https://img.shields.io/badge/PyTorch-134e4a?style=for-the-badge&logo=pytorch&logoColor=5EEAD4"/>
<img src="https://img.shields.io/badge/Scikit--learn-134e4a?style=for-the-badge&logo=scikitlearn&logoColor=5EEAD4"/>
<img src="https://img.shields.io/badge/XGBoost-134e4a?style=for-the-badge&logoColor=5EEAD4"/>
<img src="https://img.shields.io/badge/SBERT-134e4a?style=for-the-badge&logoColor=5EEAD4"/>
<img src="https://img.shields.io/badge/Hugging%20Face-134e4a?style=for-the-badge&logo=huggingface&logoColor=5EEAD4"/>
</p>

**infra_and_deployment**
<p align="left">
<img src="https://img.shields.io/badge/FastAPI-134e4a?style=for-the-badge&logo=fastapi&logoColor=5EEAD4"/>
<img src="https://img.shields.io/badge/Docker-134e4a?style=for-the-badge&logo=docker&logoColor=5EEAD4"/>
<img src="https://img.shields.io/badge/AWS%20EC2/ECR-134e4a?style=for-the-badge&logo=amazonaws&logoColor=5EEAD4"/>
<img src="https://img.shields.io/badge/GitHub%20Actions-134e4a?style=for-the-badge&logo=githubactions&logoColor=5EEAD4"/>
<img src="https://img.shields.io/badge/ChromaDB-134e4a?style=for-the-badge&logoColor=5EEAD4"/>
<img src="https://img.shields.io/badge/Qdrant-134e4a?style=for-the-badge&logoColor=5EEAD4"/>
<img src="https://img.shields.io/badge/MongoDB-134e4a?style=for-the-badge&logo=mongodb&logoColor=5EEAD4"/>
</p>

**languages**
<p align="left">
<img src="https://img.shields.io/badge/Python-134e4a?style=for-the-badge&logo=python&logoColor=5EEAD4"/>
<img src="https://img.shields.io/badge/C++-134e4a?style=for-the-badge&logo=cplusplus&logoColor=5EEAD4"/>
<img src="https://img.shields.io/badge/JavaScript-134e4a?style=for-the-badge&logo=javascript&logoColor=5EEAD4"/>
<img src="https://img.shields.io/badge/SQL-134e4a?style=for-the-badge&logo=mysql&logoColor=5EEAD4"/>
</p>

<br>

### `$ tail -f research.log`

Right now I'm deep in the orchestration layer itself — not what one agent can do, but how several agents *coordinate*: state handoffs that don't lose context, confidence-based escalation instead of silent failure, and sub-second routing decisions before any LLM call fires. That's the throughline across NUMAA.ai's inter-agent handoffs, HelixDesk's triage escalation, and FinSight's pre-LLM safety/intent layer — same underlying problem, three different domains.

<br>

### `$ git log --oneline`

```
2026  DEPLOY    AI/ML Intern @ Incrivelsoft — orchestrating the Nutrition Agent in NUMAA.ai's production multi-agent pipeline
2026  MERGE     4 upstream PRs merged into mlflow/mlflow and ansible/ansible
2025  SHIP      HelixDesk, FinSight AI, Context Pager, JobFit-AI — four multi-agent / ML systems, design through deploy
2025  PROMOTE   Coordinator, DSAI Club @ IIT Bhilai — ran the Meraz hackathon for 100+ participants
2024  JOIN      Core Member, DSAI Club  ·  Volunteer, Centre for Career Planning & Services
2024  INIT      Started B.Tech, Data Science & AI @ IIT Bhilai
```

<br>

### `$ curl stats.vatsalyd.dev`

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=vatsalyd&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=5EEAD4&icon_color=5EEAD4&text_color=c9d1d9" width="49%"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vatsalyd&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=5EEAD4&text_color=c9d1d9" width="38%"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=vatsalyd&theme=react-dark&hide_border=true&bg_color=0D1117&color=5EEAD4&line=5EEAD4&point=ffffff" width="90%"/>
</p>

<br>

### `$ connect()`

<p align="center">
  <a href="mailto:vatsal.y.official@gmail.com"><img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=5EEAD4"/></a>
  <a href="https://www.linkedin.com/in/vatsal-yadav"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=5EEAD4"/></a>
  <a href="https://vatsalyd.github.io/Portfolio"><img src="https://img.shields.io/badge/Portfolio-0d1117?style=for-the-badge&logo=googlechrome&logoColor=5EEAD4"/></a>
  <a href="https://github.com/vatsalyd"><img src="https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=5EEAD4"/></a>
  <a href="https://x.com/fixedbyvatsal"><img src="https://img.shields.io/badge/X-0d1117?style=for-the-badge&logo=x&logoColor=5EEAD4"/></a>
  <a href="https://leetcode.com/u/vatsalyd/"><img src="https://img.shields.io/badge/LeetCode-0d1117?style=for-the-badge&logo=leetcode&logoColor=5EEAD4"/></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:115e59,100:0f172a&height=100&section=footer" width="100%"/>
</p>
