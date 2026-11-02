<div align="center">

  <h1>Hi, I'm Siddhant Chindhe 👋</h1>
  <h3>AI & Data Engineer · M.Sc. International Information Systems @ FAU Erlangen-Nürnberg</h3>

  <p>
    <em>I build AI and data systems for real operations (IT service management, compliance and Industry 4.0),<br>
    with the evaluation and governance that make them trustworthy.</em>
  </p>

  <p>
    <img src="https://img.shields.io/badge/N%C3%BCrnberg%2C_Germany-1F2937?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location: Nürnberg, Germany" />
    <img src="https://img.shields.io/badge/Open_to-Working_Student_·_Internship_·_Master's_Thesis-2563EB?style=for-the-badge" alt="Open to Working Student, Internship, Master's Thesis" />
  </p>

  <p>
    <a href="https://www.linkedin.com/in/siddhant-chindhe/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:siddhant.chindhe.de@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  </p>

</div>

---

### 🧭 How I build

- **📏 Measured, not claimed.** Every AI project ships with a labelled evaluation set and a simple baseline, and the README also reports what didn't work.
- **🛡️ Governance by design.** Human review where it matters, audit logs, role-restricted tools, and requirements mapped to the **EU AI Act**, **GDPR** and **ISO 27001**.
- **⚙️ Production habits.** Typed APIs, idempotent pipelines, tests that run without API keys, and CI on every push.

---

### 🌟 Featured Projects

#### 🛡️ Trustworthy AI & Compliance

