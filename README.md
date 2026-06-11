<h1 align="center">👋 Hi, I'm YUYANG WEI</h1>

<p align="center">
  🎓 Information Technology Student @ UWA (Expected 2026)<br>
  🤖 Building <strong>LLM-powered multi-agent systems</strong> — orchestration, Function Calling, RAG, and observability<br>
  💻 Full-stack foundation: Python · FastAPI · Vue · Node.js
</p>


---

## 🚀 Core Tech Stack

<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="50" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="50" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="50" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original.svg" width="50" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original.svg" width="50" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flask/flask-original.svg" width="50" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" width="50" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sqlite/sqlite-original.svg" width="50" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="50" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="50" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" width="50" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LLM-Function%20Calling-E07B39" />
  <img src="https://img.shields.io/badge/RAG-BM25%20%2B%20Vector-6A9A78" />
  <img src="https://img.shields.io/badge/Multi--Agent-Orchestration-C95F39" />
  <img src="https://img.shields.io/badge/Observability-Tracing%20%2B%20SSE-8D6C4E" />
</p>


---

## 🌟 Featured Projects

### ✈️ WanderWarm: Multi-Agent Travel Planner

> A 7-agent travel planning system with a real-time web demo — enter budget, dates and style;
> agents collaborate to recommend a destination, search flights/hotels/activities in parallel,
> and autonomously re-plan when over budget.
>
> - **Orchestration**: Pipeline + parallel execution (asyncio) + evaluator-optimizer budget loop,
>   agents communicate via a shared state (blackboard pattern) driven by a state machine
> - **ReplanAgent (true agent)**: an LLM **Function Calling loop** decides which search tools to
>   call and with what constraints when over budget — guarded by step limits, code-owned budget
>   math, and final code verification; falls back to rule-based degradation on LLM failure
> - **RAG-enhanced recommendation**: semantic chunking, query rewriting, BM25 + vector dual
>   retrieval with automatic fallback, citation-grounded generation to reduce hallucination
> - **Observability**: self-built tracing (OpenTelemetry-style span tree via `contextvars`),
>   token accounting, plus an **SSE event stream** that visualizes every agent step live in the browser
> - **Engineering**: 56 tests (scripted stub-LLM for agent-loop termination), graceful degradation
>   at every layer, deployed on Alibaba Cloud with cost-protection access keys
>
> ✅ Open-source: [multi-agent-travel-planner](https://github.com/SayHiToYoung/multi-agent-travel-planner)

---

### 🧠 AuraWell: AI-Driven Health Orchestration Agent

> A personalized health agent platform that integrates user routines, fitness goals, preferences, and schedule.  
>
> - **Core Features**:
>   - Integrated with **DeepSeek AI** for contextual health recommendations
>   - Standardized health data model supporting multi-platform input
>   - Comprehensive user health profile management
>   - Gamification engine with achievements and daily challenges
>   - Privacy-first design under R.A.I.L.G.U.A.R.D principles  
>     ✅ Open-source: [AuraWell_Agent Repository](https://github.com/PrescottClub/AuraWell_Agent)

---

### 🛠️ Admin Management System

> A full-featured admin dashboard built with Vue.js and Element UI.  
>
> - **Frontend**: Vue 2, Element UI, Vuex, Vue Router, Webpack  
> - **Backend**: Node.js (node-elm), RESTful APIs  
>   ✅ Role-based access control, product/shop management, data dashboards, WYSIWYG editors.

---

### 🧘‍♂️ Fitness Tracking Website

> Team project for tracking and visualizing user fitness data.  
>
> - Backend: **Flask** and **SQLite**  
>   ✅ Responsible for data acquisition and visual chart generation.

---

### 👶 Smart Cradle Monitoring System

> An AIoT-based real-time monitoring system for infant safety.  
>
> - Hardware: Raspberry Pi, pressure/sound/temperature sensors, LED, camera  
> - Software: **Python**, **Flask**, **Twilio**, **SMTP**  
>   ✅ Detects abnormal status and sends real-time alerts via email/SMS.  
>   ✅ Features real-time dashboard, alert indicators, and customizable config.

---

## 🧑‍💼 Internship Experience

### 🛍️ Shopify-based E-commerce Platform Intern (2024)

> Operated and maintained a Shopify store for local Australian clients.  
> ✅ Optimized product listings, implemented SEO strategies  
> ✅ Configured lazy image loading, handled CSV-based product imports  
> ✅ Ensured platform stability and content protection

---

## 📫 Let's Connect

📧 Email: weiyuyang250@outlook.com  
🌍 GitHub: [SayHiToYoung](https://github.com/SayHiToYoung)

---

<p align="center">✨ Thanks for visiting my profile! Let’s build meaningful tech together. ✨</p>
