<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,100:2563eb&height=180&section=header&text=Weishan%20Li&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Data%20Pipelines%20%C2%B7%20SQL%20%C2%B7%20Analytics%20%C2%B7%20Full-Stack&descAlignY=58&descSize=18" width="100%" alt="Weishan Li" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=2563EB&center=true&vCenter=true&width=600&lines=Master+of+IT+(AI)+Graduate+%40+UWA;I+turn+messy+data+into+clean+tables+and+dashboards;Python+%7C+SQL+%7C+dbt+%7C+FastAPI+%7C+Power+BI;Open+to+Graduate+%2F+Junior+roles+in+Perth" alt="typing" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/📍_Perth,_WA-1e3a8a?style=for-the-badge" />
  <img src="https://img.shields.io/badge/UWA-MIT_(AI)_2024–2026-2563eb?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Open_to-Graduate_%2F_Junior_Roles-2ea44f?style=for-the-badge" />
  <br/>
  <a href="mailto:SSLA2002@outlook.com"><img src="https://img.shields.io/badge/Email-SSLA2002@outlook.com-D14836?style=for-the-badge&logo=microsoftoutlook&logoColor=white" /></a>
  <!-- <a href="https://www.linkedin.com/in/your-id"><img src="https://img.shields.io/badge/LinkedIn-Weishan_Li-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a> -->
</p>

---

## 👩‍💻 About Me

I'm a recent **Master of Information Technology (AI)** graduate from the **University of Western Australia**. I like the part of a project where raw, inconsistent data becomes something people can trust and use: cleaning and de-duplicating records, designing the database, exposing it through an API, and showing it in a chart.

