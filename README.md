<h1 align="center">Hi, I'm Sibi</h1>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=2F81F7&center=true&vCenter=true&width=640&lines=AI+Security+%C2%B7+Agentic+Systems+%C2%B7+Data+Engineering;Making+Agent+memory+robust+against+poisoned+data;Shipped+a+Teradata+%E2%86%92+Databricks+lakehouse+to+go-live;MS+Applied+Data+Science+%40+UF+(4.0+GPA)" alt="Typing intro" />
  </a>
</p>

<p align="center">
  AI and data engineer with client-facing delivery across <b>enterprise consulting, financial servies, defense, and regulated medtech</b>.<br>
  I've taken a legacy warehouse to a Spark lakehouse through go-live, and now I'm focused on <b>AI security</b>:<br>
  making agentic and RAG systems robust enough for high-stakes deployments.
</p>

<p align="center">
  <a href="mailto:sibiseenivasan@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/sibi-seenivasan"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://www.github.com/sibi-seeni"><img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

---

### Right Now

- **AI Security Engineer** with NIWC & DIU through Hacking for Defense, reproducing RAG poisoning attacks from 8 papers and benchmarking defenses for a Navy-facing prototype
- **Researching** trust-aware graph retrieval, a GNN retriever that down-weights poisoned sources before they reach the LLM (extending into my Spring 2027 capstone)
- **Under review** at *ECJ Data Science (Elsevier)*: modeling how fast community backlash decays online
- **Open to** AI Security, Agentic AI, and Data Engineering roles · graduating May 2027

---

### Experience

<details open>
<summary><b>AI Security Engineer</b> · Naval Information Warfare Center (NIWC) & DIU, Hacking for Defense · <i>Aug 2026 – Present</i></summary>
<br>

- Scoped the threat through **19 stakeholder interviews** (Navy captains, NIWC directors, portfolio managers, engineers), narrowing 3 classes of RAG poisoning down to the highest-impact one: outdated or conflicting document versions that mislead even agentic RAG
- Reproduced attacks from **8 published papers** to set evaluation baselines; now benchmarking defenses for a planned prototype
- Translating technical risk into defense-in-depth recommendations for non-technical DoD stakeholders

</details>

<details>
<summary><b>Software Engineer Intern</b> · Verotech Solutions LLC · <i>May 2026 – Aug 2026</i></summary>
<br>

- Built an **agentic RAG decision-support system** for Stryker, turning FDA 21 CFR 820 requirements into a client-facing compliance workflow
- Added source attribution and human-in-the-loop review using Google's **Agent2Agent (A2A)** protocol, wired into the client's existing compliance system
- Scaled reasoning to **200+ pages** of compliance docs across 6-turn sessions, owning the Python codebase through review and handoff

</details>

<details>
<summary><b>Technology Consulting Associate</b> · PwC India · <i>Aug 2024 – Jul 2025</i></summary>
<br>

- Forward-deployed for 6 months with **Aditya Birla Sun Life**, working with the Head of Data inside a 40-member Agile team
- Owned **50+ Teradata → Databricks DDL conversions** and **40+ silver/gold DML scripts** for a medallion lakehouse fed by Azure Data Factory
- Ran daily validation with 6 business units through go-live, letting the client decommission Teradata and **cut cloud costs 17%**
- Built the client's CI/CD with automated testing (**30% faster deploys**) and Power BI observability dashboards (**3× faster insights**)
- Built LLM proofs-of-concept presented in sales engagements that helped land a new enterprise project

</details>

<details>
<summary><b>Graduate Teaching & Research Assistant</b> · University of Florida (IC3 Lab; Engineering Education) · <i>Nov 2025 – Present</i></summary>
<br>

- Built an agent-based **NL2SQL tool** (LangChain) giving an LLM function-calling access to the MIMIC critical-care database
- Improved transcription accuracy **33%** with a locally deployed GPT-OSS-20B
- Maintain server infrastructure and CI for **600+ students** a semester; built analytics pipelines presented at the UF Engineering Education Symposium

</details>

---

### Featured Work

<table>
<tr>
<td width="50%" valign="top">

#### Xposure: Accessible Portfolio Exposure Graph
**Honorable Mention, Blackstone challenge @ ShellHacks 2026** (solo, 36 hrs)

