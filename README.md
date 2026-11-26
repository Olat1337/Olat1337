<div align="center">
  <h1>Kyrylo Kudrevych</h1>
  <h3>ML, Data Science, AI & SWE Builder | Section Leader @ GHOST | Bioinformatics @ PUT</h3>
  <p>Building end-to-end ML, Data Science, RAG, and Backend Applications.<br>
  <b>Open to ML, Data Science, AI Engineering & SWE Internships</b> (Poland or Remote EU · Available immediately, flexible hours)</p>

  <a href="https://www.linkedin.com/in/kyrylo-kudrevych/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:kyrylo.kudrevych@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</div>

---

### About

Bioinformatics undergraduate at Poznan University of Technology focused on **Machine Learning, Data Science, AI Engineering, and Software Engineering**. I work across both sides of the stack: modeling and statistics from first principles, and the Python APIs, data pipelines, and CI/CD workflows that ship them as working software.

- **Leadership:** Section Leader (**End-to-End Data Science** — mentoring ~14 active builders; **Intro to ML** — launched with 47 attendees) & Board Secretary at **GHOST** (PUT's ML scientific circle). Also on the Sponsors Team for **GHOST Day: AMLC 2027**.
- **Education:** B.Sc. in Bioinformatics, Poznan University of Technology (Oct 2024 – Apr 2028) — Data Structures, Algorithms, Relational Databases (SQL), Statistics.
- **Certifications:** NVIDIA DLI — Fundamentals of Deep Learning (2025); Kaggle Learn — Advanced SQL, Intermediate ML & Time Series (2026).
- **Languages:** English (C1), Polish (C1), Ukrainian (Native), Russian (Bilingual).
- **Contact:** [kyrylo.kudrevych@gmail.com](mailto:kyrylo.kudrevych@gmail.com) | [LinkedIn](https://www.linkedin.com/in/kyrylo-kudrevych/)

---

### Tech Stack

**Languages & Data**  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C6984?style=for-the-badge)

**Machine Learning & AI**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=for-the-badge&logoColor=black)
![Optuna](https://img.shields.io/badge/Optuna-2563EB?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-111827?style=for-the-badge&logo=ollama&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-F9AB00?style=for-the-badge&logo=huggingface&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-10B981?style=for-the-badge)

**Backend, MLOps & Tooling**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

### Featured Projects

#### [Poznań Rent Radar — End-to-End Rental Price Prediction Service](https://github.com/Olat1337/poznan-rent-radar)
`Python` · `CatBoost` · `Optuna` · `Scikit-Learn` · `FastAPI` · `Streamlit` · `CI/CD`
- Engineered an automated scraping, cleaning, and feature-engineering pipeline over ~1,000 live Poznań rental listings.
- Benchmarked linear and gradient boosting models on log-transformed target prices with Optuna tuning; selected **CatBoost (~307 PLN validation MAE)** to capture non-linear feature interactions.
- Built the inference service as a **FastAPI** backend with a **Streamlit** UI and an automated Railway CI/CD pipeline.

#### [Poker Tournament Judge — Offline-First Local RAG Assistant](https://github.com/Olat1337/poker-judge)
`Python` · `LangChain` · `Llama 3 (Ollama)` · `ChromaDB` · `HuggingFace` · `aiogram`
- Built a fully local Retrieval-Augmented Generation (RAG) system over the official TDA Poker Rulebook using LangChain, Hugging Face embeddings, ChromaDB, and Llama 3 via Ollama.
- Delivered as an async Telegram bot (`aiogram`) with per-chat conversation memory and rule-grounded citations at zero external API cost.
