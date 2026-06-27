<!-- Mohammad Sadegh Abbaszadeh | AI Engineer Profile -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&height=160&section=header&text=Mohammad%20Sadegh%20Abbaszadeh&fontSize=36&fontColor=00f5ff&stroke=bf00ff&animation=fadeIn" alt="Header banner"/>

**AI Engineer & Principal Data Scientist**

*Neural Systems | Agentic AI | Production LLMs | MLOps*

<br/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=00F5FF&center=true&width=850&lines=Designing+neural+pipelines+that+learn+and+scale;Building+multi-agent+systems+with+CrewAI+%26+LangChain;Shipping+RAG+%2C+LLMs+%2C+and+inference+at+production+scale"/>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/msabbaszadeh)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:msabbaszadeh1997@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/msabbaszadeh)

</div>

---

## Deep Neural Network

Principal Data Scientist with **7+ years** building ML and LLM systems across **Fintech, HealthTech, and Insurance**. I architect neural pipelines from raw data to production inference.

<img src="https://raw.githubusercontent.com/msabbaszadeh/msabbaszadeh/main/assets/neural-header.svg" width="100%" alt="Deep neural network with input layers, hidden layers, activation, and AI inference core"/>

```
  SENSORY INPUT          HIDDEN LAYERS              ACTIVATION        INFERENCE
       o                    o   o   o                  o o o            (AI)
      /|\      synapse     /|  /|  /|      signal      \|/|/      -->   core
   o--o--o--o-----------> o-o-o-o-o-o ----------------> o-o-o ---------> [*]
```

| Layer | What I build |
|-------|-------------|
| **Generative AI** | RAG, fine-tuning, CPT, DPO, RLHF, LLM-to-SLM distillation |
| **Inference** | vLLM, GGUF/AWQ quantization, low-latency neural serving |
| **MLOps** | MLflow, Kubernetes, Docker, CI/CD on AWS / GCP / Azure |
| **Classical ML** | XGBoost, survival analysis, fraud/risk engines, A/B testing |

---

## Agentic AI Systems

I design **autonomous multi-agent workflows** that plan, execute, validate, and iterate — not just single-shot LLM calls.

<img src="https://raw.githubusercontent.com/msabbaszadeh/msabbaszadeh/main/assets/agentic-ai.svg" width="100%" alt="Agentic AI orchestration with Planner, Research, Executor, and Critic agents connected to RAG, LLM, and MCP tools"/>

```mermaid
flowchart TB
    subgraph ORCH["Orchestrator — CrewAI / LangChain"]
        P[Planner Agent]
        R[Router / Memory]
    end

    subgraph AGENTS["Specialized Agents"]
        A1[Research Agent\nRAG + Vector Search]
        A2[Executor Agent\nTools + API + Code]
        A3[Critic Agent\nValidation + Guardrails]
    end

    subgraph TOOLS["Tool Layer — MCP"]
        T1[(Vector DB\nQdrant / Pinecone)]
        T2[LLM / SLM\nvLLM Inference]
        T3[External APIs\nSQL / Python / Web]
    end

    P --> A1
    P --> A2
    A1 --> T1
    A2 --> T2
    A2 --> T3
    A3 --> P
    A1 --> A3
    A2 --> A3

    style ORCH fill:#0a0e17,stroke:#00f5ff,color:#c9d1d9
    style AGENTS fill:#0a0e17,stroke:#bf00ff,color:#c9d1d9
    style TOOLS fill:#0a0e17,stroke:#00ff88,color:#c9d1d9
```

**Stack:** CrewAI · LangChain · MCP (Model Context Protocol) · Tool Design · Agent Memory · Human-in-the-loop

**Current work @ Vortem:** translating SOTA agentic architectures into production commercial systems with rigorous benchmarking and MLOps lifecycle management.

---

## Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,docker,kubernetes,fastapi,postgres,aws,gcp,azure,git,linux&theme=dark&perline=6" alt="Technology icons"/>

</div>

`LangChain` · `CrewAI` · `vLLM` · `RAG` · `Qdrant` · `Pinecone` · `Spark` · `Airflow` · `MLflow` · `XGBoost`

---

## Featured Projects

| | Project | Description |
|---|---------|-------------|
| **RAG** | [**Electron**](https://github.com/msabbaszadeh/Electron) | Open-source recommendation engine — vector search, embeddings, LLM personalization |
| **ML** | [**Cardiovascular ML**](https://github.com/msabbaszadeh/Machine-learning-DNN-ETC-on-cardiovascular-disease-patients-data) | Predictive modeling on 300K+ patient records — DNN, ensembles, survival analysis |
| **Prod** | **Insurance RAG** *(private)* | Claims automation with custom chunking + vector indexing — **+12% throughput** |
| **Lab** | [**Diabetes SVM**](https://github.com/msabbaszadeh/diabets-analysis-SVM-model) | Classical ML experiments and health analytics notebooks |

> Enterprise agentic pipelines and MLOps systems live in private repos — available for architecture walkthroughs in interviews.

---

## GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=msabbaszadeh&show_icons=true&theme=transparent&bg_color=0a0e17&title_color=00f5ff&icon_color=bf00ff&text_color=c9d1d9&border_color=30363d&include_all_commits=true" alt="GitHub stats"/>
<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=msabbaszadeh&theme=dark&background=0a0e17&ring=00f5ff&fire=bf00ff&currStreakLabel=00ff88&sideLabels=00f5ff&dates=c9d1d9&border=30363d" alt="Contribution streak"/>

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=msabbaszadeh&layout=compact&theme=transparent&bg_color=0a0e17&title_color=00f5ff&text_color=c9d1d9&border_color=30363d&langs_count=8" alt="Top languages"/>

</div>

---

## Currently Building

- Multi-agent orchestration with **CrewAI** and **MCP**
- LLM distillation and quantization for edge inference
- Production RAG evaluation and observability

---

<div align="center">

**AI Team Lead @ Vortem** · Tehran, Iran · Open to remote

*Neurons fire. Agents collaborate. Systems scale.*

<br/>

<img src="https://komarev.com/ghpvc/?username=msabbaszadeh&color=00f5ff&style=flat-square" alt="Profile views"/>

</div>
