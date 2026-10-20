<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b26,100:7aa2f7&height=210&section=header&text=Hamid%20Raza%20Bajwa&fontSize=46&fontColor=c0caf5&fontAlignY=40&desc=CS%20Student%20%E2%80%A2%20Math-First%20ML%20Builder%20%E2%80%A2%20Agent%20Engineer&descAlignY=60&descSize=17" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1000&color=7DCFFF&center=true&vCenter=true&width=700&lines=Deriving+the+math+before+I+trust+the+library;Auditing+every+notebook+for+leakage+before+it+ships;Building+agents+on+Google+ADK%2C+Gemini+and+OpenAI;Serving+models+with+FastAPI+and+Docker;No+shortcuts%2C+no+fit()+until+I've+derived+it+myself" />

<br>

<a href="https://www.linkedin.com/in/hamidrazabajwa49"><img src="https://img.shields.io/badge/LinkedIn-1a1b26?style=for-the-badge&logo=linkedin&logoColor=7aa2f7" /></a>
<a href="https://x.com/hs_developers18"><img src="https://img.shields.io/badge/X-1a1b26?style=for-the-badge&logo=X&logoColor=bb9af7" /></a>
<a href="mailto:hamidrazabajwa49@gmail.com"><img src="https://img.shields.io/badge/Email-1a1b26?style=for-the-badge&logo=gmail&logoColor=7dcfff" /></a>

</div>

<br>

## ⚡ Tech Stack

<table width="100%">
<tr>
<td width="25%" valign="top">

**🧠 ML / Data**

