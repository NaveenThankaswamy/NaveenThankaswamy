<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4C1D95,1:5B21B6,2:7C3AED,3:A855F7,4:C084FC&height=250&section=header&text=NAVEEN%20T%20R&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI%20%7C%20ML%20%7C%20Data%20Science%20%7C%20Full-Stack%20Engineering&descAlignY=55&descAlign=50" width="100%"/>
</div>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=24&duration=3000&pause=1000&color=A855F7&center=true&vCenter=true&width=800&lines=Building+intelligent+systems+with+ML+%26+AI;Engineering+production-ready+RAG+pipelines;Turning+data+into+decisions+with+uplift+modeling;Full-stack+developer+with+a+product+engineering+mindset" alt="Typing SVG" />
</div>

<div align="center">
  <img src="https://img.shields.io/badge/CGPA-7.5-8B5CF6?style=for-the-badge&logo=academia&logoColor=white" />
  <img src="https://img.shields.io/badge/Graduating-July%202026-7C3AED?style=for-the-badge&logo=graduation-cap&logoColor=white" />
  <img src="https://img.shields.io/badge/Bengaluru,_India-6366F1?style=for-the-badge&logo=google-maps&logoColor=white" />
</div>

<div align="center">
  <a href="https://linkedin.com/in/naveen4235">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:naveenthankaswamy07@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/NaveenThankaswamy">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=NaveenThankaswamy&color=8B5CF6&style=for-the-badge" />
  <img src="https://img.shields.io/github/followers/NaveenThankaswamy?color=7C3AED&style=for-the-badge&logo=github&label=Followers" />
  <img src="https://img.shields.io/github/stars/NaveenThankaswamy?color=A855F7&style=for-the-badge&logo=github&label=Stars" />
</div>

---

## <div align="center">About</div>

<div align="center">

Computer Science graduate working across **data science, machine learning, and AI** — not tied to one lane. Problem-first, tool-second: sometimes that's building a model, sometimes integrating an LLM, sometimes making sure the pipeline behind either one holds up.

Early career, with a clear sense of the kind of engineer I want to become. I bring a **product engineering mindset** to every project: shipping models behind APIs, containerizing services, and building interfaces that make AI accessible.

</div>

<div align="center">

**Open To:** Data Science · ML Engineering · AI Engineering · Full-Stack + AI Hybrid Roles *(Fresher Level)*

</div>

---

## <div align="center">Tech Stack</div>

<div align="center">

### Languages
<img src="https://skillicons.dev/icons?i=python" />

### Frontend
<img src="https://skillicons.dev/icons?i=react" />

### Backend & Databases
<img src="https://skillicons.dev/icons?i=fastapi,express,postgres,sqlite" />

### Cloud, DevOps & Tooling
<img src="https://skillicons.dev/icons?i=docker,git" />
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />

</div>

---

## <div align="center">AI / ML Expertise</div>

<div align="center">

| Domain | Proficiency | Details |
|--------|-------------|---------|
| **Machine Learning** | Advanced | scikit-learn, XGBoost, Logistic Regression, Uplift Modeling, SHAP, Statistical Analysis |
| **Model Evaluation** | Advanced | ROC-AUC, Qini AUC, Performance Metrics, Model Comparison |
| **Data Analysis** | Proficient | Pandas, NumPy, Matplotlib |
| **AI & LLM Engineering** | Proficient | Retrieval-Augmented Generation (RAG), Semantic Search, FAISS, SentenceTransformers |
| **Deployment & APIs** | Proficient | FastAPI, REST API Design, API-Key Auth, Docker, PostgreSQL, Streamlit |

</div>

---

## <div align="center">Featured Projects</div>

<details>
<summary><b>Churn Analytics with Uplift Modeling</b></summary>
<br>

Trained and compared churn classifiers (XGBoost: 0.9646 ROC-AUC) against three uplift models, with SoloModel achieving the best Qini AUC of 0.1708 — identifying customers where a retention offer would actually change behavior rather than just churn risk. Designed a campaign ROI simulator (expected uplift × customer lifetime value vs. offer cost) and used SHAP and Qini curves to evaluate and defend model selection. Shipped the models behind a FastAPI + PostgreSQL service with API-key auth, containerized via Docker Compose alongside a Streamlit dashboard.

