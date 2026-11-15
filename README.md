# Hi there, I'm Arkanil 👋 

### 🚀 Senior AI Product Engineer | Backend & Spatial AI enthusiast
A lifelong student, curious human being. I enjoy building and solving problems that I encounter or I envision someone to encounter. I have about 10 years of experience helping organisations build scalable future ready systems. 

---

### 💻 Core Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC2626?style=for-the-badge&logo=qdrant&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)

---

### ⭐ Featured AI Systems & Repositories

| Project | Stack | Description |
| :--- | :--- | :--- |
| [**CDP RAG Assistant**](https://github.com/arkanild/cdp-rag-assistant) | `FastAPI`, `Qdrant`, `LangGraph`, `RAGAS` | In-progress - Production-grade customer data platform assistant using agentic workflows, hybrid search (BM25 + Dense), and dynamic evals. |
| [**Agentic GraphRAG System**](https://github.com/arkanild/Agentic-GraphRAG-System) | `OpenSearch`, `HyDE`, `RRF`, `NetworkX` | In-Progress - Hybrid Local & Global query router combining knowledge graphs with reciprocal rank fusion retrieval. |
| [**Spatial AI Prototype**](./projects/03-spatial-ai) | `Python`, `PostGIS`, `PyTorch` | Conceptual research - Field research & bioacoustic analysis tools for environmental conservation data processing. |
| [**Smart Resume Builder**](https://github.com/arkanild/smart_resume_builder) |` Python`, `HuggingFace` , `PyTorch` | Smart resume builder to save time and effort modifying resumes for individual roles.

---

### 🌱 Active Open Source Contributions

#### [climatechange-ai-tutorials/bioacoustic-monitoring — PR #5](https://github.com/climatechange-ai-tutorials/bioacoustic-monitoring/pull/5) · *Open*
**Batch inference pipeline, multi-source ingestion and a Streamlit review dashboard for the Climate Change AI "Agile Modeling for Bioacoustic Monitoring" tutorial.**

**The problem:** the tutorial teaches researchers to train a bird-species classifier in a Colab notebook, but there was no way to apply that classifier to new field recordings at scale, or to feed expert corrections back for retraining, without writing code.

**What the PR adds:**
- 📥 **Multi-source ingestion**: recursively reads `.wav`/`.flac` from local folders, S3/GCS buckets and public Google Drive folders
- 🧠 **Batch inference CLI**: runs the tutorial's own Perch v8 embedding model and saved linear classifier over every recording, writing a predictions manifest CSV
- 🎯 **Active-learning queue**: low-confidence clips (configurable threshold) are routed to a review queue; corrupted audio is logged and skipped without stopping the batch
- 🖥️ **Streamlit dashboard**: run the whole workflow from a browser, see summary metrics, listen to uncertain clips, correct labels, and export them back into the notebook's database for retraining
- ✅ **Verified end to end**: all 28 notebook cells run, pipeline scores match the notebook's classifier exactly, and 13 unit tests run in seconds without a GPU

**Tech stack:**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Perch](https://img.shields.io/badge/Perch_v8_(perch--hoplite)-4285F4?style=flat-square&logo=google&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![fsspec](https://img.shields.io/badge/fsspec_(S3%2FGCS)-232F3E?style=flat-square&logo=amazons3&logoColor=white)
![Google Drive](https://img.shields.io/badge/gdown_(Google_Drive)-4285F4?style=flat-square&logo=googledrive&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

<p align="left">
  <img src="./assets/bioacoustic-dashboard-summary.png" alt="Batch summary tab: files processed, high-confidence detections by species, mean confidence" width="49%" />
  <img src="./assets/bioacoustic-dashboard-review.png" alt="Human review queue: low-confidence clips with audio player and label correction" width="49%" />
</p>
<sub><i>Left: batch summary. Right: human review queue with audio playback and label correction. Results from real Powdermill soundscape recordings.</i></sub>

---

### 📊 GitHub Activity & Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=arkanild&show_icons=true&theme=tokyonight" alt="Arkanil's GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=arkanild&layout=compact&theme=tokyonight" alt="Top Languages" width="48%" />
</p>

---

### 📫 Connect with Me
- 💼 **LinkedIn:** [Arkanild](www.linkedin.com/in/arkanildutta)
- 🌐 **Location:** Madrid, Spain / Open to Remote HQP Opportunities
