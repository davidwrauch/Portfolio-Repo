# David Rauch — Data Scientist (Decision Systems, Causal Inference, Marketplaces)

Data scientist focused on building adaptive decision systems that connect user behavior, incentives, and business outcomes. Experience spans experimentation, causal inference, marketplace dynamics, and narrative intelligence systems, with projects emphasizing production-style pipelines and real-world decision-making under uncertainty.

---

## ⭐ Featured Projects

### Contextual Bandit Experimentation Platform (Adaptive Experimentation + OPE)

A production-style adaptive experimentation platform simulating contextual bandit decision systems with off-policy evaluation, drift monitoring, and experimentation infrastructure.

Designed to model how adaptive systems learn from user interactions while preserving rigorous evaluation and monitoring.

**Key capabilities:**
- Multiple contextual bandit policies (LinUCB, Thompson Sampling, epsilon-greedy)
- Off-policy evaluation using IPS, SNIPS, and doubly robust estimators
- Drift monitoring and behavioral diagnostics
- Structured logged bandit feedback generation
- Realistic experimentation pipelines with monitoring summaries and subgroup analysis
- FastAPI endpoints and production-style evaluation workflow

**Core decision:**
> Dynamically allocate interventions while continuously learning which strategies work best for different contexts

**Tech stack:**  
Python, FastAPI, pandas, scikit-learn, pytest, Streamlit

🔗 https://github.com/davidwrauch/Contextual-Bandit-Experimentation-Platform

---

### Political Donation Adaptive Experimentation

An adaptive experimentation prototype exploring how political messaging strategies can be evaluated and improved using contextual signals, heterogeneous treatment effects, and adaptive allocation.

Built to connect causal inference, experimentation, and political communication systems.

**Key capabilities:**
- Adaptive message experimentation framework
- Message-arm testing structure
- Context-aware intervention assignment
- Simulated donor-response environment
- Experiment logging and evaluation workflow
- Human-review-oriented experimentation design

**Core decision:**
> Learn which political message frames perform best under changing narrative environments

**Tech stack:**  
Python, pandas, causal inference methods, contextual bandits

🔗 https://github.com/davidwrauch/political-donation-adaptive-experimentation

---

### Social Listening (Narrative Intelligence + Campaign Research)

A strategist-facing social listening and narrative intelligence system built for political campaign research and adaptive experimentation workflows.

Combines public news and Reddit discussion to track which issues are gaining attention across New York regions, surface story evidence for researchers, and generate structured outputs for future experimentation systems.

**Key capabilities:**
- Real public-discourse ingestion from GDELT news + Reddit
- Regional issue monitoring across New York
- Topic trend detection and narrative-share analysis
- Strategist-facing outputs: issue briefs, polling prompts, message hypotheses
- Structured experimentation scaffolding for adaptive message testing
- Interactive visual briefing interface with linked story evidence

**Core decision:**
> Identify which narratives are gaining public attention and where campaign research or message testing should focus next

**Tech stack:**  
Python, pandas, Streamlit, Plotly, Reddit + GDELT ingestion

🔗 https://github.com/davidwrauch/social-listening

---

### Marketplace Integrity Monitor (Fraud Detection + Moderation System)

A Trust & Safety review system that identifies and prioritizes likely review manipulation using behavioral signals, anomaly detection, and explainable scoring.

**Key capabilities:**
- High-precision fraud detection combining multiple weak signals (not anomaly spam)
- Review prioritization system tuned for human moderation workflows
- Behavioral and reviewer-level features to surface manipulation patterns
- Synthetic / templated language signal for generic or copied review content
- Streamlit-based interface with persistent human-in-the-loop labeling

**Core decision:**
> Prioritize which reviews are worth a moderator’s time by focusing on high-confidence manipulation signals

**Tech stack:**  
Python, PySpark, pandas, scikit-learn, Streamlit

🔗 https://github.com/davidwrauch/Marketplace-Integrity-Monitor

---

### Market Intelligence System (ML + Pipeline + Decision Support)

A production-style data system that ingests live UK job postings, estimates expected compensation, and identifies roles and companies paying above or below market.

**Key capabilities:**
- Automated data pipeline (API ingestion → BigQuery → model updates)
- Machine learning model to estimate expected salary by role, location, and company
- Company-level aggregation to analyze compensation strategies and hiring behavior
- RAG-based LLM layer to generate grounded explanations of pay differences
- Interactive app for exploring job and company-level signals

**Core decision:**
> Prioritize job opportunities based on expected value relative to market compensation

**Tech stack:**  
Python (pandas, scikit-learn), SQL, BigQuery, Streamlit, Claude (RAG)

🔗 https://github.com/davidwrauch/UK-Market-Intelligence-System

---

## 🔬 Selected Data Science Projects

### Marketplace Labor Supply Simulator (NYC Ride-Hail Data)

Simulation of a two-sided marketplace using real NYC ride-hail data to evaluate how compensation strategies affect fulfillment, worker earnings, and platform margin.

🔗 https://github.com/davidwrauch/World-Values-Matcher

---

### World Values Matcher (ML + App)

Predicts country alignment from survey responses using machine learning and a deployed API-backed application.

🔗 https://github.com/davidwrauch/World-Values-Matcher

---

### Causal Forest Modeling

Analyzing heterogeneous treatment effects using causal forests.

🔗 https://github.com/davidwrauch/Causal-Forest-for-Estimating-Heterogeneous-Treatment-Effects

---

### Anomaly Detection in Financial Transactions

Detecting rare events in highly imbalanced datasets with practical threshold tuning.

🔗 https://github.com/davidwrauch/Anomaly-Detection-in-Financial-Transactions

---

## 🧠 Product & Data Systems (Led / Product Managed)

<details>
<summary>Click to expand</summary>

### Pedestrian Counter System  
🔗 https://github.com/davidwrauch/pedestrian-counter  

### Citygram Platform  
🔗 https://github.com/davidwrauch/citygram-services  

### Screening & Data Collection Tool  
🔗 https://github.com/davidwrauch/screenerClient  

### LinkSF (Mobility Platform)  
🔗 https://github.com/davidwrauch/linksf  

### Pi-Ano  
🔗 https://github.com/benzittlau/pi_ano  

</details>

---

## ⚙️ Skills

- **Languages:** Python, R, SQL  
- **Methods:** Causal inference, experimentation, contextual bandits, off-policy evaluation, forecasting, segmentation, anomaly detection, machine learning  
- **Data & Systems:** BigQuery, APIs, automated pipelines, feature engineering, model deployment, adaptive experimentation systems  
- **Tools:** Snowflake, Tableau, Looker, Power BI, Streamlit, FastAPI  

---

## 🌐 Links

- LinkedIn: https://www.linkedin.com/in/davidwrauch  
- GitHub: https://github.com/davidwrauch  