| Attribute | Value |
|-----------|-------|
| **Stack** | Python, XGBoost, scikit-learn, FastAPI, PostgreSQL, Docker, Streamlit |
| **Scale** | Single-tenant API service with containerized deployment |
| **Performance** | XGBoost ROC-AUC: **0.9646** · SoloModel Qini AUC: **0.1708** |
| **Security** | API-key authentication, secure data handling |
| **Impact** | ROI-driven campaign simulator with SHAP explainability for model defense |
| **Repository** | [github.com/NaveenThankaswamy/churn-uplift-project](https://github.com/NaveenThankaswamy/churn-uplift-project) |

</details>

<details>
<summary><b>DocuMind AI — Enterprise Knowledge Assistant (RAG)</b></summary>
<br>

Full-stack RAG system (FastAPI backend) enabling PDF upload and natural-language Q&A grounded in document content, with source citation. Implemented the retrieval pipeline — chunked PDF text, SentenceTransformer embeddings, indexed in FAISS — and integrated a local LLM (Ollama, phi3:mini) with context-restricted prompts to reduce hallucination.

| Attribute | Value |
|-----------|-------|
| **Stack** | Python, FastAPI, FAISS, SentenceTransformers, Ollama (phi3:mini) |
| **Scale** | Full-stack RAG system with local LLM integration |
| **Performance** | Context-restricted prompts to reduce hallucination |
| **Security** | Document-grounded responses with source citation |
| **Impact** | Enterprise knowledge assistant enabling PDF Q&A with traceable sources |
| **Repository** | [github.com/NaveenThankaswamy/DocuMind-AI-RAG](https://github.com/NaveenThankaswamy/DocuMind-AI-RAG) |

</details>

<details>
<summary><b>EcoStream-Lite — Multi-Storefront E-Commerce Platform (LLM-Integrated)</b></summary>
<br>

Architected a multi-tenant platform (React 19, Express, SQLite) with 4 independent storefronts sharing a common admin layer. Integrated LLMs via OpenRouter for SEO copywriting, sentiment analysis, and smart customer replies. Built a React admin dashboard for cross-store analytics and content oversight.

| Attribute | Value |
|-----------|-------|
| **Stack** | React 19, Express, SQLite, OpenRouter |
| **Scale** | Multi-tenant platform with 4 independent storefronts |
| **Performance** | LLM-integrated SEO, sentiment analysis, and smart customer replies |
| **Security** | Common admin layer with cross-store oversight |
| **Impact** | Multi-storefront e-commerce with AI-powered content and analytics |
| **Repository** | [github.com/NaveenThankaswamy/ECOSTREAM-LITE](https://github.com/NaveenThankaswamy/ECOSTREAM-LITE) |

</details>

---

## <div align="center">Experience</div>

<div align="center">

### Software Engineering Intern — NexGen Innovator Solutions
*July 2025 – August 2025*

</div>

<div align="left">

- Built core backend modules — **user authentication, student registration, profile management, and secure data handling** — for a Django-based Student Portfolio Portal with generative AI features for managing student profiles, academic records, and project portfolios.
- Designed and implemented **responsive, intuitive front-end interfaces** aligned with academic usability standards; contributed to both the UI layer and the underlying data architecture.

</div>

<div align="center">

`Django` · `Python` · `Generative AI` · `Full-Stack Development` · `Secure Data Handling`

</div>

---

## <div align="center">Achievements</div>

<div align="center">

| Achievement | Organization | Year |
|-------------|--------------|------|
| *Placeholder — To be updated* | — | — |
| *Placeholder — To be updated* | — | — |
| *Placeholder — To be updated* | — | — |

</div>

---

## <div align="center">Certifications</div>

<div align="center">

### AWS
<img src="https://img.shields.io/badge/AWS-Placeholder-FF9900?style=flat-square&logo=amazon-aws&logoColor=white" />

### Oracle
<img src="https://img.shields.io/badge/Oracle-Placeholder-F80000?style=flat-square&logo=oracle&logoColor=white" />

### NPTEL
<img src="https://img.shields.io/badge/NPTEL-Placeholder-1E88E5?style=flat-square&logo=google-scholar&logoColor=white" />

### Cisco
<img src="https://img.shields.io/badge/Cisco-Placeholder-1BA0D7?style=flat-square&logo=cisco&logoColor=white" />

</div>

---

## <div align="center">Coding Profiles</div>

<div align="center">

<a href="#"><img src="https://img.shields.io/badge/LeetCode-Placeholder-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/GeeksforGeeks-Placeholder-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/HackerRank-Placeholder-00EA64?style=for-the-badge&logo=hackerrank&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/CodeChef-Placeholder-5B4638?style=for-the-badge&logo=codechef&logoColor=white" /></a>

</div>

---

## <div align="center">GitHub Analytics</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=NaveenThankaswamy&theme=midnight-purple&hide_border=true&include_all_commits=true&count_private=true&show_icons=true&rank_icon=github" height="180" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=NaveenThankaswamy&theme=midnight-purple&hide_border=true" height="180" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NaveenThankaswamy&theme=midnight-purple&hide_border=true&layout=compact&langs_count=8" height="180" />
</div>

---

## <div align="center">GitHub Trophies</div>

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=NaveenThankaswamy&theme=onestar&no-frame=true&no-bg=true&column=7&margin-w=10&margin-h=10" />
</div>

---

## <div align="center">Contribution Activity</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=NaveenThankaswamy&theme=react-dark&hide_border=true&area=true&color=A855F7&line=7C3ED&point=C084FC" />
</div>

---

## <div align="center">Contribution Snake</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/NaveenThankaswamy/NaveenThankaswamy/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/NaveenThankaswamy/NaveenThankaswamy/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/NaveenThankaswamy/NaveenThankaswamy/output/github-contribution-grid-snake.svg">
  </picture>
</div>

---

## <div align="center">Current Focus</div>

<div align="center">

```yaml
Learning:
  - Advanced MLOps & Model Serving
  - Vector Database Optimization
  - Production RAG Architectures

Building:
  - End-to-end ML pipelines with FastAPI
  - LLM-integrated full-stack applications
  - Uplift modeling & causal inference systems

Exploring:
  - Multi-agent AI systems
  - Real-time inference at scale
  - Cloud-native ML deployments

Open To:
  - Data Science roles
  - ML Engineering positions
  - AI Engineering opportunities
  - Full-stack + AI hybrid roles
</div>
<div align="center">
<div align="center">
<a href="mailto:naveenthankaswamy07@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://linkedin.com/in/naveen4235">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://github.com/NaveenThankaswamy">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
</div>
<div align="center">
  <i>"Build systems that think. Ship systems that scale."</i>
</div>
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:C084FC,1:A855F7,2:7C3AED,3:5B21B6,4:4C1D95&height=150&section=footer" width="100%"/>
</div>
```