- 🔭 In my capstone I built the **silver → gold data layers**, the **job search APIs** and the **Market Trends dashboard** for an autonomous-vehicle job platform ([live demo](https://av-c3eqb29wm-husthunterpy01s-projects.vercel.app))
- 🥗 My **Food Science** undergraduate degree gives me domain knowledge for food and manufacturing organisations
- 🎯 Looking for **Graduate / Junior Data Analyst, Business / Systems Analyst or IT roles in Perth**
- 🌏 Mandarin (native) · English (professional)

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,java,ts,js,postgres,sqlite,supabase,fastapi,flask,react,nextjs,tailwind,docker,githubactions,vercel,git&perline=8" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />
  <img src="https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white" />
</p>

| Area | Skills |
|---|---|
| **Data & Databases** | PostgreSQL, SQL migrations, ERD / star-schema design, dbt, data cleaning & de-duplication, Power BI |
| **Backend** | Python, FastAPI, Flask, SQLAlchemy, REST APIs, pytest |
| **Frontend** | Next.js, React, TypeScript, Tailwind CSS, accessibility (WCAG) |
| **AI / ML** | Machine Learning, NLP, Deep Learning, nature-inspired optimisation |
| **Ways of working** | Git/GitHub flow (issues → PRs → review), CI with GitHub Actions, Docker, client liaison |

---

## 🚀 Featured Project

### 🚗 Autonomous Vehicle Job Profiles &nbsp;·&nbsp; *CITS5206 Capstone, UWA (team of 5)*

> **What is the autonomous vehicle industry hiring for, and which skills should students learn next?**

<p>
  <a href="https://av-c3eqb29wm-husthunterpy01s-projects.vercel.app"><img src="https://img.shields.io/badge/Live_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="https://github.com/husthunterpy01/Autonomous_Vehicle_Job_Profiles_Group3"><img src="https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/My_merged_PRs-26-2ea44f?style=for-the-badge" />
</p>

A job board and skill-trend dashboard built from public job ads of AV companies. Jobs flow through a **bronze → silver → gold** pipeline and are served by FastAPI to a Next.js frontend.

```
ATS APIs ─► Scrapers ─► MinIO (bronze) ─► Cleaning + LLM (silver) ─► dbt (gold)
                                                                        │
                                      Next.js ◄── FastAPI ◄── PostgreSQL
```

<p align="center">
  <img src="https://raw.githubusercontent.com/husthunterpy01/Autonomous_Vehicle_Job_Profiles_Group3/main/media/skill_trends.png" width="85%" alt="Market Trends: monthly skill demand" />
  <br/><sub><i>Market Trends page I built: job postings per skill per month, from the gold star schema</i></sub>
</p>

**What I built**

- 🧹 **Silver-layer cleaning & de-duplication** — required fields, HTML stripping, timestamp / employment-type / location normalisation, and a 3-level de-duplication key that keeps the most complete record ([#83](https://github.com/husthunterpy01/Autonomous_Vehicle_Job_Profiles_Group3/pull/83))
- ⭐ **Gold star schema with dbt** — fact and dimension tables for monthly skill demand, synced to its own PostgreSQL database ([#136](https://github.com/husthunterpy01/Autonomous_Vehicle_Job_Profiles_Group3/pull/136))
- 📈 **Skill-trend API + interactive chart** — `GET /trends/skills`, a line chart with highlight, zoom/pan, keyboard navigation and a table view ([#143](https://github.com/husthunterpy01/Autonomous_Vehicle_Job_Profiles_Group3/pull/143))
- 🔌 **Backend integration** — loaded silver jobs into normalised tables with stable job identity and versioned categories, behind list/detail/filter APIs ([#87](https://github.com/husthunterpy01/Autonomous_Vehicle_Job_Profiles_Group3/pull/87))
- 🌍 **Exact country filter** — parsed 154 free-text location labels into countries for all 1,229 live jobs (handling clashes like `IL` = Illinois vs Israel) ([#152](https://github.com/husthunterpy01/Autonomous_Vehicle_Job_Profiles_Group3/pull/152), [#153](https://github.com/husthunterpy01/Autonomous_Vehicle_Job_Profiles_Group3/pull/153))
- 💰 **Salary rules in the database** — check constraints, migrations with rollbacks, and a documented salary model ([#115](https://github.com/husthunterpy01/Autonomous_Vehicle_Job_Profiles_Group3/pull/115))
- 🖥️ **Frontend** — landing page, job search and company list MVP, the Find Jobs table with sorting/pagination, and real data on the homepage ([#27](https://github.com/husthunterpy01/Autonomous_Vehicle_Job_Profiles_Group3/pull/27), [#118](https://github.com/husthunterpy01/Autonomous_Vehicle_Job_Profiles_Group3/pull/118), [#134](https://github.com/husthunterpy01/Autonomous_Vehicle_Job_Profiles_Group3/pull/134))
- ♿ **Quality** — accessibility audit and fixes, and a data-quality sample check ([#180](https://github.com/husthunterpy01/Autonomous_Vehicle_Job_Profiles_Group3/pull/180), [#166](https://github.com/husthunterpy01/Autonomous_Vehicle_Job_Profiles_Group3/pull/166))
- 🤝 **Client liaison** — requirements gathering, meeting minutes and progress reporting; 22 issues written to plan and track work

<sub>**Stack:** Python · PostgreSQL · dbt · MinIO · FastAPI · Next.js · TypeScript · Tailwind · Docker · GitHub Actions · Vercel</sub>

---

## 📂 More Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📈 Stock Trading Simulator</h3>
      <i>CITS5505 Agile Web Development · team project</i>
      <p>A browser-based trading simulator with long/short trading, simulated live prices, leaderboards and achievements.</p>
      <ul>
        <li>Built the login & registration flow with <b>WTForms + CSRF protection</b></li>
        <li><b>Salted password hashing</b> and <b>hashed reset codes</b> with expiry and attempt limits</li>
        <li>Frontend pages and UI, trade history view</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" />
        <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" />
        <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
      </p>
      <a href="https://github.com/ElliotZhangzr/CITS5505_project_1">🔗 View on GitHub</a>
    </td>
    <td width="50%" valign="top">
      <h3>🤖 AI Trading Bots</h3>
      <i>CITS4404 AI & Adaptive Systems · team of 4</i>
      <p>Trading bots for BTC/USDT using Weighted Moving Average crossover signals, tuned with <b>nature-inspired optimisation algorithms</b> and backtested on historical data.</p>
      <ul>
        <li>Part 1: literature review, one synopsis per member</li>
        <li>Part 2: implementation and backtesting of the bots</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
      </p>
      <a href="https://github.com/Jiongge390/CITS4404Group4">🔗 View on GitHub</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🏙️ Urban Growth Simulation</h3>
      <i>CITS4403 Computational Modelling · team project</i>
      <p>A Python cellular-automata / agent-based model of urban growth, with a <b>travel-cost model</b> and an <b>agent-based zoning model</b> for residential, commercial and industrial land.</p>
      <a href="https://github.com/KelseyOnGit/CITS4403-Project">🔗 View on GitHub</a>
    </td>
    <td width="50%" valign="top" align="center">
      <img src="https://raw.githubusercontent.com/KelseyOnGit/CITS4403-Project/main/city_sprawl_animation.gif" width="90%" alt="City sprawl animation" />
      <br/><sub><i>The city growing from a single seed</i></sub>
    </td>
  </tr>
</table>

---

## 📊 GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Weishan-Li&show_icons=true&hide_border=true&count_private=true&title_color=2563eb&icon_color=2563eb" />
  <img height="165" src="https://streak-stats.demolab.com?user=Weishan-Li&hide_border=true&ring=2563EB&fire=2563EB&currStreakLabel=2563EB" />
</p>

## 📫 Let's Connect

I'm happy to chat about graduate roles, data projects, or anything food-and-data related.
📧 [SSLA2002@outlook.com](mailto:SSLA2002@outlook.com) · 📍 Perth, WA

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,100:1e3a8a&height=100&section=footer" width="100%" />
