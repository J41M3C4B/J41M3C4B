# Hi! 👋 I'm Jaime Caballero Ponce

**Data Analyst · Business Intelligence**
Systems Engineer (coursework completed, degree in progress) · Based in Mexico 🇲🇽

🌐 [Versión en español](README.md)

I'm fascinated by how the world works and by using data to solve real problems: the ones with no solution yet, and the ones whose existing solution doesn't actually fit. I'm a multidisciplinary analyst: I bring together data, finance, psychology, science and engineering, because almost no real business problem fits in a single discipline. What I enjoy most is translating what the data says into decisions that a non-technical person can act on.

> 🔎 **I'm looking for my first role as a Data Analyst / Business Intelligence Analyst.**

---

## 🧭 How I work

* **Understand before building.** I talk to the people who live the problem and look for the root cause, because what people ask for is rarely the problem: it's a consequence of it (the "five whys" method).
* **Turn data into decisions.** Every analysis ends with a business question answered and a concrete recommendation, not just a dashboard.
* **Measure before deciding.** I run small experiments, document what worked and what didn't, and validate with real users.
* **Structure large projects.** I break the work into phases with clear completion criteria, record every important decision and its reasoning, and account for cost, risk and privacy from day one.

---

## 🚀 Main project

### 🧱 [Cimiento](https://github.com/J41M3C4B/Cimiento-Agente-de-Ingenieria-de-Proyectos-) — Data for the people nobody is looking after

**The problem.** Private-assistance institutions (nursing homes, children's homes) in Mexico lose grants, not because they don't need them, but because every funder publishes its rules in long, inconsistent PDFs, and the people who handle them (many of them nuns, with little time and no technical background) have no way to turn them into a well-framed project.

**My approach.** I came across it during my **mandatory social service** and it is now the **inspiration for my thesis**. An ERP or an off-the-shelf system wasn't the answer: for them it adds complexity and friction. So I built a tool that does the opposite: it **reduces friction**. It reads the grant calls, guides the user to the root cause of their need, and produces a budget that adds up and a guide that's ready to submit.

**Results**
* ✅ **Real use:** two institutions use it with their day-to-day grant calls.
* 📉 **Less workload:** what surprised them the most, according to their feedback (qualitative; time savings haven't been measured yet).
* 🎯 **Reliable reading:** 96–99% of citations verified on new grant calls, evaluated blind.
* 💰 **Controlled cost:** a full project with AI costs around 18 MXN, with a configurable monthly cap.
* 🔒 **Sensitive data protected:** everything runs locally and encrypted, and only aggregates reach the AI.

**Skills it shows:** requirements gathering with real users · process analysis · metric and validation design · cost analysis · decision documentation · communicating with non-technical audiences.

<details>
<summary>🔧 Technical details (if you're curious)</summary>

* **Pipeline:** PDF/Word/Excel → page-level extraction → sensitive-data scanner → reading against a canonical JSON Schema → citation verification done by code → guided diagnosis → budget computed in code → Word guide.
* **Principle:** code calculates and validates; the AI only proposes.
* **Process:** 24 documented architecture decisions (ADRs), 413 Rust tests and 95 frontend tests.
* **Stack:** Tauri 2 · Rust · React 19 · TypeScript · SQLite/SQLCipher.

</details>

*(The project's documentation is in Spanish.)*

---

## 📊 Data analysis portfolio

| Project | Business question | Finding and recommendation | Tools |
|---|---|---|---|
| **🔗 [Supply Chain Audit](https://github.com/J41M3C4B/auditoria-cadena-suministro-sql)** · [Dashboard](https://datastudio.google.com/s/pqJ-nfYmpuA) | Where are the hidden risk and cost in the supply chain? | 70.9% of spend is concentrated in one country, and some categories exceed $50 USD/kg in freight. I recommended qualifying alternative suppliers and consolidating shipments. | PostgreSQL · SQL · Looker Studio |
| **📊 [Crime Incidence in Mexico](https://github.com/J41M3C4B/Incidencia_Delictva_Mexico)** · [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiODEzYjNlMzctNWQ2Zi00N2NhLTgyOWYtNDZlZDhjODIzOGE5IiwidCI6ImIwM2EzOWY4LWVlNDAtNDk3My1hNDUwLTIyOGExYzY3YWI0YSJ9) | What is the *real* crime rate per 100k inhabitants, rather than just the total? | 3M+ records transformed to compare states and municipalities fairly and to find hot spots and trends. | PostgreSQL · Power BI · DAX |
| **📈 [E-commerce Sales](https://github.com/J41M3C4B/Ecommerce-Sales-Analysis-SQL-PowerBI)** · [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMDYwY2NmMTMtMGUzNC00YWNlLWI3YWQtYmMyNDJjNzY4ZmZiIiwidCI6ImIwM2EzOWY4LWVlNDAtNDk3My1hNDUwLTIyOGExYzY3YWI0YSJ9) | Which products and customers keep the business going? | $17.07M in sales analyzed; RFM segmentation of 5,861 customers, with a proposal to re-engage "at-risk" customers and clear out "zombie inventory". | PostgreSQL · Power BI · RFM |
| **☕ [Coffee Shop Sales](https://github.com/J41M3C4B/Cafeteria_data_analysis_Excel)** · [.xlsx file](https://github.com/J41M3C4B/Cafeteria_data_analysis_Excel/blob/main/Coffee%20Shop%20Dashboard%20(Presentacion).xlsx) | When and what sells the most? What is the average order value? | Peak hours are 8–10 a.m. and coffee leads revenue. Interactive dashboard built in Excel only. | Excel · Power Pivot · DAX |

Each repository explains its purpose and the skills it practices *(in Spanish)*.

---

## 🛠️ Toolbox

<p align="left">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Excel" />
  <img src="https://img.shields.io/badge/Looker_Studio-4285F4?style=for-the-badge&logo=looker&logoColor=white" alt="Looker Studio" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
</p>

* **Analytics & BI:** SQL (CTEs, views, normalization), Power BI, advanced DAX, star-schema modeling, RFM analysis, KPIs and data storytelling.
* **Business:** requirements gathering, process analysis, finance and cost analysis, and communicating findings to non-technical audiences.
* **Methodology:** root-cause diagnosis, small experiments, decision documentation and phased project management.
* **Complementary:** Rust, TypeScript, basic DevOps, virtualization and ERP deployment (Odoo).

---

## 📫 Let's connect

* **LinkedIn:** [jaimecaballero20](https://www.linkedin.com/in/jaimecaballero20)
* **Email:** [jaime.caballero.ponce@gmail.com](mailto:jaime.caballero.ponce@gmail.com)
