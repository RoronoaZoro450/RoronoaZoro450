<!--
  🔧 Quick setup before publishing:
  1. Create a PUBLIC repo named EXACTLY your GitHub username (e.g. github.com/yourusername/yourusername)
  2. Drop this file in as README.md — GitHub renders it automatically on your profile page
  3. Find & replace "yourusername" everywhere below with your real GitHub username
  4. Swap in your real email / LinkedIn / portfolio links
  5. Point project links at your actual repos & live demos
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Niuy&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI%20%26%20ML%20Engineer%20%7C%20Building%20Full-Stack%20Agentic%20Systems&descAlignY=55&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=22&duration=3000&pause=1000&color=6366F1&center=true&vCenter=true&width=700&lines=Multi-Agent+AI+Systems+Engineer;LangGraph+%7C+LangChain+%7C+FastAPI+%7C+Streamlit;Turning+LLM+Prototypes+into+Deployed+Products;Currently+Grinding+DSA+for+Internship+Season" /> 

</div>

<br/>

## 🚀 About Me

I'm an AI/ML builder who'd rather ship a working agent than debate architecture in a notebook. Here's what that looks like in practice:

- 🔭 Currently deep in **AlphaLens** — a multi-agent AI stock research system
- 🌱 Grinding **DSA** (NeetCode 150 / Blind 75) — arrays, strings, linked lists & stacks
- 🎯 Actively prepping for **AI/ML internship applications**
- ⚙️ I care about the stuff around the model as much as the model — Docker, real backends, real observability, not just notebooks
- 💬 Ask me about multi-agent orchestration, RAG pipelines, or LLM observability
- 📫 Reach me at **your.email@example.com**

<br/>

## 🛠️ Tech Stack

**Languages**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>

**AI / ML / LLM Orchestration**

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge"/> <img src="https://img.shields.io/badge/LangGraph-8B5CF6?style=for-the-badge"/> <img src="https://img.shields.io/badge/LangSmith-A855F7?style=for-the-badge"/> <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge"/> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>

**Backend & Data Validation**

<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white"/>

**Frontend**

<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>

**Data, Infra & Deployment**

<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"/> <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/> <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white"/>

<br/>

## 💼 Featured Projects

### 🧠 [AlphaLens — Multi-Agent AI Stock Research System](https://github.com/yourusername/alphalens)
An autonomous research desk in code — a team of LLM agents that extracts tickers, analyzes fundamentals, and synthesizes investment-grade reports, all orchestrated end-to-end with LangGraph.

- 🧩 Dedicated agents for ticker/company extraction (ChatGroq + yfinance + DuckDuckGo), financial analysis, and report synthesis
- 📈 Full observability: LangSmith tracing with `@traceable` decorators on deterministic pipeline stages, plus end-to-end token consumption tracking across every sub-agent
- 🐳 Dockerized FastAPI backend deployed on Render, Streamlit frontend on Streamlit Community Cloud — with real attention to runtime `PORT` handling and CORS
- 🧱 Lean, flat Pydantic schemas over the wire, no unnecessary nesting

<img src="https://img.shields.io/badge/LangGraph-8B5CF6?style=flat-square"/> <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square"/> <img src="https://img.shields.io/badge/LangSmith-A855F7?style=flat-square"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>

🔗 **[Live Demo](https://your-alphalens-demo.streamlit.app)** · **[Source](https://github.com/yourusername/alphalens)**

---

### 🎥 [YouTube Video RAG](https://github.com/yourusername/youtube-video-rag)
Drop in a YouTube link and chat with the video directly — answers are grounded in the actual transcript instead of guesswork.

- 🔍 Retrieval-augmented pipeline that grounds answers in real video content
- ⚡ FastAPI backend deployed on Render, Streamlit frontend for a clean chat UI

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>

🔗 **[Live Demo](#)** · **[Source](https://github.com/yourusername/youtube-video-rag)**

---

### 🕵️ [Real-Time Fraud Detection Pipeline](https://github.com/yourusername/fraud-detection-pipeline)
A streaming ML system that flags suspicious transactions as they happen, blending unsupervised anomaly detection with supervised classification.

- 🌲 Isolation Forest for anomaly detection layered with XGBoost for supervised classification
- 📡 Kafka streams live transactions, Redis serves low-latency feature lookups
- 🗄️ PostgreSQL for persistence, Docker Compose for orchestration, Grafana dashboards for live monitoring
- 📚 Trained and evaluated on the IEEE-CIS Fraud Detection dataset

<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/> <img src="https://img.shields.io/badge/XGBoost-5B21B6?style=flat-square"/> <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/>

🔗 **[Source](https://github.com/yourusername/fraud-detection-pipeline)**

<br/>

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&theme=tokyonight&hide_border=true" width="48%"/>

<img src="https://streak-stats.demolab.com?user=yourusername&theme=tokyonight&hide_border=true" width="70%"/>

<img src="https://github-profile-trophy.vercel.app/?username=yourusername&theme=tokyonight&no-frame=true&row=1&column=6" width="98%"/>

</div>

<br/>

## 🤝 Connect With Me

<div align="center">

<a href="https://linkedin.com/in/yourprofile"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:your.email@example.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://yourportfolio.com"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/></a>

</div>

<br/>

<div align="center">

<img src="https://komarev.com/ghpvc/?username=yourusername&style=for-the-badge&color=6366F1&label=Profile+Views"/>

<sub>💡 Bonus: want the animated contribution snake too? Set up <a href="https://github.com/Platane/snk">Platane/snk</a> (a small GitHub Action, ~2 min), then add:<br/><code>![snake](https://raw.githubusercontent.com/yourusername/yourusername/output/github-contribution-grid-snake.svg)</code></sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" width="100%"/>

</div>
