<div align="center">

  <h1>Hi, I'm Siddhant Chindhe 👋</h1>
  <h3>AI · Data · Machine Learning · M.Sc. International Information Systems @ FAU Erlangen-Nürnberg</h3>

  <p>
    <em>I build data and AI systems for real business problems, and I measure whether they work:<br>
    baselines, held-out tests, and an honest account of what didn't.</em>
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

### 🤖 AI Engineering & LLM Applications

| Project | What it does | Result |
| :--- | :--- | :--- |
| **[it-service-desk-triage](https://github.com/sidd-24/it-service-desk-triage)** | ITIL ticket triage API: an LLM judges category, impact and urgency; fixed rules set priority, resolver group and SLA deadlines. English and German tickets. | **0 of 16** P1/P2 incidents under-called (keyword baseline: 12) |
| **[policy-compliance-rag](https://github.com/sidd-24/policy-compliance-rag)** | Q&A over company policies, GDPR, the AI Act and NIS2. Every answer cites document, page and section; questions the policies don't cover are refused. | 25/25 answers correct and cited, 8/8 uncovered questions refused |
| **[resume-screener-eu-ai-act](https://github.com/sidd-24/resume-screener-eu-ai-act)** | Ranks CVs against a job description but never decides: anonymisation before the LLM call, evidence-checked claims, audit log, built for the EU AI Act's high-risk rules. | 53 tests · CI |
| **[it-ops-compliance-assistant](https://github.com/sidd-24/it-ops-compliance-assistant)** | LangGraph agent for IT operations and ISO 27001, using role-restricted MCP tools, with audit logging and human-approved ticket drafts. | 43 tests · CI |

### 🏗️ Data Engineering

| Project | What it does | Result |
| :--- | :--- | :--- |
| **[db-delay-tracker](https://github.com/sidd-24/db-delay-tracker)** | Deutsche Bahn punctuality pipeline for Nürnberg, Fürth, Erlangen and Bamberg: DuckDB extract from a national archive, dbt models with data tests, monthly scheduled refresh. | 1.57M train stops · 20 dbt tests |
| **[job-skill-tracker](https://github.com/sidd-24/job-skill-tracker)** | Daily pipeline that collects German job postings and extracts skills, seniority and language requirements, with an auto-updated report. | Runs daily · 47 tests |
| **[energy-market-airflow-etl](https://github.com/sidd-24/energy-market-airflow-etl)** | Airflow pipeline for the German electricity market (SMARD): idempotent daily loads, data-quality checks, cheapest hours for energy-intensive production. | Load shifting would have cut a 2 MW job's October energy cost by **35 %** |
| **[kg-etl-pipeline](https://github.com/sidd-24/kg-etl-pipeline)** | ETL from JSON, YAML and XML into an RDF knowledge graph, with Pydantic validation and a FastAPI interface. | 13 tests · CI |

### 📈 Machine Learning & Data Science

| Project | What it does | Result |
| :--- | :--- | :--- |
| **[credit-default-model](https://github.com/sidd-24/credit-default-model)** | Default risk for 30,000 credit card customers: baselines, tuned LightGBM, calibration, a threshold set by business cost, SHAP, MLflow and a model card. | AUC 0.784 · cost **17 %** below the analyst rule |
| **[demand-forecast](https://github.com/sidd-24/demand-forecast)** | 28-day sales forecasts for 3,049 Walmart products (M5), backtested on three earlier windows against simple baselines. | Store-level error **6.8 %** vs 15.1 % for a 28-day average |
| **[german-news-classifier](https://github.com/sidd-24/german-news-classifier)** | Fine-tuned German BERT vs a TF-IDF baseline on 10,000 news articles, compared on accuracy, speed, size and error types. | **90.7 %** vs 87.1 % accuracy, at 620× the CPU cost |
| **[industry4-semiconductor-quality-monitoring](https://github.com/sidd-24/industry4-semiconductor-quality-monitoring)** | Early warning for failing wafers on real fab data (UCI SECOM): PCA monitoring, autoencoder and Isolation Forest, with sensor root-cause hints. | **~2×** more failures caught than random inspection |

### 📊 Data Analytics & BI

| Project | What it does | Result |
| :--- | :--- | :--- |
| **[retail-sales-powerbi](https://github.com/sidd-24/retail-sales-powerbi)** | Power BI sales dashboard on 1 million real retail transactions: cleaned star schema, DAX measures, cohort retention. | Revenue +2.5 % driven by order size, not order count |
| **[controlling-report](https://github.com/sidd-24/controlling-report)** | Monthly controlling report from SAP cost exports: reconciliation, data checks, budget vs actual vs prior year, red/amber/green status and written commentary in Excel. | Every file reconciled · 19 tests |
| **[email-ab-test](https://github.com/sidd-24/email-ab-test)** | Analysis of a randomised e-mail experiment with 64,000 customers: significance tests, multiple-testing correction, power analysis and a decision memo. | **+$0.77** revenue per customer vs no e-mail |

### 🗂️ Product & Project Management

| Project | What it does | Result |
| :--- | :--- | :--- |
| **[order-automation-case-study](https://github.com/sidd-24/order-automation-case-study)** | PRD for an order-entry AI agent: users, success metrics, phased rollout, risks (GDPR, works council) and an Excel business case. | **€89k** a year, 8-month payback |
| **[sample-tracker](https://github.com/sidd-24/sample-tracker)** | Excel tracker for product development samples with a dashboard and data checks, plus an auto-generated weekly PowerPoint status deck. | Weekly deck in one command |
| **[IT-governance-status-reporter](https://github.com/sidd-24/IT-governance-status-reporter)** | Turns Jira tickets into PMO reports: KPI trends, RAG status and a one-page steering committee PDF. | Jira Cloud or offline demo |
| **[ai-use-case-assessment-eu-ai-act](https://github.com/sidd-24/ai-use-case-assessment-eu-ai-act)** | Prioritises AI use cases by value and feasibility, then checks each against EU AI Act risk tiers and GDPR. | Portfolio matrix and steering one-pager |

<details>
<summary><strong>More projects</strong></summary>
<br>

- **[IT-asset-compliance-tracker](https://github.com/sidd-24/IT-asset-compliance-tracker)**: IT asset register with ISO 27001 evidence packs, end-of-life checks and licence reconciliation.
- **[f1-race-predictor](https://github.com/sidd-24/f1-race-predictor)**: Formula 1 finishing-position model on FastF1 data; it honestly only matches the "finish = grid" baseline.
- **[FLM](https://github.com/sidd-24/FLM)**: Federated learning on non-IID data, comparing synchronous and asynchronous aggregation.
- **[qa-coverage-tool](https://github.com/sidd-24/qa-coverage-tool)**: AI-assisted test generation and a coverage gap tracker.
- **[playwright-e2e-suite](https://github.com/sidd-24/playwright-e2e-suite)**: End-to-end browser tests with Playwright and pytest.
- **[n8n-llm-automation](https://github.com/sidd-24/n8n-llm-automation)**: Low-code support-request routing with n8n and an LLM.
- **[llm-agent](https://github.com/sidd-24/llm-agent)**: Tool-calling agent with web search, Wikipedia and a calculator.

</details>

---

### 🛠️ Skills & Technologies

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,fastapi,docker,githubactions,git,linux,aws,azure" height="44" alt="Python, PyTorch, scikit-learn, FastAPI, Docker, GitHub Actions, Git, Linux, AWS, Azure" />
</p>

| Domain | Technologies |
| :--- | :--- |
| **🤖 AI & LLMs** | `LangGraph` · `LangChain` · `MCP` · `RAG` · `Hugging Face Transformers` · `LLM evaluation` · `Azure OpenAI` · `Groq` |
| **🏗️ Data Engineering** | `SQL` · `dbt` · `DuckDB` · `Apache Airflow` · `Parquet` · `ETL/ELT` · `Data quality tests` · `GitHub Actions` |
| **📈 Machine Learning** | `scikit-learn` · `LightGBM` · `XGBoost` · `PyTorch` · `MLflow` · `SHAP` · `Time series` · `NLP` |
| **📊 Analytics & BI** | `Power BI` · `DAX` · `Excel` · `pandas` · `A/B testing` · `Statistics` |
| **🗂️ Product & Project** | `PRDs` · `Business cases` · `Jira` · `Agile/Scrum` · `Stakeholder reporting` · `EU AI Act` · `GDPR` |
| **⚙️ Engineering** | `FastAPI` · `Pydantic` · `pytest` · `Docker` · `REST APIs` · `CI/CD` |

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
  <sub>Open to <strong>Working Student</strong>, <strong>Internship</strong> and <strong>Master's Thesis</strong> positions in AI Engineering, Data Engineering, Data Science, BI and Product / Project Management (Germany / EU / Remote).</sub>
  <br><br>
  <a href="https://www.linkedin.com/in/siddhant-chindhe/" title="LinkedIn"><img src="https://skillicons.dev/icons?i=linkedin" height="38" alt="LinkedIn" /></a>
  &nbsp;&nbsp;
  <a href="mailto:siddhant.chindhe.de@gmail.com" title="Email"><img src="https://skillicons.dev/icons?i=gmail" height="38" alt="Gmail" /></a>
  &nbsp;&nbsp;
  <a href="https://github.com/sidd-24" title="GitHub"><img src="https://skillicons.dev/icons?i=github" height="38" alt="GitHub" /></a>
</div>