![PyTorch](https://img.shields.io/badge/PyTorch-1a1b26?style=flat-square&logo=PyTorch&logoColor=7aa2f7)
![JAX](https://img.shields.io/badge/JAX-1a1b26?style=flat-square&logoColor=bb9af7)
![sklearn](https://img.shields.io/badge/sklearn-1a1b26?style=flat-square&logo=scikit-learn&logoColor=bb9af7)
![XGBoost](https://img.shields.io/badge/XGBoost-1a1b26?style=flat-square&logoColor=7dcfff)
![Optuna](https://img.shields.io/badge/Optuna-1a1b26?style=flat-square&logoColor=c0caf5)
![NumPy](https://img.shields.io/badge/NumPy-1a1b26?style=flat-square&logo=numpy&logoColor=7dcfff)
![Pandas](https://img.shields.io/badge/Pandas-1a1b26?style=flat-square&logo=pandas&logoColor=c0caf5)
![Matplotlib](https://img.shields.io/badge/Matplotlib-1a1b26?style=flat-square&logo=Matplotlib&logoColor=9ece6a)

</td>
<td width="25%" valign="top">

**🤖 GenAI / Agents**

![Google ADK](https://img.shields.io/badge/Google%20ADK-1a1b26?style=flat-square&logo=google&logoColor=7aa2f7)
![Gemini](https://img.shields.io/badge/Gemini-1a1b26?style=flat-square&logo=googlegemini&logoColor=bb9af7)
![OpenAI](https://img.shields.io/badge/OpenAI-1a1b26?style=flat-square&logo=openai&logoColor=7dcfff)
![LangChain](https://img.shields.io/badge/LangChain-1a1b26?style=flat-square&logo=langchain&logoColor=9ece6a)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-1a1b26?style=flat-square&logo=huggingface&logoColor=c0caf5)
![MCP](https://img.shields.io/badge/MCP-1a1b26?style=flat-square&logoColor=7aa2f7)

</td>
<td width="25%" valign="top">

**💻 Languages / Backend**

![Python](https://img.shields.io/badge/Python-1a1b26?style=flat-square&logo=python&logoColor=7aa2f7)
![C++](https://img.shields.io/badge/C++-1a1b26?style=flat-square&logo=c%2B%2B&logoColor=bb9af7)
![FastAPI](https://img.shields.io/badge/FastAPI-1a1b26?style=flat-square&logo=fastapi&logoColor=9ece6a)
![Flask](https://img.shields.io/badge/Flask-1a1b26?style=flat-square&logo=flask&logoColor=7dcfff)
![Streamlit](https://img.shields.io/badge/Streamlit-1a1b26?style=flat-square&logo=streamlit&logoColor=bb9af7)

</td>
<td width="25%" valign="top">

**☁️ Cloud / DB / Tools**

![MySQL](https://img.shields.io/badge/MySQL-1a1b26?style=flat-square&logo=mysql&logoColor=7aa2f7)
![Supabase](https://img.shields.io/badge/Supabase-1a1b26?style=flat-square&logo=supabase&logoColor=9ece6a)
![Docker](https://img.shields.io/badge/Docker-1a1b26?style=flat-square&logo=docker&logoColor=7dcfff)
![Terraform](https://img.shields.io/badge/Terraform-1a1b26?style=flat-square&logo=terraform&logoColor=bb9af7)
![Git](https://img.shields.io/badge/Git-1a1b26?style=flat-square&logo=git&logoColor=c0caf5)

</td>
</tr>
</table>

**🎯 How I work:** derive it from math first, fit the library second, audit the metric before I believe it. Agents are built at the API level (Gemini, OpenAI) while I still trust myself more than the abstraction on top.

<br>

## 🔭 Flagship Builds

<table width="100%">
<tr>
<td width="100%" valign="top">

### 🤖 Lead Qualifier Agent

Multi-agent lead-qualification pipeline on **Google ADK**, capstone for the **Google × Kaggle 5-Day AI Agent Intensive**.
inbound lead → security checkpoint → enricher → scorer → human review


A security checkpoint sub-agent handles prompt-injection detection and PII redaction, enrichment and scoring sub-agents run via AgentTool with a custom MCP toolset, and low-confidence leads route to a human instead of auto-approving. Deployed with Docker + Terraform.

**[→ github.com/hamidrazabajwa49/lead-qualifier-agent](https://github.com/hamidrazabajwa49/lead-qualifier-agent)**

</td>
</tr>
<tr>
<td width="100%" valign="top">

### 🍷 Wine Quality API

A model served properly, not just trained. Random Forest on UCI Red Wine Quality behind **FastAPI**, with a **Streamlit** front end, **Docker** packaging and 14 tests. The API returns a tree-spread confidence band, warns on out-of-range inputs, and drops duplicates before the split.

`Test MAE 0.467 vs 0.705 baseline`

**[→ github.com/hamidrazabajwa49/wine-quality-api](https://github.com/hamidrazabajwa49/wine-quality-api)**

</td>
</tr>
<tr>
<td width="100%" valign="top">

### 📐 ML/AI Systems, Built From Scratch

Machine learning, deep learning and statistics implemented from mathematical first principles in pure Python, with no `sklearn.fit()` shortcuts and no NumPy/SciPy/scikit-learn at runtime. Each system ships with its own README, derivations and unit tests.

Covers linear algebra, probability, Bayesian inference, optimization and information theory, through to t-test, chi-square, ANOVA, and linear/logistic regression.

**[→ github.com/hamidrazabajwa49/ml-implementation-from-scratch](https://github.com/hamidrazabajwa49/ml-implementation-from-scratch)**

</td>
</tr>
<tr>
<td width="100%" valign="top">

### 🔥 Deep Learning, From First Principles

Progressive PyTorch curriculum: tensors, autograd, custom `nn.Module`s, `Dataset`/`DataLoader` pipelines, full training loops, and ANN/CNN image classifiers on Fashion MNIST. Includes GPU support, LR scheduling, per-class metrics and Optuna-based hyperparameter tuning.

**[→ github.com/hamidrazabajwa49/deep-learning](https://github.com/hamidrazabajwa49/deep-learning)**

</td>
</tr>
</table>

<br>

## 🚀 Shipped to Real Users

<table width="100%">
<tr>
<td width="50%" valign="top">

**🧾 Wallet Shop Ledger**

Built after watching a shop owner spend 30 to 40 minutes tallying a paper register every night, then throwing the data away. Each sale is logged in about a minute. After a free 7-day trial, the owner bought premium.

</td>
<td width="50%" valign="top">

**🏥 Clinic Token System**

A queue and token system sold to private clinics and hospitals.

</td>
</tr>
</table>

<br>

## 🗂️ Portfolio Highlights: Leakage Audits

I audit every pipeline for leakage and publish the corrected, lower number instead of the inflated one.

<table width="100%">
<tr>
<td width="33%" valign="top">

**🗳️ Pakistan Elections**

Found a feature mathematically guaranteed to equal 1.0 for every winner. Rebuilt leakage-free.

`ROC-AUC 0.9995 → 0.9093`

**[→ Repo](https://github.com/hamidrazabajwa49/pakistan-elections-win-prediction)**

</td>
<td width="33%" valign="top">

**🚦 NYC Traffic Volume**

Caught a same-day traffic-count leak from two mismatched fiscal-year datasets. Rebuilt with a history baseline recomputed inside each CV fold.

`R² 0.99 → 0.74`

**[→ Repo](https://github.com/hamidrazabajwa49/nyc-traffic-volume-prediction)**

</td>
<td width="33%" valign="top">

**🏏 T20 Cricket Batting**

Removed leaked features from a batting-performance model and reported the honest score.

`R² 0.98 → 0.782`

**[→ Repo](https://github.com/hamidrazabajwa49/t20-cricket-batting-prediction)**

</td>
</tr>
<tr>
<td width="33%" valign="top">

**👔 HR Promotion**

Corrected a leaky promotion classifier instead of shipping the flattering metric.

`F1 0.516 → 0.472`

</td>
<td width="33%" valign="top">

**💳 Credit Card Fraud**

A model hit 1.000 PR-AUC. Instead of celebrating, I audited it feature by feature and traced it to synthetic-data separability, not leakage.

`Verified, not assumed`

</td>
<td width="33%" valign="top">

**🚢 Titanic DS Pipeline**

End-to-end pipeline: cleaning, significance testing, a 4-model comparison and a live Streamlit dashboard.

**[→ Repo](https://github.com/hamidrazabajwa49/titanic-ds-pipeline)**

</td>
</tr>
</table>

<br>

## 💼 Experience

- **ML Intern, FlyRank AI** (remote, Jul to Sep 2026): built a search-content review-priority model that lifted Precision@50 from about 0.24 (hand-rule baseline) to about 0.74, using a client-holdout split. Earned AI Fluency and Machine Learning completion certificates. **[→ Repo](https://github.com/hamidrazabajwa49/flyrank-ml-internship)**
- **Data Science and ML Intern, GIST** (remote): four-task data science track plus an ML track with four end-to-end projects, including a FastAPI-deployed regression model. **[→ ML track repo](https://github.com/hamidrazabajwa49/ml-project-basics-to-deployment)**

<br>

## 🧪 Right Now

- Daily build sprint: one fresh ML/DL project plus one agentic AI concept, pushed to GitHub every day
- Learning agent frameworks (LangGraph), practical MCP, guardrails and evaluations
- Following Karpathy's *Zero to Hero* and implementing papers from scratch
- Working through the Google × Coursera AI and data analytics certificates

<br>

## 📊 GitHub Stats

<table width="100%">
<tr>
<td width="50%"><img width="100%" src="https://github-readme-stats.vercel.app/api?username=hamidrazabajwa49&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&show_icons=true" /></td>
<td width="50%"><img width="100%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hamidrazabajwa49&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&layout=compact" /></td>
</tr>
<tr>
<td width="50%"><img width="100%" src="https://nirzak-streak-stats.vercel.app/?user=hamidrazabajwa49&theme=tokyonight&hide_border=true" /></td>
<td width="50%" valign="middle" align="center">

**🏆 Trophy Case**

<img width="100%" src="https://github-profile-trophy.vercel.app/?username=hamidrazabajwa49&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4&row=2&column=3" />

</td>
</tr>
</table>

<br>

## 🎯 Beyond the Code

<table width="100%">
<tr>
<td width="33%" align="center">

**♟️ Chess**
<br>pattern recognition, several moves out

</td>
<td width="33%" align="center">

**🏋️ Calisthenics**
<br>discipline easier to keep than to start

</td>
<td width="33%" align="center">

**🔭 Quantum & Astro**
<br>the fabric of reality, purely for curiosity

</td>
</tr>
</table>

<br>

## 🤝 Let's Collaborate

Open to working on:
- Agent pipelines built directly on LLM APIs (Gemini, OpenAI)
- Math-heavy ML implementations: loss functions, optimizers, from scratch
- Serving ML models as clean, tested APIs
- Turning research papers into runnable code

Reach out via [LinkedIn](https://www.linkedin.com/in/hamidrazabajwa49) or [email](mailto:hamidrazabajwa49@gmail.com).

<div align="center">
<br>

[![](https://visitcount.itsvg.in/api?id=hamidrazabajwa49&icon=6&color=7)](https://visitcount.itsvg.in)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,100:1a1b26&height=110&section=footer" />

</div>
