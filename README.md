<h1 align="center">Hi, I'm Alman Julhijan 👋</h1>

<p align="center">
  <b>Product Manager who builds.</b><br>
  I write the spec — then I ship the thing.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/almanjulhijan/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:alman.julhijan@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/almanjulhijan"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
</p>

---

## About

I'm a **product manager** who doesn't stop at the PRD. I scope the problem, write the
spec, and then build a working product to prove it out — usually an **AI agent or bot**
wired into the tools people actually use (Lark, Strava, Discord, WhatsApp, calendars).

Most of what I ship is powered by the **Claude API** and built solo, end to end:
requirements → architecture → code → deploy. The repos below are real, working tools —
not tutorials.

- 🧭 **Product thinking first** — I obsess over the *why* and the user before writing code.
- 🤖 **AI-native builder** — LLM agents, prompt design, tool-use, and API integrations.
- 🚀 **Ship-to-learn** — I prototype fast, put it in front of real users, and iterate.

---

## 🚀 Featured Projects

### 🤖 [lark-claude-bot](https://github.com/almanjulhijan/lark-claude-bot) — *"AI-Man"*
A WebSocket Lark assistant powered by Claude that actually gets work done.

- 💬 **Knowledge-base chat** with a custom persona — sounds like you, knows your stuff, and tags answers 🟢/🟡/🔴 by confidence.
- 📄 **Reads Lark Docs, Wikis & Spreadsheets** — paste a link, get an answer (handles large sheets and Bitable tables).
- 🗓️ **Schedules meetings** from plain language — checks free/busy, respects working hours, creates the event with a meeting link.
- 🔐 **Per-user OAuth**, rate limiting, thread summaries, and a built-in 👍/👎 feedback loop.
- 🌐 Auto-matches English / Indonesian; works in DMs and group chats.

`Python` · `Claude API` · `Lark/Feishu API` · `OAuth` · `WebSocket`

### 📧→💬 [email-to-whatsapp-bot](https://github.com/almanjulhijan/email-to-whatsapp-bot)
Bridges email alerts into WhatsApp groups so the right people see them *in seconds* — built to push site safety/PPE alerts from an email-based analytics system straight to the ops team.

- 📥 **IMAP inbox polling** — works with Gmail, Outlook, Yahoo, Zoho, or any IMAP server.
- 🎯 **Flexible filtering & subject-based routing** — one bot fans out to many groups; the subject decides the destination.
- 🖼️ **Forwards image attachments** as WhatsApp photos, with clean formatting (strips signatures, adds a tidy header + timestamp).
- 🐳 **Docker-ready & self-healing** — bundles headless Chromium, one command to deploy, auto-restarts on any cheap VPS for 24/7 uptime.

`Node.js` · `whatsapp-web.js` · `IMAP` · `Docker` · `MIT licensed`

### 🏃 [fitness-coach](https://github.com/almanjulhijan/fitness-coach) — *Strava Training Coach*
A personal AI training coach that connects to Strava and reasons over your real workouts.

- 📊 Pulls your **last 30 days of Strava activities** and injects them as live context.
- 🧠 **Personal knowledge base** (goals, injuries, schedule) for genuinely tailored coaching.
- ⚡ **Prompt caching** for fast, cheap follow-up questions; `refresh` reloads data mid-session.
- 🔔 Extras: **Discord bot**, weekly training analysis, and automatic post-run enrichment.

`Python` · `Claude API` · `Strava API` · `Discord`

---

## 🧰 Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white)
![LLM Agents](https://img.shields.io/badge/LLM_Agents-5A3FD0?style=flat-square&logo=openai&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-009688?style=flat-square&logo=fastapi&logoColor=white)
![OAuth](https://img.shields.io/badge/OAuth_2.0-EB5424?style=flat-square&logo=auth0&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Product:** PRDs & specs · user research · scoping & prioritization · rapid prototyping · shipping to real users
**Build:** Python · Node.js · Claude / LLM tool-use · prompt engineering · third-party API integration (Lark, Strava, WhatsApp, Discord) · Docker & VPS deploy

---

## 🧭 How I work

> Most PMs write a doc and hand it off. I write the doc **and** build the v1.
> It keeps my specs honest, my estimates real, and my feedback loop short.

1. **Frame the problem** — who's hurting, and why it matters.
2. **Spec it** — a tight PRD with the smallest version worth shipping.
3. **Build it** — a working prototype, usually an AI agent over a real API.
4. **Ship & learn** — put it in front of users, read the feedback, iterate.

---

<p align="center"><i>Open to product roles where building alongside the team is a feature, not a bug.</i></p>
