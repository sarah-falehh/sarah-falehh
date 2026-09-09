<div align="center">

<img src="banner.png" width="100%" alt="Sarah Faleh — Applied AI Engineer">

# Sarah Faleh

### Final-Year Data Science & AI Engineering Student

**Applied AI · NLP · Document Intelligence · RAG · AI Agents · ML Engineering**

<br>

<a href="https://www.linkedin.com/in/sarah-faleh/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
</a>

<a href="https://github.com/sarah-falehh">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
</a>

<a href="mailto:sarafaleh76@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white">
</a>

<br><br>

**Available for a 6-month Final-Year Internship (PFE) in France · January 2027**

</div>

---

# About Me

I'm a final-year **Data Science & Artificial Intelligence Engineering student at ESPRIT** interested in building reliable AI systems from data processing to deployable applications.

My main interests are:

- **NLP & Document Intelligence**
- **Retrieval-Augmented Generation**
- **AI Agents & Multi-Agent Systems**
- **Information Retrieval & Embeddings**
- **Machine Learning Engineering**
- **FastAPI & AI Backend Development**
- **MLOps & Reproducible Evaluation**

I particularly enjoy projects where the challenge is not only training a model, but designing the complete system around it:

```text
Data
  ↓
Processing / Retrieval
  ↓
AI / ML
  ↓
Evaluation
  ↓
API
  ↓
Application
```

I work mainly with **Python**, and I care about making AI systems measurable, testable and understandable rather than simply adding model complexity.

---

# Technical Stack

## Applied AI

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

```text
Machine Learning
Deep Learning
NLP
BERT
LLMs
RAG
Embeddings
Information Retrieval
AI Agents
Multi-Agent Systems
```

---

## Data & ML Engineering

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)

```text
Pandas
NumPy
Scikit-learn
XGBoost
MLflow
Pytest
Regression Testing
Model Evaluation
```

---

## Backend & Software Engineering

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

```text
FastAPI
REST APIs
Docker
Docker Compose
Git
GitHub Actions
CI/CD
Linux
Flask
```

---

## Databases & Search

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

```text
SQL
PostgreSQL
MySQL
MongoDB
SQLite
Elasticsearch
FAISS
```

---

# Featured Projects

## EconIA — Multilingual Economic Document Intelligence

<a href="https://github.com/sarah-falehh/econIA">
  <img
    src="https://github.com/sarah-falehh/econIA/raw/main/docs/assets/diagrams/banner.png"
    alt="EconIA"
    width="100%"
  >
</a>

**Multilingual economic information extraction in French, Arabic and English.**

EconIA converts PDF, CSV and text-based economic reports into structured, atomic and traceable observations.

### Core architecture

```text
Document
   ↓
Structure Detection
   ↓
Atomic Segmentation
   ↓
Economic Ontology
   ↓
Semantic Binding
   ↓
Temporal / Context Resolution
   ↓
Validation & Numerical Reconciliation
   ↓
Structured Observations
```

### Engineering highlights

- deterministic and lightweight NLP;
- economic indicator ontology;
- indicator-value-period-unit-geography binding;
- geometry-aware PDF table processing;
- French / Arabic / English processing;
- Arabic RTL normalization;
- confidence and validation workflow;
- numerical coverage and provenance;
- human review;
- time-series reconstruction;
- regression testing.

### Current evaluation

- **225 / 225 regression tests passing**
- **14 TP · 0 FP · 0 FN** on the current frozen 14-event GOLD benchmark
- **100% Precision / Recall / F1 / Event Exact Match** on that small benchmark only
- Arabic validation runs producing **32 and 44 extracted events**
- CPU-friendly execution

> The current GOLD benchmark is intentionally small. These results do not imply universal extraction accuracy on unseen documents.

**Tech:** Python · NLP · Scikit-learn · PyMuPDF · pandas · Streamlit · Plotly · SQLite · Pytest

