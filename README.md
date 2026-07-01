<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Akil%20Nasim&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI%20Engineer%20%7C%20Building%20Production%20LLM%20%26%20Voice%20AI%20Systems&descAlignY=55&descSize=18" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=650&lines=AI+Engineer+%7C+Voice+AI+%26+LLM+Systems;Generative+AI+%C2%B7+Conversational+AI+%C2%B7+Full+Stack;B.Tech+in+Artificial+Intelligence" alt="Typing SVG" />
</a>

<br/>

![Academic](https://img.shields.io/badge/B.Tech-Artificial%20Intelligence-6D28D9?style=flat-square&logo=googlescholar&logoColor=white)
![Location](https://img.shields.io/badge/Location-Bengaluru,%20India-6D28D9?style=flat-square&logo=googlemaps&logoColor=white)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white)](https://akilnasim.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akil-nasim-38ab671b1)
[![Email](https://img.shields.io/badge/Email-4C1D95?style=for-the-badge&logo=gmail&logoColor=white)](mailto:akilnasim17@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-1E1B4B-8B5CF6?style=for-the-badge&logo=github&logoColor=white)](https://github.com/akilnasim17)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=akilnasim17&color=8b5cf6&style=flat-square&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/akilnasim17?color=6D28D9&style=flat-square&label=Followers)
![Stars](https://img.shields.io/github/stars/akilnasim17?color=A78BFA&style=flat-square&label=Stars)

</div>

<br/>

## 🪞 About Me

I'm an **AI Engineer** who builds production systems at the intersection of **Generative AI, Voice AI, and full-stack engineering** — from LLM-powered voice agents that handle real conversations to computer vision models solving healthcare problems.

- 🧠 Strong foundation in **software engineering** paired with applied **AI/ML expertise**
- 🛠️ Comfortable across the **full stack** — from Django/Channels backends to production frontends
- 🎯 Product engineering mindset — I care about what ships and works, not just what's technically interesting
- 🎓 B.Tech in Artificial Intelligence, Christ University (Bangalore)

```yaml
Open To: AI Engineer · Machine Learning Engineer · Forward Deployed Engineer roles
```

<br/>

## 🧰 Tech Stack

**Languages**

<img src="https://skillicons.dev/icons?i=python,js,html,css&theme=dark" />

**Frontend**

<img src="https://skillicons.dev/icons?i=html,css,js,react,vite&theme=dark" />

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=django,fastapi,nodejs,sqlite,supabase,postgres&theme=dark" />

**Cloud, DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=git,github,vscode,postman,docker&theme=dark" />

<br/>

## 🤖 AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|---|---|---|
| **Generative AI (GANs)** | Advanced | Built a GAN-based super-resolution model using knowledge distillation from ESRGAN for medical image enhancement |
| **Conversational & Voice AI** | Advanced | Built a production voice agent (Django + Channels + Groq/OpenAI + edge-tts) exposing tools via MCP for real-time booking workflows |
| **Machine Learning** | Intermediate–Advanced | Supervised & unsupervised learning, model evaluation, data preprocessing on real-world datasets |
| **LLM Orchestration** | Intermediate | LLM-driven conversational logic and tool-calling via the Model Context Protocol (MCP) |

</div>

<br/>

## 🚀 Featured Projects

<details>
<summary><b>🏥 Schelles Hospital Voice Receptionist</b></summary>
<br/>

AI-powered voice receptionist that automates patient inquiries, appointment booking, cancellation, and rescheduling for a healthcare provider — built as a real-time conversational backend with LLM tool-calling exposed via MCP.

| | |
|---|---|
| **Stack** | Python, Django, Django Channels, Daphne (ASGI), Groq API, OpenAI API, edge-tts, MCP (Model Context Protocol) |
| **Scale** | Real-time voice sessions with concurrent WebSocket connections via Channels/Daphne |
| **Performance** | Real-time speech-to-response pipeline with tool-calling for live appointment data |
| **Security** | Environment-based secret management, CORS-restricted API access |
| **Impact** | Automates patient booking/rescheduling workflows, reducing manual front-desk workload |
| **Repository** | [github.com/akilnasim17/schelles-voice-receptionist](https://github.com/akilnasim17/schelles-voice-receptionist) |

Designed the system end-to-end: session management, rate limiting, a Groq-backed conversational engine, and an MCP server exposing clinic tools (`list_doctors`, `check_availability`, `book_appointment`, `cancel_appointment`, `lookup_appointment`) so the LLM can take real actions instead of just generating text.

</details>

<details>
<summary><b>🖼️ AI-Powered Medical Image Super-Resolution (Distilled GAN)</b></summary>
<br/>

A GAN-based model that enhances low-resolution medical images using knowledge distillation from ESRGAN into a lightweight network.

| | |
|---|---|
| **Stack** | Python, GANs, ESRGAN, Knowledge Distillation |
| **Scale** | Medical imaging dataset, single-model training pipeline |
| **Performance** | Improved image quality with reduced inference compute vs. the full ESRGAN teacher network |
| **Security** | N/A — research/academic project |
| **Impact** | Enhances diagnostic image quality for practical, compute-constrained healthcare applications |
| **Repository** | *Private — in progress* |

Distilled a large ESRGAN teacher model into a smaller student network, trading a small amount of quality for a meaningful drop in compute cost — aimed at making super-resolution viable in lower-resource clinical settings.

</details>

<details>
<summary><b>🏢 Schelles — AI Venture, Cloud Software & IT Solutions</b></summary>
<br/>

Schelles is an AI-first venture delivering cutting-edge AI solutions, cloud-based software, and enterprise IT services — including the hospital voice receptionist system above.

| | |
|---|---|
| **Stack** | HTML, CSS, JavaScript |
| **Scale** | Public-facing venture site |
| **Performance** | Static, fully client-rendered site |
| **Security** | Standard static-site hosting |
| **Impact** | Public front door for the Schelles venture and its AI/cloud/IT offerings |
| **Repository** | [github.com/akilnasim17/schelles-website](https://github.com/akilnasim17/schelles-website) |
| **Live Site** | [schelles.in](https://schelles.in/) |

</details>

<details>
<summary><b>📈 AI Sales & Inventory Prediction Platform</b></summary>
<br/>

A FastAPI + React platform for demand forecasting, inventory prediction, sales-route analysis, and salesman performance scoring — built for enterprise sales operations.

| | |
|---|---|
| **Stack** | Python, FastAPI, SQL, JWT Auth, React, Vite |
| **Scale** | Multi-tenant backend covering forecasting, inventory, purchase orders, and route analytics |
| **Performance** | Dedicated ML modules for sales forecasting, inventory prediction, and root-cause analysis |
| **Security** | JWT-based authentication, tenant-scoped data access |
| **Impact** | Gives sales teams forward-looking demand, inventory, and route recommendations instead of reactive reporting |
| **Repository** | [github.com/akilnasim17/ai-sales-prediction](https://github.com/akilnasim17/ai-sales-prediction) |

</details>

<details>
<summary><b>💬 Social Media Automations (WhatsApp / Instagram)</b></summary>
<br/>

An AI-driven automation platform for handling WhatsApp and Instagram conversations, lead capture, and analytics for businesses.

| | |
|---|---|
| **Stack** | Python (FastAPI), React, Docker, WhatsApp & Instagram APIs |
| **Scale** | Webhook-driven conversation handling with lead and analytics tracking |
| **Performance** | Containerized backend/frontend via Docker Compose |
| **Security** | Environment-based credential management for third-party API integrations |
| **Impact** | Automates conversational lead capture across two major messaging channels |
| **Repository** | [github.com/akilnasim17/social-media-automations](https://github.com/akilnasim17/social-media-automations) |

</details>

<details>
<summary><b>🎫 NudgeDesk — AI-Powered Helpdesk</b></summary>
<br/>

A helpdesk platform that uses an LLM to categorize incoming tickets, draft replies, and surface similar past tickets via semantic search.

| | |
|---|---|
| **Stack** | Python, FastAPI, SQLModel, Groq (LLM), model2vec (embeddings) |
| **Scale** | Ticket queue with agent workflows, knowledge base, and analytics |
| **Performance** | Provider-agnostic LLM layer — swappable between Groq/other providers via config |
| **Security** | Session-based auth via `itsdangerous`, environment-based secrets |
| **Impact** | Cuts manual ticket triage by auto-categorizing tickets and drafting first-pass replies |
| **Repository** | [github.com/akilnasim17/nudgedesk](https://github.com/akilnasim17/nudgedesk) |

</details>

<br/>

## 💼 Experience

**AI Engineer** · NATMCO Solutions LLP
`Apr 2026 – Present`

Building an AI-powered Voice Receptionist for healthcare operations — integrating speech-to-text, text-to-speech, and LLMs to automate patient inquiries, appointment booking, and rescheduling, while reducing call center workload and improving operational efficiency. Owns the project lifecycle from concept through near-production deployment, working directly with clinical stakeholders.

`Python` `Django` `LLMs` `Speech-to-Text` `Text-to-Speech` `Conversational AI`

<br/>

**Software Development Intern** · NATMCO Solutions LLP
`Mar 2025 – May 2025`

Built a full-stack logistics management website for administrators — an admin portal, real-time shipment tracking, analytics dashboards, and user management — using HTML, CSS, and JavaScript on the front end with SQL and Supabase on the back end.

`HTML` `CSS` `JavaScript` `SQL` `Supabase`

<br/>

**Machine Learning Intern** · IIROHUB Infotech Pvt. Ltd.
`Apr 2024 – May 2024`

Applied supervised and unsupervised learning techniques to real-world datasets — covering data preprocessing, model development, and evaluation with Python and standard ML libraries.

`Python` `Machine Learning` `Data Preprocessing`

<br/>

## 🏆 Achievements

<div align="center">

| Recognition | Details |
|---|---|
| 🥇 National Football Championship | Kristu Jayanthi University |
| 🥇 National Football Championship | Azim Premji University |
| 🥇 National Football Championship | Christ University |
| 🥇 National Football Championship | Mount Carmel College |

</div>

<br/>

## 📜 Certifications

**CIMA**
![Management Accounting](https://img.shields.io/badge/Management%20Accounting-6D28D9?style=flat-square&logo=CIMA&logoColor=white)

**NPTEL**
![Data Science for Engineers](https://img.shields.io/badge/Data%20Science%20for%20Engineers-6D28D9?style=flat-square&logo=googlescholar&logoColor=white)

**IIT Tirupati Navavishkar I-Hub Foundation**
![Computer Vision Workshop](https://img.shields.io/badge/Computer%20Vision%20Workshop%20(MATLAB)-6D28D9?style=flat-square&logo=mathworks&logoColor=white)

<br/>

## 📊 GitHub Analytics

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=akilnasim17&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=8B5CF6&text_color=c9d1d9" width="48%"/>
<img src="https://streak-stats.demolab.com?user=akilnasim17&theme=tokyonight&hide_border=true&background=0D1117&ring=8B5CF6&fire=A78BFA&currStreakLabel=A78BFA" width="48%"/>
</div>

<div align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=akilnasim17&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=c9d1d9" width="48%"/>
</div>

<br/>

## 🏅 GitHub Trophies

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=akilnasim17&theme=algolia&no-frame=true&no-bg=true&margin-w=8&column=7" />
</div>

<br/>

## 📈 Contribution Activity

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=akilnasim17&theme=react-dark&hide_border=true&bg_color=0D1117&color=A78BFA&line=8B5CF6&point=ffffff" width="100%"/>
</div>

<br/>

## 🐍 Contribution Snake

<div align="center">
<img src="https://raw.githubusercontent.com/akilnasim17/akilnasim17/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</div>

<br/>

## 🎯 Current Focus

```yaml
Learning:   Retrieval-Augmented Generation, LLM tool-calling patterns (MCP)
Building:   Schelles — AI voice agents & cloud software for healthcare
Exploring:  Forward Deployed Engineering, applied Generative AI in production
Open To:    AI Engineer / Forward Deployed Engineer opportunities
```

<br/>

## 📫 Connect

[![Gmail](https://img.shields.io/badge/Gmail-4C1D95?style=for-the-badge&logo=gmail&logoColor=white)](mailto:akilnasim17@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akil-nasim-38ab671b1)
[![GitHub](https://img.shields.io/badge/GitHub-1E1B4B-8B5CF6?style=for-the-badge&logo=github&logoColor=white)](https://github.com/akilnasim17)
[![Portfolio](https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white)](https://akilnasim.netlify.app/)

<br/>

<div align="center">

*"Build the thing that works in production, not just the demo."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=20,11,6&height=120&section=footer" width="100%"/>

</div>