| Project | What it does | Result |
| :--- | :--- | :--- |
| **[resume-screener-eu-ai-act](https://github.com/sidd-24/resume-screener-eu-ai-act)** | Ranks CVs against a job description, but **never decides**. Personal data is anonymised before the LLM call, AI claims are checked against the CV, and every run is audit-logged, following the EU AI Act rules for high-risk hiring systems. | 53 tests · CI |
| **[policy-compliance-rag](https://github.com/sidd-24/policy-compliance-rag)** | Q&A over company policies, GDPR, the AI Act and NIS2. Every answer cites **document, page and section**, and it refuses questions the policies don't cover. | 25/25 answers correct and cited, 8/8 uncovered questions refused |
| **[ai-use-case-assessment-eu-ai-act](https://github.com/sidd-24/ai-use-case-assessment-eu-ai-act)** | Prioritises AI use cases by value and feasibility, then checks each against **EU AI Act risk tiers** and GDPR DPIA triggers. | Portfolio matrix, obligations tracker, steering one-pager |

#### 🧩 IT Operations & Governance

| Project | What it does | Result |
| :--- | :--- | :--- |
| **[it-service-desk-triage](https://github.com/sidd-24/it-service-desk-triage)** | ITIL triage API. An LLM judges category, impact and urgency; fixed rules set **priority, resolver group, SLA deadlines** and human review. Handles English and German tickets. | **0 of 16** P1/P2 incidents under-called (keyword baseline: 12) |
| **[it-ops-compliance-assistant](https://github.com/sidd-24/it-ops-compliance-assistant)** | AI assistant for IT operations and ISO 27001. A LangGraph agent uses **role-restricted MCP tools**, with an audit log and human-approved ticket drafts. | 43 tests · CI |
| **[IT-asset-compliance-tracker](https://github.com/sidd-24/IT-asset-compliance-tracker)** | IT asset repository with **ISO 27001 Annex A evidence packs**, end-of-life checks and license true-up reconciliation. | Audit-ready Excel evidence pack |
| **[IT-governance-status-reporter](https://github.com/sidd-24/IT-governance-status-reporter)** | Turns Jira tickets into PMO reports: KPI trends, RAG status and a **one-page steering committee PDF**. | Jira Cloud or offline demo |

#### 🏭 Data Engineering & Industry 4.0

| Project | What it does | Result |
| :--- | :--- | :--- |
| **[airflow-etl](https://github.com/sidd-24/airflow-etl)** | Airflow pipeline for the **German electricity market** (Bundesnetzagentur SMARD): idempotent daily loads, data-quality checks, and the cheapest hours to run energy-intensive production. | Shifting a 2 MW job would have cut its October energy cost by **35%** |
| **[industry4-semiconductor-quality-monitoring](https://github.com/sidd-24/industry4-semiconductor-quality-monitoring)** | Early warning for failing wafers on **real fab data** (UCI SECOM). Compares PCA process monitoring, an autoencoder and Isolation Forest, with sensor root-cause hints. | **~2×** more failures caught than random inspection |
| **[kg-etl-pipeline](https://github.com/sidd-24/kg-etl-pipeline)** | ETL from JSON, YAML and XML into an **RDF knowledge graph**, with Pydantic validation and a FastAPI interface. | 13 tests · CI |

<details>
<summary><strong>More projects</strong></summary>
<br>

- **[f1-race-predictor](https://github.com/sidd-24/f1-race-predictor)**: Formula 1 finishing-position model built on FastF1 data. It honestly matches the strong "finish = grid" baseline (Spearman 0.63 vs 0.62).
- **[qa-coverage-tool](https://github.com/sidd-24/qa-coverage-tool)**: AI-assisted test generation and a coverage gap tracker, with Python and TypeScript regression suites in CI.
- **[playwright-e2e-suite](https://github.com/sidd-24/playwright-e2e-suite)**: End-to-end browser tests with Playwright and pytest.
- **[n8n-llm-automation](https://github.com/sidd-24/n8n-llm-automation)**: Low-code support-request routing with n8n and an LLM.
- **[llm-agent](https://github.com/sidd-24/llm-agent)**: Tool-calling agent with web search, Wikipedia and a calculator.
- **[FLM](https://github.com/sidd-24/FLM)**: Federated learning experiments.

</details>

---

### 🛠️ Skills & Technologies

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,docker,pytorch,aws,sqlite,git,githubactions,linux,bash,postman,vscode" height="44" alt="Python, FastAPI, Docker, PyTorch, AWS, SQLite, Git, GitHub Actions, Linux, Bash, Postman, VS Code" />
</p>

| Domain | Technologies |
| :--- | :--- |
| **🧠 GenAI & Agents** | `LangGraph` · `LangChain` · `Model Context Protocol (MCP)` · `RAG` · `ChromaDB` · `Groq` · `Hugging Face` · `LLM evaluation` |
| **⚙️ Backend & APIs** | `FastAPI` · `Pydantic` · `pytest` · `REST APIs` · `Streamlit` · `Uvicorn` |
| **📊 Data Engineering** | `Apache Airflow` · `Docker` · `ETL/ELT` · `Knowledge Graphs (RDFLib)` · `Pandas` · `SQLite` · `AWS` |
| **📈 Machine Learning** | `Scikit-Learn` · `XGBoost` · `PyTorch` · `Anomaly Detection` · `Autoencoders` · `Federated Learning` |
| **🛡️ Governance & IT Management** | `EU AI Act` · `GDPR` · `ISO/IEC 27001` · `ITIL` · `NIS2` · `Jira` |
| **🤝 Ways of Working** | `Agile SDLC` · `Technical Documentation` · `Stakeholder Communication` · `GitHub Actions CI/CD` |

---

### 💼 Experience & Education

<details open>
<summary><strong>🎓 Education</strong></summary>
<br>

- **Friedrich-Alexander-Universität Erlangen-Nürnberg (FAU)** | *Nürnberg, Germany*
  - **M.Sc. in International Information Systems** *(Oct 2024 – Present)*
  - **Focus**: Machine Learning, Process Mining & Analytics, Federated Learning, Enterprise Knowledge Management.
</details>

<details open>
<summary><strong>💼 Industry Experience</strong></summary>
<br>

- **Cognizant** | *Programmer Analyst (Prompt Engineer)* | `Apr 2023 – Sep 2024` *(Pune, India)*
  - Built context-aware enterprise chatbots with LangChain and Azure OpenAI, cutting response latency by **40%** through prompt optimization and workflow automation.
  - Deployed GenAI solutions on Azure Cloud with function calling, real-time retrieval and risk-control guardrails.
  - Designed and tested Python AI/ML pipelines across the Agile SDLC.
- **Cognizant** | *Data Integration Intern* | `Mar 2022 – Sep 2022` *(Pune, India)*
  - Developed automated data ingestion and validation pipelines with Python, SQL and shell scripting for large-scale data processing.
</details>

---

### 📊 GitHub Activity

<div align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=sidd-24&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="165" />
  <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=sidd-24&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165" />
</div>

---

<div align="center">
  <sub>Open to <strong>Working Student</strong>, <strong>Internship</strong> and <strong>Master's Thesis</strong> positions in AI Engineering, Data Engineering and Python Backend (Germany / EU / Remote).</sub>
  <br><br>
  <a href="https://www.linkedin.com/in/siddhant-chindhe/" title="LinkedIn"><img src="https://skillicons.dev/icons?i=linkedin" height="38" alt="LinkedIn" /></a>
  &nbsp;&nbsp;
  <a href="mailto:siddhant.chindhe.de@gmail.com" title="Email"><img src="https://skillicons.dev/icons?i=gmail" height="38" alt="Gmail" /></a>
  &nbsp;&nbsp;
  <a href="https://github.com/sidd-24" title="GitHub"><img src="https://skillicons.dev/icons?i=github" height="38" alt="GitHub" /></a>
</div>
