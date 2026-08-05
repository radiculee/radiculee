# Vedant Gaikwad

**Data Analyst | BI and Reporting | Dublin, Ireland**

I build data products, not just dashboards. My work sits between analytics engineering and production software: SQL and Python pipelines, Power BI and Streamlit reporting layers, and Next.js apps deployed and running in production.

MSc Computing (Data Analytics), Dublin City University. Currently a Data Analyst with commercial experience across reporting automation, data modelling, and internal tooling.

- Portfolio: [vedantgaikwad.ie](https://vedantgaikwad.ie)
- LinkedIn: [in/vedant-gaikwad-873368226](https://www.linkedin.com/in/vedant-gaikwad-873368226/)
- Kaggle: [kaggle.com/radiculee](https://www.kaggle.com/radiculee)
- Email: vedantgaikwad01@gmail.com

Full Irish work rights (Stamp 1G), no sponsorship required.

---

## What I work with

| Area | Tools |
|---|---|
| Languages | Python, SQL, TypeScript, DAX, M (Power Query) |
| BI and reporting | Power BI (Desktop and Service), Streamlit, Plotly |
| Data engineering | Pandas, DuckDB, REST and OAuth2 API integration, GitHub Actions |
| Web | Next.js, React, Tailwind CSS, Vercel |
| Other | Git, Docker, Mapbox, Folium, LLM APIs (Claude, OpenAI) |

---

## Selected projects

### Off Ye Go
**Live: [offyego.ie](https://offyego.ie) | Repo: [radiculee/offyego](https://github.com/radiculee/offyego)**

A pub randomiser for Ireland. Pick a radius, spin, get a pub. Built with Next.js 16, React 19, TypeScript and Tailwind v4, pulling live venue data from the Overpass (OpenStreetMap) API and rendering it on Mapbox.

Engineering notes: geographic filtering against an Ireland boundary polygon, graceful degradation when the upstream Overpass API is rate limited, dynamic Open Graph image generation, and a Lighthouse profile of 99 / 98 / 100 / 100. Deployed on Vercel with a custom domain.

### Strava Cycling Dashboard
**Live: [strava-cycling-dashboard.streamlit.app](https://strava-cycling-dashboard.streamlit.app)**

An automated ETL pipeline and analytics dashboard for my own training data. A nightly GitHub Actions workflow authenticates against the Strava API using OAuth2 with refresh token rotation, extracts activity data, transforms it in Python, and serves it through a mobile-first Streamlit app.

Engineering notes: pinned to Python 3.11 due to a pydantic 1.x dependency in stravalib, scheduled workflow orchestration, secret management through GitHub Actions, and a GitHub-style contribution heatmap plus twelve-week rolling volume analysis. Source repository is private on request as it contains personal training data.

### Bohemian Bar
**Live: [bohemianpub.ie](https://bohemianpub.ie)**

A production website for a Dublin pub, built and shipped end to end. Next.js 15, TypeScript, Tailwind v4, Framer Motion, with four transactional booking forms routed through Resend to the venue inbox. Deployed on Vercel and in daily commercial use.

### MicroSplit (MSc Dissertation)
**AI-driven decomposition of monolithic applications into microservices**

Combined static code analysis (Joern code property graphs), graph neural networks (GraphSAGE structural embeddings), and a locally hosted Mistral LLM for semantic reasoning to identify microservice boundaries in Java monoliths.

Evaluated against three benchmark systems: TrainTicket (F1 = 0.52), Apollo (F1 = 0.48, NMI = 0.62), and PetClinic (F1 = 0.38, NMI = 0.46).

### Automated Job Application Agent
An LLM agent pipeline that classifies inbound email, drafts contextual responses, and writes structured records to a Notion database. Uses a tiered model strategy (a fast model for classification, a stronger model for drafting) to control cost, with human-in-the-loop approval gating any outbound message. Hosted on a Hetzner VPS.

---

## Earlier work

Machine learning and NLP projects from my undergraduate degree, kept public for reference rather than as a reflection of current practice:

- [Sentiment Analysis on Amazon Food Reviews](https://github.com/radiculee/Sentiment-analysis-on-Amazon-Food-reviews)
- [Ham and Spam Detection](https://github.com/radiculee/Ham-and-Spam-Detection-Python)
- [Price Optimization Model](https://github.com/radiculee/Price-Optimization-model)
- [Chatbot using Deep Learning and NLP](https://github.com/radiculee/Chatbot-using-Deep-learning-and-NLP-)

---

## Background

**Data Analyst**, Converge Engineering, Dublin. Reporting automation, data modelling, and analytics delivery for engineering operations.

**Esports Operations Lead**, Lethal Esports. Contract negotiation, player retention analytics, and international tournament operations.

**MSc Computing (Data Analytics)**, Dublin City University.
**BEng Computer Engineering**, Rajiv Gandhi Institute of Technology, Mumbai.

Outside work: cycling, football, and training toward Ironman Youghal 2027.

---

Open to Data Analyst, BI Analyst, and Analytics Engineer roles in Dublin.