[View EconIA →](https://github.com/sarah-falehh/econIA)

---

## FX AlphaLab — Multi-Agent Financial Intelligence

<a href="https://github.com/sarah-falehh/fx-alphalabs">
  <img
    src="https://github.com/sarah-falehh/fx-alphalabs/raw/main/assests/fx-alphalab-banner.png"
    alt="FX AlphaLab"
    width="100%"
  >
</a>

Five-month collaborative project developed by a **six-person engineering team in collaboration with VALUE**.

I contributed as one of the project's **Solution Architects**, focusing on architectural coherence and integration between the data, AI and application layers.

### Architecture

```text
Market Data
Macro Data
News / Sentiment
      ↓
Unified Data Layer
      ↓
Technical Agent
Macro Agent
Sentiment Agent
      ↓
Central Orchestrator
      ↓
Conviction / Validation
      ↓
FastAPI
      ↓
Dashboard
```

The broader architecture also includes an **AlphaBot contextual retrieval component** using RAG.

### Highlights

- 200,000+ rows of integrated financial data;
- specialized analytical agents;
- central orchestration;
- contextual retrieval and RAG;
- embeddings;
- FastAPI;
- REST APIs;
- WebSocket communication;
- MLflow;
- Docker;
- historical backtesting.

> FX AlphaLab is a financial-intelligence prototype. It did not perform live real-money trading and does not claim validated real-world alpha.

**Tech:** Python · FastAPI · RAG · Embeddings · AI Agents · MLflow · Docker · React · TypeScript

[View FX AlphaLab →](https://github.com/sarah-falehh/fx-alphalabs)

---

## SmartShop AI — Multimodal E-Commerce AI

<a href="https://github.com/sarah-falehh/smartshop-ai">
  <img
    src="https://github.com/sarah-falehh/smartshop-ai/raw/main/assets/banner.png"
    alt="SmartShop AI"
    width="100%"
  >
</a>

Multimodal e-commerce project integrating **six AI modules**:

- accessible product captioning;
- image enhancement;
- multimodal recommendation;
- product categorization;
- Aspect-Based Sentiment Analysis;
- RAG shopping assistant.

### Selected results

| Task | Result |
|---|---:|
| Product Categorization | **86% Accuracy** |
| ABSA | **81.5% Macro F1** |
| RAG Retrieval | **91.7% Hit Rate** |

The RAG retrieval score measures the **retrieval stage**, not final chatbot-answer correctness.

**Tech:** BERT · Sentence-BERT · Llama 3.1 8B · Groq · FAISS · EfficientNet · ResNet · PyTorch

[View SmartShop AI →](https://github.com/sarah-falehh/smartshop-ai)

---

## Water Quality — End-to-End MLOps Pipeline

<a href="https://github.com/sarah-falehh/water-quality-prediction-mlops">
  <img
    src="https://github.com/sarah-falehh/water-quality-prediction-mlops/raw/main/assets/banner.png"
    alt="Water Quality MLOps"
    width="100%"
  >
</a>

ML engineering project built around a Random Forest water-potability classifier.

The model itself shows significant overfitting:

```text
Training accuracy = 100%
Test accuracy     ≈ 66.8%
```

The project is therefore mainly used to demonstrate the **engineering lifecycle around an ML model**.

### Engineering coverage

- FastAPI model serving;
- REST API;
- Pydantic validation;
- MLflow experiment tracking;
- Docker / Docker Compose;
- Elasticsearch / Kibana;
- GitHub Actions;
- Pytest;
- Black / Flake8 / Bandit;
- model retraining endpoint.

**Tech:** Python · Scikit-learn · FastAPI · MLflow · Docker · GitHub Actions · Elasticsearch · Kibana

[View Water Quality MLOps →](https://github.com/sarah-falehh/water-quality-prediction-mlops)

---

# Additional Projects

### FIFA World Cup Analytics

Business Intelligence project using:

**Power BI · Power Query · DAX · Star Schema · ETL**

Interactive dashboards for historical World Cup analysis, teams, players and tournament KPIs.

---

### Multilingual Appointment Platform

Python / Flask web application with:

- authentication;
- appointment management;
- patient and admin spaces;
- messaging;
- multilingual interface;
- notifications.

**Tech:** Flask · SQLite · HTML · CSS · JavaScript

---

# Engineering Principles

Across my projects, I try to follow a few simple principles:

### Measure before claiming

A metric should always be associated with its evaluation protocol and scope.

### Keep limitations visible

A weak model, small benchmark or prototype limitation should be documented rather than hidden.

### Separate concerns

```text
Data
≠
Model
≠
Retrieval
≠
API
≠
Application
```

### Prefer appropriate architecture over unnecessary complexity

A large LLM is not automatically the right solution for every AI problem.

### Make systems testable

Regression tests, evaluation datasets and reproducible pipelines are part of the AI system.

---

# Currently Exploring

I'm currently strengthening my knowledge in:

- AI Agents;
- Multi-Agent Systems;
- LangGraph;
- advanced RAG evaluation;
- retrieval and reranking;
- production AI architecture.

These are areas I am actively learning and experimenting with, not technologies I claim to have fully mastered.

---

# Education

### ESPRIT

**Engineering Degree in Computer Science**  
Data Science & Artificial Intelligence specialization

**2022 — 2027**

Relevant coursework:

```text
Machine Learning
Deep Learning
Statistics
NLP
Data Science
MLOps
Software Engineering
Databases
```

---

# Languages

| Language | Level |
|---|---|
| Arabic | Native |
| French | C1 |
| English | C1 |

---

# GitHub Activity

<p align="center">

<img
  width="49%"
  src="https://github-stats-extended.vercel.app/api?username=sarah-falehh&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true"
  alt="Sarah Faleh GitHub statistics"
/>

<img
  width="39%"
  src="https://github-stats-extended.vercel.app/api/top-langs/?username=sarah-falehh&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"
  alt="Sarah Faleh languages"
/>

</p>

<p align="center">

<img
  width="95%"
  src="https://github-readme-activity-graph.vercel.app/graph?username=sarah-falehh&theme=tokyo-night&hide_border=true&area=true&custom_title=Sarah%20Faleh%27s%20Contribution%20Graph"
  alt="Sarah Faleh contribution activity"
/>

</p>

---

# Let's Connect

<div align="center">

I'm currently looking for a **6-month PFE internship in Applied AI / Data & AI Engineering in France starting January 2027**.

<br>

<a href="https://www.linkedin.com/in/sarah-faleh/">
  <img src="https://img.shields.io/badge/LinkedIn-Sarah_Faleh-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
</a>

<a href="mailto:sarafaleh76@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white">
</a>

<br><br>

**Building AI systems that are useful, measurable and technically defensible.**

</div>
