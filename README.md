<div align="center">
  <h1>Hi there, I'm Kyrylo Kudrevych 👋</h1>
  <h3>Bioinformatics Student @ PUT | Data & Software Engineering</h3>
  <p><i>Building deployed ML & RAG projects | Seeking 2026 Data/ML/SWE Internship</i></p>
  
  <a href="https://kyrylo-kudrevych-portfolio.up.railway.app/">
    <img src="https://img.shields.io/badge/View_Interactive_Portfolio-10b981?style=for-the-badge&logo=openai&logoColor=white" />
  </a>

  <br><br>

  <img src="https://img.shields.io/badge/Machine%20Learning-009688?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Data%20Engineering-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG%20Systems-FF6F00?style=for-the-badge&logo=langchain&logoColor=white" />
</div>

### 👨‍💻 About Me
I am a Bioinformatics student at Poznan University of Technology focused on machine learning and data application development. I learn by building complete projects and deploying them as working applications. I am actively seeking a data, machine learning, or software engineering internship for 2026/2027. I am open to opportunities in Poland and remote across the EU.

- 🧬 **Education:** B.Sc. in Bioinformatics, Poznan University of Technology (Expected Apr 2028).
- 🏆 **Certifications:** NVIDIA DLI - Fundamentals of Deep Learning (2025); Kaggle - Advanced SQL, Intermediate ML, Time Series (2026).
- 🧠 **Experience:** Member of the Data Science Section at GHOST Student Scientific Circle and KNBI Bioinformatics Student Association.
- 📫 **Contact:** [kyrylo.kudrevych@gmail.com](mailto:kyrylo.kudrevych@gmail.com)

### 🛠️ Tech Stack & Tools

**Languages & Databases**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Machine Learning & AI**<br>
![Scikit-Learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch_(Learning)-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-FFFFFF?style=for-the-badge&logo=ollama&logoColor=black)
![HuggingFace](https://img.shields.io/badge/HuggingFace-F9AB00?style=for-the-badge&logo=huggingface&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-12B981?style=for-the-badge&logo=chroma&logoColor=white)

**Data Engineering & Visualization**<br>
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C6984?style=for-the-badge&logo=python&logoColor=white)

**Frameworks & Tools**<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### 🚀 Projects

#### 🏡 Poznań Rent Radar: Real Estate Valuation Engine
**[👉 View Live Demo](https://poznan-rent-radar-ui.up.railway.app/)** | **[🔗 View Source Code](https://github.com/Olat1337/poznan-rent-radar)**
A rent price estimator for the Poznań market.
* **Stack:** Python, FastAPI, Streamlit, Scikit-Learn, CatBoost
* **Highlights:**
  * Scrapes rental listings, trains a CatBoost model (validation MAE ~307 PLN), and serves predictions through a FastAPI API.
  * Compared several models and chose CatBoost because it gave the best results on the dataset.
  * Deployed with Railway and set up a simple CI/CD pipeline for automatic updates.

#### 🃏 Poker Tournament Judge AI: RAG-Powered Rule Enforcer
**[🔗 View Source Code](https://github.com/Olat1337/poker-judge)**
A local RAG application that answers rule disputes based on the official TDA poker rulebook.
* **Stack:** LangChain, Llama 3, ChromaDB, aiogram
* **Highlights:**
  * Delivered as an async Telegram bot running fully offline via Ollama, with responses perfectly grounded in retrieved rule citations.
  * Selected local inference via Ollama over API-based models to keep the system fully offline and free of per-request costs.
