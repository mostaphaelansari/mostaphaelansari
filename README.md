<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Mostapha%20El%20Ansari&fontSize=50&fontColor=fff&fontAlignY=55&desc=Machine%20Learning%20Engineer&descSize=18&descAlignY=75&descColor=aaaaaa&animation=twinkling" width="100%"/>

<br/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Space+Mono&weight=700&size=14&duration=2800&pause=1200&color=00E5FF&center=true&vCenter=true&width=650&height=45&lines=Production+LLM+systems+that+hold+under+real+load.;RAG+pipelines+from+architecture+to+deployment.;Agents+that+act+%E2%80%94+with+guardrails.;MLOps%3A+train%2C+promote%2C+serve%2C+monitor.;Re-implementing+papers+because+using+%E2%89%A0+understanding.)](https://git.io/typing-svg)

</div>

<br/>

<table>
<tr>
<td width="55%" valign="top">

### About

Machine Learning Engineer working on language models, computer vision, and the software engineering that gets them into production.

**Currently:**
- Building **ScoreFlow** — credit-risk scoring with explainable decisions and drift monitoring
- Local AI agents that operate real infrastructure (Kubernetes, browsers, code review)
- MLOps pipelines: automated model promotion, Kubeflow, MLflow
- Fine-tuning LLMs with LoRA/QLoRA and first-principles paper re-implementations

</td>
<td width="45%" valign="top" align="center">

```
┌─────────────────────────────┐
│  mostapha@workstation:~$    │
│  > location  : Fez, Morocco │
│  > focus     : LLMs · MLOps │
│  > method    : from scratch │
│  > status    : building ██▒ │
└─────────────────────────────┘
```

[![](https://img.shields.io/badge/elansarimostapha.ai-000?style=for-the-badge&logo=firefox&logoColor=00e5ff)](https://elansarimostapha.ai)
[![](https://img.shields.io/badge/LinkedIn-000?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](https://linkedin.com)
[![](https://img.shields.io/badge/HuggingFace-000?style=for-the-badge&logo=huggingface&logoColor=FFD21F)](https://huggingface.co)
[![](https://img.shields.io/badge/Kaggle-000?style=for-the-badge&logo=kaggle&logoColor=20BEFF)](https://kaggle.com)
[![](https://img.shields.io/badge/Medium-000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com)

</td>
</tr>
</table>

---

## Projects

> Each one is a system, not a script. Built to understand, not to show.

<br/>

### Featured

| # | Project | Category | Description | Stack |
|---|---------|----------|-------------|-------|
| 01 | 📊 **[ScoreFlow](https://github.com/mostaphaelansari/ScoreFlow)** | `Credit Risk` | Credit-scoring toolkit for regulated environments. Trains and selects models on AUC/KS, then adds risk bands, reason codes, PSI drift monitoring, and HTML evaluation reports. Served via REST API or batch export. | Python · LightGBM · scikit-learn · FastAPI · pytest · GitHub Actions |
| 02 | 🩺 **[PodMedic](https://github.com/mostaphaelansari/PodMedic)** | `Agents` | Local AI agent that watches a Kubernetes cluster, investigates failing pods, explains root causes, and proposes fixes. Remediation is gated behind human approval. No API keys, fully local. | Python · Kubernetes client · Ollama · kind |
| 03 | 🛡️ **[CV Guardian](https://github.com/mostaphaelansari/The-CV-Guardian-)** | `Security · NLP` | Scans uploaded résumés for malicious links, injection payloads (SQL, XSS, prompt), embedded PDF scripts, and AI-generated text before they reach a hiring pipeline. [Live demo →](https://the-cv-guardian.vercel.app) | Node.js · Express · Flask · DeBERTa v3 · MongoDB · Docker |
| 04 | 🔎 **[Diff-First Review Agent](https://github.com/mostaphaelansari/Feature-to-Production-Autonomous-Flow)** | `Agents · DevOps` | Autonomous code-review agent that analyzes diffs semantically, scores risk, and approves, blocks, or tags changes. Includes security regression and architecture-drift checks. | Python · JSON Schema · GitLab CI |
| 05 | 🚀 **[MLOps Auto Model Promotion](https://github.com/mostaphaelansari/mlops-auto-model-promotion)** | `MLOps` | Full churn-model lifecycle: training with schema validation, gated staging → production promotion with rollback, and a serving API with auto-reload and A/B testing. | MLflow · scikit-learn · Flask · Docker Compose |
| 06 | 🔍 **[RAG System](https://github.com/mostaphaelansari/Optimization-and-Deployment-of-a-Retrieval-Augmented-Generation-RAG-System-)** | `RAG` | Offline PDF Q&A with local inference and zero cloud dependency. Semantic retrieval over research papers with grounded answers, via CLI or web UI. | LangChain · ChromaDB · Ollama · Streamlit · Docker |

### More

| Project | Category | Description |
|---------|----------|-------------|
| 🌐 **[Bedrock Browser Agent](https://github.com/mostaphaelansari/browser-agent)** | `Agents` | Multi-agent orchestrator on Amazon Bedrock that routes tool calls to a Playwright browser agent. |
| 💳 **[Kubeflow Fraud Detection](https://github.com/mostaphaelansari/Kubeflow-Pipelines-on-Kubernetes-Credit-Card-Fraud-Detection)** | `MLOps` | Four-stage Kubeflow pipeline (ingest → features → train → evaluate) on a local Kubernetes cluster. |
| 🕸️ **[Markov-GNN Dynamics](https://github.com/mostaphaelansari/Markov-GNN-Dynamics)** | `Research` | Graph Neural Network that learns local transition rules of diffusion processes on networks. |
| 📄 **[LLM Document Q&A](https://github.com/mostaphaelansari/LLM-Powered-Document-Q-A-with-Llama-3.2)** | `LLM` | Multi-document reasoning on Llama 3.2 across heterogeneous formats. |
| 🗄️ **[Text-to-SQL](https://github.com/mostaphaelansari/Text2SQL)** | `NLP` | Natural language → SQL with schema-aware prompting and a self-correction loop. |
| 📚 **[Semantic Book Recommender](https://github.com/mostaphaelansari/Semantic-Book-Recommender)** | `NLP` | Embeddings combined with emotion-aware filtering at query time. |

> 🧠 Also building privately: **ML papers from scratch** (Transformers, ResNet, BERT from the equations) and **ML/DL algorithms in pure NumPy**, with no scikit-learn and no autograd.

<br/>

---

## Stack

<div align="center">

**Core ML**

![PyTorch](https://img.shields.io/badge/PyTorch-111?style=flat-square&logo=pytorch&logoColor=EE4C2C)&nbsp;
![HuggingFace](https://img.shields.io/badge/HuggingFace-111?style=flat-square&logo=huggingface&logoColor=FFD21F)&nbsp;
![LangChain](https://img.shields.io/badge/LangChain-111?style=flat-square&logoColor=white)&nbsp;
![LoRA](https://img.shields.io/badge/LoRA%20%2F%20QLoRA-111?style=flat-square&logoColor=00e5ff)&nbsp;
![ChromaDB](https://img.shields.io/badge/ChromaDB-111?style=flat-square&logoColor=white)&nbsp;
![FAISS](https://img.shields.io/badge/FAISS-111?style=flat-square&logoColor=white)&nbsp;
![scikit-learn](https://img.shields.io/badge/scikit--learn-111?style=flat-square&logo=scikit-learn&logoColor=F7931E)&nbsp;
![XGBoost](https://img.shields.io/badge/XGBoost-111?style=flat-square&logoColor=white)&nbsp;
![LightGBM](https://img.shields.io/badge/LightGBM-111?style=flat-square&logoColor=white)&nbsp;
![Ollama](https://img.shields.io/badge/Ollama-111?style=flat-square&logo=ollama&logoColor=white)&nbsp;
![OpenCV](https://img.shields.io/badge/OpenCV-111?style=flat-square&logo=opencv&logoColor=5C3EE8)&nbsp;
![MLflow](https://img.shields.io/badge/MLflow-111?style=flat-square&logo=mlflow&logoColor=0194E2)

**Infrastructure**

![FastAPI](https://img.shields.io/badge/FastAPI-111?style=flat-square&logo=fastapi&logoColor=009688)&nbsp;
![Docker](https://img.shields.io/badge/Docker-111?style=flat-square&logo=docker&logoColor=2496ED)&nbsp;
![Kubernetes](https://img.shields.io/badge/Kubernetes-111?style=flat-square&logo=kubernetes&logoColor=326CE5)&nbsp;
![Kubeflow](https://img.shields.io/badge/Kubeflow-111?style=flat-square&logo=kubeflow&logoColor=4279F4)&nbsp;
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-111?style=flat-square&logo=githubactions&logoColor=2088FF)&nbsp;
![AWS](https://img.shields.io/badge/AWS-111?style=flat-square&logo=amazon-aws&logoColor=FF9900)&nbsp;
![GCP](https://img.shields.io/badge/GCP-111?style=flat-square&logo=google-cloud&logoColor=4285F4)

**Languages**

![Python](https://img.shields.io/badge/Python-111?style=flat-square&logo=python&logoColor=3776AB)&nbsp;
![C++](https://img.shields.io/badge/C++-111?style=flat-square&logo=cplusplus&logoColor=00599C)&nbsp;
![SQL](https://img.shields.io/badge/SQL-111?style=flat-square&logo=postgresql&logoColor=336791)&nbsp;
![JavaScript](https://img.shields.io/badge/JavaScript-111?style=flat-square&logo=javascript&logoColor=F7DF1E)&nbsp;
![R](https://img.shields.io/badge/R-111?style=flat-square&logo=r&logoColor=276DC3)

</div>

---

## Activity

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=mostaphaelansari&show_icons=true&theme=github_dark&hide_border=true&count_private=true&title_color=00e5ff&icon_color=00e5ff&text_color=cccccc&bg_color=0d1117"/>
&nbsp;&nbsp;
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mostaphaelansari&layout=compact&theme=github_dark&hide_border=true&title_color=00e5ff&text_color=cccccc&bg_color=0d1117"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=mostaphaelansari&theme=github-dark-blue&hide_border=true&background=0d1117&ring=00e5ff&fire=ff9900&currStreakLabel=00e5ff&sideLabels=888888&dates=555555" height="150"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=mostaphaelansari&bg_color=0d1117&color=00e5ff&line=00e5ff&point=ffffff&area=true&area_color=00e5ff&hide_border=true&radius=4" width="96%"/>

</div>

---

<br/>

<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   "The goal is not to use the latest model.                  ║
║    The goal is to solve the problem well."                   ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

<br/>

![Profile views](https://komarev.com/ghpvc/?username=mostaphaelansari&style=flat-square&color=00e5ff&label=profile+views)
&nbsp;&nbsp;
[![Email](https://img.shields.io/badge/elansarimostapha011%40gmail.com-111?style=flat-square&logo=gmail&logoColor=EA4335)](mailto:elansarimostapha011@gmail.com)

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=100&section=footer&animation=twinkling" width="100%"/>
