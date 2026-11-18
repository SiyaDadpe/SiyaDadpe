<h1 align="center">Hey, I'm Siya ✨</h1>

<p align="center">
  CSE @ Government College of Engineering, Chhatrapati Sambhajinagar · Honors in Modern AI
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/siyadadpe/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:siyadadpe@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

I enjoy building tech that actually works: systems that are reliable, explainable, and hold up when things go wrong. Lately that means AI tools, the safety layer around coding agents, and clean full-stack products.

- 💼 Currently a frontend engineering intern at **smallcase** (since July 2026)
- 🛠️ Most of my side projects start with "this should be safer / simpler / less broken"
- 📫 Happy to chat: [siyadadpe@gmail.com](mailto:siyadadpe@gmail.com)

---

### 🔨 Things I've worked on & contributed to

#### 🛡️ [PACT — Pre-Install Agentic Code Trust Layer](https://github.com/SiyaDadpe/pact-agentic-code-trust-layer)
AI coding agents sometimes hallucinate npm package names, and attackers register those names (**slopsquatting**). PACT sits before `npm install` and decides whether a package is safe to install.
- Checks the npm registry and **OSV** advisories, then scores supply-chain risk signals (typosquat similarity, install scripts, package age, maintainer changes, hallucination corpus)
- Returns **ALLOW / WARN / BLOCK / UNKNOWN** with an explanation, fails closed, logs every decision, and has an optional Docker sandbox
- **97.09% accuracy · 0.969 F1** on 13,708 labelled npm packages

`Node.js` `JavaScript` `Docker` `OSV`

#### 🎓 [PolyGuide](https://github.com/ronit-1404/PolyGuide)
A RAG chatbot and voicebot that answers questions about polytechnic institutes: courses, hostels, and admissions.
- An LLM turns each question into a structured JSON query plan, which becomes parameterized SQL over PostgreSQL, with FAISS vector search over the institute brochure

`Python` `Flask` `FAISS` `PostgreSQL` `Gemini` `Node.js`

#### 🌾 [EnAI — Governed Agricultural Data Pipeline](https://github.com/SiyaDadpe/EnAI)
Team project: an end-to-end pipeline that turns messy agricultural CSVs into validated, ML-ready feature sets, with anomaly detection, AI-generated explanations, and a Streamlit dashboard.
- I built the data engineering and governance stage: encoding detection, schema validation, deduplication, missing-value handling, lineage tracking, and audit logs

`Python` `pandas` `scikit-learn` `Streamlit`

#### 📦 [ATLAS-FileSharing](https://github.com/SiyaDadpe/ATLAS-FileSharing) · [Live demo](https://atlas23.vercel.app)
Anonymous, self-expiring vaults for sharing files and notes, with retrieval codes, QR links, bcrypt-protected secret phrases, and one-time-view mode.

`React` `Vite` `Tailwind` `Supabase` `Vercel`

---

### 📄 Research

**Beyond Installation Blocking: An Empirical Study of Post-Intervention Behavior in Autonomous Coding Agents**<br/>
S. Dadpe, H. Mishra, V. A. Chakkarwar · *Under review*<br/>
What do coding agents do *after* a security gate blocks a dependency? Retry, switch, comply, or find a way around it?

---

### 🧰 Tech I work with

**Languages**<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black"/>
<img src="https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white"/>

**AI, ML & LLMs**<br/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/XGBoost-337AB7?style=flat"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white"/><br/>
NLP · LLMs · Prompt Engineering · Model Evaluation · SHAP · SMOTE

**Software Engineering**<br/>
<img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white"/>
<img src="https://img.shields.io/badge/Jest-C21325?style=flat&logo=jest&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"/><br/>
REST APIs · CI/CD

**Data**<br/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat"/><br/>
Exploratory Data Analysis · Statistical Analysis · Model Validation

**Security**<br/>
Cybersecurity Fundamentals · Software Supply-Chain Security · Dependency Risk Analysis · Threat Modeling

**Systems & CS**<br/>
DSA · OOP · Operating Systems · Computer Networks · COA · DBMS · Distributed Systems · Linux · Multithreading & Concurrency

---

<p align="center"><i>Thanks for stopping by ✨</i></p>
