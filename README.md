<!-- Header banner (free, no signup): https://github.com/kyechan99/capsule-render -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:2563eb&height=170&section=header&text=Arkanil%20Dutta&fontSize=44&fontColor=ffffff&fontAlignY=36&desc=Lead%20Data%20%26%20AI%20Engineer%20%C2%B7%20Madrid&descAlignY=58&descSize=18" width="100%" alt="Arkanil Dutta, Lead Data & AI Engineer, Madrid" />

<p align="center">
  <a href="https://www.linkedin.com/in/arkanildutta"><img src="https://img.shields.io/badge/LinkedIn-arkanildutta-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <img src="https://img.shields.io/badge/Based%20in-Madrid%2C%20Spain-c60b1e?style=flat-square" alt="Based in Madrid, Spain" />
  <img src="https://img.shields.io/badge/Open%20to-Lead%20%2F%20Staff%20roles-16a34a?style=flat-square" alt="Open to Lead / Staff roles" />
  <img src="https://img.shields.io/badge/Experience-10%2B%20years-334155?style=flat-square" alt="10+ years experience" />
</p>

<p align="center">
  <a href="https://github.com/arkanild"><img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=18&pause=1200&color=2563EB&center=true&vCenter=true&width=620&lines=I+build+data+platforms+that+don't+fall+over.;Then+I+put+LLMs+on+top+of+them+that+tell+the+truth.;Spark+%C2%B7+Kafka+%C2%B7+BigQuery+%C2%B7+FastAPI+%C2%B7+RAG+%C2%B7+evals" alt="Typing intro" /></a>
</p>

## Hi, I'm Arkanil 👋

I'm a **Lead Data & Software Engineer** with about 10 years of shipping systems that real teams depend on: batch and streaming data pipelines, the platforms underneath them, and lately the AI products built on top.

What I'm good at, in plain terms:

- **Data engineering at scale.** Spark, Kafka, BigQuery, lakehouse tables (Iceberg/BigLake). Ingest messy data, model it properly and make it cheap to query.
- **AI engineering that's measured.** RAG and agent systems with hybrid retrieval, re-ranking, caching, tracing and **evals**. I don't trust an LLM feature I can't score.
- **Product-minded backend.** FastAPI services, Postgres, Docker, CI, and tests. I care about what the user actually gets, not just the architecture diagram.
- **Leading.** <!-- TODO: replace with your real numbers, e.g. "Led a team of 6 engineers; owned the data platform for 40M customer profiles" --> Setting technical direction, reviewing designs and mentoring engineers.

> 🇪🇸 **Looking for my next role in Spain** (Madrid on-site/hybrid, or remote within Spain). I'm eligible for Spain's **Highly Qualified Professional (HQP) / EU Blue Card** permit, a fast-track process that a sponsoring employer can complete in weeks. Happy to explain how it works.

---

## 🧰 What I work with

**Data**&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Apache%20Iceberg-4E8EE9?style=flat-square&logo=apache&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
<!-- Add only if true: Airflow, dbt, Databricks, Snowflake, AWS -->

**AI / ML**&nbsp;
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![RAGAS](https://img.shields.io/badge/RAGAS-evals-0F766E?style=flat-square)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

**Backend & infrastructure**&nbsp;
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

---

## ⭐ Things I've built

### 🔎 [CDP RAG Assistant](https://github.com/arkanild/cdp-rag-assistant) · *in progress*
Customer data platform docs (Adobe Experience Platform, mParticle) are huge and fragmented, and engineers burn hours looking up identity-resolution and schema rules. This is a domain RAG assistant that answers those questions **with citations**.

- Hybrid retrieval (dense + BM25) with reciprocal rank fusion and cross-encoder re-ranking
- Parent-child chunking, a Redis semantic cache and a staleness check on source docs
- Evaluation harness: golden set, precision@k, MRR, RAGAS faithfulness, logged to BigQuery
- OpenTelemetry spans for every pipeline stage, plus a `/metrics/cost` endpoint for spend per query

`FastAPI` `Qdrant` `LangGraph` `Gemini` `Redis` `RAGAS` `BigQuery` `OpenTelemetry`
<!-- TODO: once evals run, add one line of real results here, e.g. "Faithfulness 0.91 · MRR 0.84 · p95 1.8 s". Numbers sell this project. -->

### 🐦 [Bioacoustic monitoring pipeline](https://github.com/climatechange-ai-tutorials/bioacoustic-monitoring/pull/5) · *open-source contribution to Climate Change AI*
The tutorial taught researchers to train a bird-species classifier in a notebook, but gave them no way to run it on new field recordings or feed corrections back. I turned it into a tool a non-programmer can use.

- Ingests audio from local folders, S3/GCS and Google Drive, then batch-scores it with Google's Perch v8 model
- Routes low-confidence clips to an active-learning review queue; corrupted files are logged, not fatal
- Streamlit dashboard to listen, relabel and export corrections for retraining
- Scores match the notebook exactly; 13 unit tests run in seconds without a GPU

`Python` `TensorFlow` `Perch` `Streamlit` `fsspec` `pytest`

<p align="left">
  <img src="./assets/bioacoustic-dashboard-summary.png" alt="Batch summary: files processed, high-confidence detections by species, mean confidence" width="49%" />
  <img src="./assets/bioacoustic-dashboard-review.png" alt="Review queue: low-confidence clips with audio playback and label correction" width="49%" />
</p>

### 🛠️ [daily-utils](https://github.com/arkanild/daily-utils) · *data engineering toolkit*
Small, tested building blocks I reach for at work: SFTP ingestion, BigQuery read/write in plain Python and Spark, and reusable PySpark transforms, with pytest fixtures for local Spark.

`PySpark` `BigQuery` `Bash` `pytest`

<!-- Make spark-biglake-metastore and kafka-connect public (with a README) and add them here.
     They are your best proof of "Lead Data Engineer" and nobody can currently see them. -->

---

## 🔭 What I'm doing right now

- Finishing the eval suite for **CDP RAG Assistant** and publishing the numbers
- Getting the bioacoustic pipeline reviewed and merged upstream
- Learning more about agent reliability: tool-call evals, guardrails and cost control in production

---

## 📈 Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=arkanild&theme=tokyonight&hide_border=true" alt="GitHub streak" width="49%" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=arkanild&theme=tokyo-night&hide_border=true&area=true" alt="Contribution activity graph" width="100%" />
</p>

<!-- Contribution snake, generated daily by .github/workflows/snake.yml -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/arkanild/arkanild/output/github-contribution-grid-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/arkanild/arkanild/output/github-contribution-grid-snake.svg" alt="Contribution graph being eaten by a snake" width="100%" />
</picture>

---

## 📫 Let's talk

I'm happy to talk about data platforms, RAG that has to work in production, or a role in Spain.

- 💼 **LinkedIn:** [linkedin.com/in/arkanildutta](https://www.linkedin.com/in/arkanildutta), the fastest way to reach me
<!-- - ✉️ **Email:** you@example.com  (uncomment and add your address if you want recruiters to email you directly) -->
- 📍 **Madrid, Spain** · CET · English <!-- TODO: add your Spanish level, e.g. "· Spanish (B1)" -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,100:0f172a&height=90&section=footer" width="100%" alt="" />
