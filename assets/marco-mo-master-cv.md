# Marco Mo — Master CV Source

Eindhoven, The Netherlands | [micobruh@gmail.com](mailto:micobruh@gmail.com) | +31 6 23925095  
[linkedin.com/in/cheuk-lam-marco-mo](https://linkedin.com/in/cheuk-lam-marco-mo) | [github.com/micobruh](https://github.com/micobruh)

**Target roles:** Data Scientist | AI / Machine Learning Engineer | Data Engineer | Data Analyst

*Internal source for tailoring CVs and motivation letters.*

---

## Professional Summary Bank

### Data Scientist

Data Scientist with an MSc in Data Science and Artificial Intelligence and experience in predictive modeling, NLP, time-series analysis, process mining, safe reinforcement learning, and imbalanced classification. Builds reproducible analytical workflows, applies careful validation, and translates model and operational results into dashboards, diagnostics, and stakeholder recommendations.

### AI / Machine Learning Engineer

AI/ML Engineer experienced in developing machine-learning and LLM applications from data ingestion and experimentation through tested APIs, model serving, monitoring, and user interfaces. Built agentic LangGraph workflows, role-gated MCP tools, offline RAG systems, FastAPI services, MLflow-tracked pipelines, containerized applications, and CI/CD workflows, with emphasis on reliability, privacy, guardrails, and maintainability.

### Data Engineer

Data Engineer experienced in Python- and SQL-based ingestion, transformation, validation, and API integration for structured and semi-structured data. Designed reusable ETL services for XML, JSON, CSV, fixed-width, and relational sources using canonical schemas, lookup tables, deduplication, batch processing, database migrations, and review workflows.

### Data Analyst

Data Analyst experienced in SQL, Python, process analysis, time-series data, KPI design, and interactive reporting. Builds analytical pipelines and dashboards for production bottlenecks, rework, operational burden, energy consumption, fraud monitoring, and data quality, and communicates findings to technical and non-technical audiences.

---

## Technical Skills

**Programming:** Python, SQL, C++, R, Java, Bash

**Machine learning and statistics:** pandas, NumPy, scikit-learn, XGBoost, PyTorch, TensorFlow, Keras, classification, feature engineering, imbalanced learning, cross-validation, temporal validation, threshold optimization, time-series analysis, forecasting, NLP, active learning, reinforcement learning

**LLM and applied AI:** LangChain, LangGraph, LangSmith, FastMCP, Model Context Protocol, RAG, embeddings, dense and sparse retrieval, BM25, reciprocal-rank fusion, reranking, Qdrant, Ollama, agentic workflows, tool calling, model routing, guardrails, prompt-injection protection

**Data engineering and MLOps:** ETL, batch processing, data transformation, canonical data models, schema validation, data quality, deduplication, REST APIs, FastAPI, Pydantic, Alembic, MLflow, model registry, model serving, model monitoring, feature drift, Docker, Docker Compose, GitHub Actions, CI/CD, pytest, unittest

**Databases and formats:** MySQL, PostgreSQL, SQLite, Qdrant, JSON, XML, CSV, fixed-width files, Parquet

**Analytics and engineering tools:** process mining, KPI development, root-cause analysis, Excel, Plotly, Dash, Streamlit, Matplotlib, Git, GitHub, Linux, Jupyter, VS Code, LaTeX

---

## Professional Experience

### Junior AI Specialist — ADC Nederland

Eindhoven, The Netherlands | Jun 2026 – Present *(fixed-term through Sep 2026)*

- Developed four internal data and AI systems covering order ingestion, database access through MCP, an agentic chatbot, and production process mining.
- Replaced a **5–10-minute manual database-entry process per order** with reusable source templates: approximately **30 minutes of initial product-mapping review**, followed by batch conversion of **7,000–8,000 orders to JSON in about 30 seconds**.
- Preserved a controlled exception path for the approximately **10–20% of orders** that omit required production details, such as page settings, and therefore require manual confirmation before database insertion.
- Combined deterministic data transformation, typed APIs, SQL analytics, role-based permissions, tenant-scoped authentication, privacy controls, human review, and automated testing.
- Delivered systems including an ETL run that scanned **7,773 files** and completed **6,044 validated conversions**, and an MCP service exposing **67 structured tools**.
- Worked in a seven-person ICT team and with department directors to translate operational workflows and database constraints into maintainable technical solutions.

**Technologies:** Python, SQL, MySQL, FastAPI, FastMCP, MCP, LangGraph, Streamlit, Pydantic, Alembic, Docker Compose, REST APIs, ETL, process mining

### Teaching Assistant — Eindhoven University of Technology

Eindhoven, The Netherlands | Sep 2021 – Jul 2025  
*Courses: Data Challenges, Data Analytics, Calculus*

- Supported **80+ students per week** in Python, pandas, SQL, introductory machine learning, mathematics, and analytical reasoning through labs, project meetings, and question-driven coaching.
- Diagnosed errors in code, methods, and interpretation and guided students toward independent solutions.
- Coached teams on problem scoping, method selection, result interpretation, and communication, and graded assignments and examinations using consistent criteria.

### Software Technical Lead — Student Team SimEnergy, Eindhoven University of Technology

Eindhoven, The Netherlands | Sep 2021 – Jul 2023

- Directed the software work of a **six-person multidisciplinary team** developing a hardware-and-software prototype for appliance-level energy disaggregation.
- Coordinated with hardware teammates to integrate ESP32 smart-meter collection with model predictions and with business teammates to implement dashboard and application features.
- Presented and explained the prototype at Energy Now 2023 and contributed to technical decisions across data preparation, modeling, aggregation, and visualization.

---

## Complete Project Bank

### Omnimap — Multi-Format Order Ingestion and Migration Platform

*Data engineering, ETL, schema-driven transformation, data quality*

- Designed a deterministic ETL platform that converts XML, JSON, CSV, and fixed-width customer-order files into validated PFA REST API payloads through a shared execution engine.
- Replaced a **5–10-minute manual entry process per order** with reusable canonical schemas, versioned templates, lookup tables, predicates, transformations, classifiers, and validation rules.
- Limited setup effort to an approximately **30-minute review of AI-suggested product mappings**; after template approval, a batch of **7,000–8,000 orders can be converted to JSON in about 30 seconds** without repeated mapping review.
- Flagged the approximately **10–20% of orders** missing production details, such as page settings, for manual confirmation rather than silently generating incomplete records.
- In a measured full workflow, scanned **7,773 files** and completed **6,044 validated conversions in 86.6 seconds**, while detecting **1,104 duplicate files** and recording failures and lookup gaps.
- Built batch reports, dry-run upload planning, a human-review website, FastAPI routes, Pydantic models, Alembic migrations, automated tests, and Docker Compose services.

**Technologies:** Python, FastAPI, Pydantic, Alembic, PostgreSQL, REST APIs, XML, JSON, CSV, fixed-width files, ETL, Docker Compose, pytest

### Agentic Wihabo Database Chatbot with Role-Based Access

*Agentic AI, LLM applications, tool calling, safety*

- Developed a LangGraph chatbot that routes requests among deterministic responses, direct MCP tools, multi-step planning, general conversation, refusal, and unsupported-intent paths.
- Integrated customer, front-desk, staff, and administrator permissions with account-scoped credentials so users receive only authorized capabilities.
- Reduced unnecessary model use by handling simple intents with deterministic logic or smaller models and escalating complex tasks through a configurable OpenAI-compatible API.
- Grounded operational answers in MCP results, screened unsafe requests before tool execution, and added FastAPI and Streamlit interfaces, persistent checkpoints, evaluation runners, and automated tests.

**Technologies:** Python, LangGraph, LangChain, LangSmith, FastAPI, Streamlit, MCP, tool calling, model routing, guardrails, SQLite, MLflow, pytest

### MCP Server for the Wihabo Order Database

*Model Context Protocol, database APIs, SQL analytics, privacy-aware access*

- Built a FastMCP server exposing **67 structured tools** over Wihabo REST endpoints and read-only MySQL analytics for orders, stock, products, pricing, shipping, quotations, validation, and reporting.
- Added typed Pydantic schemas and aggregate SQL tools so LLM clients can use supported operations without loading complete order histories into context.
- Enforced fail-closed role registration, tenant-scoped authentication, PII redaction, safe errors, tenant-scoped caches, and administrator-only raw-data access.
- Required feature enablement and explicit confirmation for writes and supported local and remote transports, JWT or static-token authentication, readiness checks, concurrency controls, and privacy regression tests.

**Technologies:** Python, FastMCP, MCP, Pydantic, MySQL, SQL, REST APIs, JWT, role-based access control, multi-tenant systems, caching, unittest

### Flowcenter Production Process Mining and Operational Analytics

*Data analysis, process mining, SQL, KPI design, dashboarding*

- Built a privacy-aware extraction and analysis pipeline over Flowcenter MySQL event logs, using production batches as cases and scan records as events.
- Measured process variants, transition delays, tail latency, rework, workload, and data quality using median wait, p90 wait, total wait, case volume, and related indicators.
- Designed an operational-pain score combining waiting time, p90 delay, rework, and workload to prioritize recurring production burdens.
- Delivered Parquet outputs and an interactive dashboard with product, component, and transition filters; used temporal case-level splits for optional predictive modeling.

**Technologies:** Python, SQL, MySQL, pandas, Parquet, process mining, temporal validation, KPI design, operational analytics, Docker

### Energy Disaggregation and Consumption Analytics — Honors Academy / SimEnergy

*Time-series machine learning, energy analytics, hardware integration, visualization*

- Led the software direction for a **six-person team** building a working prototype that collected smart-meter data, generated appliance-level predictions, and displayed the results.
- Preprocessed REDD and UK-DALE time-series data by aligning timestamps and removing missing readings, then built LSTM and denoising-autoencoder models for **10 appliances**.
- Integrated ESP32 data collection with the prediction workflow and implemented aggregation at hourly, daily, weekly, monthly, and yearly levels.
- Built the main Dash/Plotly prototype with total- and appliance-consumption views, charts, and a grid-map concept, and presented the work at Energy Now 2023.

**Technologies:** Python, pandas, NumPy, TensorFlow, Keras, LSTM, denoising autoencoder, time-series analysis, ESP32 integration, Dash, Plotly

### Fraud Detection MLOps Pipeline — IEEE-CIS

*Machine learning, imbalanced classification, model serving, monitoring*

- Built a production-style workflow for approximately **600,000 transactions** and **400+ features**, covering preprocessing, feature selection, temporal splitting, model training, threshold optimization, registry promotion, inference, and monitoring.
- Prevented temporal leakage by training on earlier transactions, tuning on a later validation window, and evaluating once on a held-out streaming test period.
- Trained an XGBoost champion and changed the operating threshold from **0.50 to 0.2138**, achieving **0.9287 ROC-AUC**, **0.5960 average precision**, **0.8311 precision**, and **0.9757 accuracy** on the held-out test.
- Served the registered model through FastAPI, tracked experiments in MLflow, monitored predictions and feature drift in Dash, and automated testing and container builds with GitHub Actions.

**Technologies:** Python, pandas, scikit-learn, XGBoost, MLflow, FastAPI, Dash, Docker, GitHub Actions, CI/CD

### Offline RAG System for Legal Contracts

*Retrieval-augmented generation, document AI, local deployment*

- Built an offline RAG application over **400+ legal documents**, keeping indexing, retrieval, reranking, and generation on local infrastructure.
- Combined dense retrieval and BM25 with reciprocal-rank fusion and cross-encoder reranking in Qdrant.
- Constrained Ollama-based generation to retrieved context and displayed supporting document sources through a Streamlit interface.
- Containerized the application and local model service with Docker Compose and supported CPU- and GPU-oriented configurations.

**Technologies:** Python, RAG, Qdrant, BM25, dense retrieval, reciprocal-rank fusion, cross-encoder reranking, Ollama, Streamlit, Docker Compose

### Reward-Free Safe Reinforcement Learning Exploration Using Different Entropy Measures — MSc Thesis

*Safe reinforcement learning, reward-free exploration, experimental research*

- Extended CEM and RENYI reward-free exploration algorithms with safety constraints and support for Shannon, Rényi, and behavioral entropy.
- Implemented k-nearest-neighbor and VAE density estimation, entropy and cost critics, TD(λ), importance sampling, PPO-style optimization, and KL-constrained updates in PyTorch.
- Evaluated all model checkpoints using a common state-coverage metric and expected safety cost over **24 fixed episode seeds** in Mountain Car Continuous, Cart Pole, and Safety Point Goal 1.
- Found that **CEM with Shannon entropy consistently achieved the highest feasible coverage in the classic-control tasks**; algorithm choice affected exploration more than entropy formulation, while VAE-based RENYI was more effective with continuous than discrete actions.

**Technologies:** Python, PyTorch, Gymnasium, Safety Gymnasium, PPO, VAE, k-nearest neighbors, Rényi entropy, importance sampling, TD(λ)

### Health Platform Text Classification — Bachelor End Project

*NLP, active learning, imbalanced classification*

- Analyzed text from **5,087 health companies** and defined a reproducible coding scheme for identifying digital transaction platforms; double-coding produced a **Krippendorff's alpha of 0.735**.
- Started with **750 labeled records** and used query-by-committee active learning over **30 batches** to prioritize informative examples, producing a final training set of **870 records**.
- Compared SVM, logistic regression, random forest, XGBoost, and Naive Bayes models using bag-of-words and word2vec representations, SMOTE, cross-validation, and independent test sets.
- Selected a **1-gram bag-of-words SVM with SMOTE**, which achieved **0.610 F1** and **0.619 accuracy** on a separate **218-record** final test set.

**Technologies:** Python, scikit-learn, NLP, SVM, logistic regression, XGBoost, random forest, Naive Bayes, SMOTE, active learning, cross-validation

### quickSilver Graph Database — Engineering Data Systems

*Graph data systems, cardinality estimation, query optimization*

- Achieved **4th place on the course leaderboard** based on the combined score for computation time and memory usage.
- Implemented and evaluated cardinality-estimation methods for regular path queries using synthetic and real-workload q-error, preparation time, estimation time, memory, and a combined internal score.
- Developed synopsis-based estimation and query-planning logic, including SYN1/SYN2 statistics, dynamic heuristics, cost-based join ordering, and dynamic programming.
- The best reported dynamic synopsis configuration achieved an internal score of **233.824**, with **170.0 ms** preparation time, **44.25 ms** estimation time, and **24.14 MB** peak memory.
- Optimized query execution using CSR-based graph storage, encoded source-target pairs, traversal-direction selection, caching, deduplication, and reuse of intermediate results.

**Technologies:** C++, graph databases, regular path queries, query optimization, cardinality estimation, dynamic programming, CSR, caching, data structures

### GAN Image Generation — Honors Academy AI Track

- Implemented and trained a generative adversarial network for image synthesis and evaluated outputs through training diagnostics and qualitative comparison.

**Technologies:** Python, TensorFlow, deep learning, GANs, computer vision

---

## Education

### MSc Data Science and Artificial Intelligence — Eindhoven University of Technology

Eindhoven, The Netherlands | 2023 – 2025

**Thesis:** *Reward-Free Safe Reinforcement Learning Exploration Using Different Entropy Measures*

**Selected coursework:** machine learning, deep learning, reinforcement learning, data mining, statistical learning, data engineering, data visualization, algorithmic analysis, research methodology

### Honors Academy — AI Track, Eindhoven University of Technology

Eindhoven, The Netherlands | 2021 – 2023

Completed multidisciplinary projects in energy disaggregation, time-series modeling, interactive visualization, and generative models.

### BSc Data Science — Eindhoven University of Technology and Tilburg University

The Netherlands | 2020 – 2023

**Bachelor End Project:** *Health Platform Text Classification Using Active Learning*

**Selected coursework:** data analytics, statistics, machine learning, NLP, databases, programming, calculus

---

## Languages

Cantonese — Native | English — Fluent | Mandarin — Fluent | Dutch — A2

---

## Application Profile

### Professional Motivation

- **Data science:** Understand complex data, design reliable evaluation, and connect analytical results to practical decisions.
- **AI/ML engineering:** Turn models and LLM capabilities into reliable, tested, privacy-aware applications.
- **Data engineering:** Build trustworthy pipelines that reduce manual work while keeping errors visible and recoverable.
- **Data analysis:** Convert operational data into meaningful metrics, dashboards, and recommendations.

### Preferred Problems and Domains

Applied AI and automation; manufacturing and operational improvement; data platforms and internal tools; fraud and risk; document intelligence; energy and sustainability; education; safe and reliable machine learning.

### Strengths and Work Style

- Combines data science, software engineering, data engineering, and analytical communication.
- Breaks broad problems into data, validation, modeling, interface, testing, and monitoring components.
- Prefers evidence from held-out evaluation, explicit metrics, tests, and reproducible workflows.
- Considers privacy, permissions, failure modes, and human review during system design.
- Values maintainable frameworks, typed interfaces, configuration, documentation, and clear stakeholder communication.
- Enjoys teams that provide ownership, technical feedback, collaboration, and measurable practical impact.

### Practical Application Facts

| Item | Current information |
|---|---|
| Current location | Eindhoven, The Netherlands |
| Preferred locations | The Netherlands; no relocation required |
| Work authorization | Currently resident in the Netherlands; from October 2026, employment requires a Dutch highly skilled migrant residence permit |
| Sponsorship requirement | Employer sponsorship by an IND-recognised sponsor required from October 2026 |
| Willingness to relocate | Not required for roles in the Netherlands |
| Earliest start date / notice period | Available from August 2026 |
| Preferred work arrangement | On-site or hybrid preferred; open to fully remote work |
| Willingness to travel | Open to commuting by public transport where the one-way journey is under two hours |
| Driving licence | No driving licence |