Shows how "diversified" holdings are secretly linked, like utilities and semiconductors through data-center power demand. A PostgreSQL knowledge graph with **20+ FastAPI endpoints** for multi-hop traversal and shock propagation, plus a **Snowflake Cortex agent** that proposes new relationships for human approval. Built for blind and low-vision investors with narration and sonification.

`FastAPI` `PostgreSQL` `Snowflake Cortex` `React` `TypeScript` `PyTest`

</td>
<td width="50%" valign="top">

#### Trust-Aware Graph Retrieval *(in progress)*
UF Applied ML II architecture project → Spring 2027 capstone

A GNN retriever with attention that models documents and evidence as a graph, learning to **down-weight poisoned or untrustworthy sources** before they reach the LLM in RAG or agent-memory pipelines. Complements the adversarial RAG work with NIWC.

`PyTorch` `GNNs` `RAG` `AI Security`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### The Half-Life of Outrage
**Submitted to ECJ Data Science (Elsevier)**

Aspect-based sentiment pipeline over **160k+ YouTube comments** across 905 videos using LLaMA 3.3 70B and RoBERTa (Gwet's AC1 of 0.98–0.99 vs. gold labels). Exponential decay models show AI-voice controversies fade **4× faster** (0.48 days) than general game discourse.

`LLaMA 3.3` `RoBERTa` `NLP` `Statistical Modeling`

</td>
<td width="50%" valign="top">

#### [Educator's AI Analytics Dashboard](https://github.com/realasuarez/gator-hack-final-app)
GatorHacks 2025

Upload a lecture, get a transcript, topics covered, and progress against the syllabus. FastAPI backend chaining **Whisper v3 → Llama-3.3-70B**, with async background jobs cutting latency **40%**.

`FastAPI` `Whisper` `Llama 3.3` `TypeScript` `asyncio`

</td>
</tr>
</table>

#### More Builds

<table>
<tr>
<td width="50%" valign="top">

**[Real-Time Product Launch Radar](https://github.com/sibi-seeni/realtime-product-radar)**<br>
<sub>Event-driven pipeline on the live Bluesky firehose with INT8 ONNX sentiment inference, ClickHouse time-series storage, and Grafana dashboards tracking sentiment velocity.</sub><br>
`ONNX` `ClickHouse` `Grafana` `Streaming`

</td>
<td width="50%" valign="top">

**[TSLA Options on Black-Scholes](https://github.com/sibi-seeni/TSLA_Option_Modeling_BS)**<br>
<sub>21k+ contracts, 11 features. XGBoost cut MAPE 46% vs. regression and beat a from-scratch Bi-LSTM by 1.8%.</sub><br>
`XGBoost` `PyTorch` `Time Series`

</td>
</tr>
</table>

---

### Tech Toolbox

**AI & Agents**<br>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/RAG-6E40C9?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/Agent2Agent%20(A2A)-4285F4?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/Snowflake%20Cortex-29B5E8?style=flat-square&logo=snowflake&logoColor=white"/>

**Data & Cloud**<br>
<img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white"/>
<img src="https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure%20Data%20Factory-0078D4?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS%20EMR-232F3E?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Teradata-F37440?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logoColor=black"/>

**Languages & Engineering**<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTest-0A9EDC?style=flat-square&logo=pytest&logoColor=white"/>

**Security Testing**<br>
<img src="https://img.shields.io/badge/Prompt%20Injection-B22222?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/RAG%20Poisoning-B22222?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/Adversarial%20Evaluation-B22222?style=flat-square&logoColor=white"/>

---

### Education & Recognition

| |
|---|
| **University of Florida** · MS, Applied Data Science · *May 2027* |
| **NIT Trichy** · B.Tech, Electrical & Electronics Engineering · *May 2024* |

- UF Herbert Wertheim College of Engineering Achievement Award
- Microsoft Certified: Power BI Data Analyst Associate · Python & Pandas for Data Engineering (Duke) · Orchestrating GenAI Workflows (DeepLearning.AI)

---

<p align="center">
  Always up for research collaborations, AI security conversations, or data-heavy product ideas.<br>
  Reach me at <a href="mailto:sibiseenivasan@gmail.com"><b>sibiseenivasan@gmail.com</b></a> or on <a href="https://linkedin.com/in/sibi-seenivasan">LinkedIn</a>.
</p>
