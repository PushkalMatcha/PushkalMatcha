<div align="center">

# PUSHKAL MATCHA

### AI Engineer · Software Engineer · Cloud

**Building intelligent systems that go from idea → model → API → production.**

<br>

<a href="https://github.com/PushkalMatcha">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>
<a href="mailto:matchapushkal@gmail.com">
<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
</a>

<br><br>

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=20&pause=1200&color=58A6FF&center=true&vCenter=true&width=700&lines=AI+Engineer;LLM+%26+Agentic+Systems;Full-Stack+Software+Engineer;Computer+Vision+%26+Deep+Learning;Cloud+%26+Backend+Engineering" alt="Typing introduction">

</div>

---

# `01 — ENGINEERING PROFILE`

```text
┌──────────────────────────────────────────────────────────┐
│                      PUSHKAL MATCHA                      │
├──────────────────────────────────────────────────────────┤
│ AI Engineer                                              │
│                                                          │
│ AI / ML       → LLMs · Agents · Computer Vision          │
│ Software      → APIs · Backend · Full Stack              │
│ Infrastructure→ AWS · Docker · Linux · CI/CD             │
│ Research      → Deep Learning · Vision Transformers      │
└──────────────────────────────────────────────────────────┘

```

I'm a Computer Science undergraduate at **SRM Institute of Science and Technology, Tiruchirappalli**, focused on building **AI-powered software systems** rather than isolated ML experiments.

My interests sit at the intersection of:

**Artificial Intelligence × Software Engineering × Cloud Infrastructure**

I enjoy taking an idea through the entire engineering lifecycle — designing the architecture, building the model or AI workflow, exposing it through APIs, creating the product layer, and deploying it.

Previously, I worked as a **Software Developer Intern at Vadoo AI**, working on **Muapi**, an image-generation API platform.

---

# `02 — WHAT I WORK ON`

### 🤖 AI ENGINEERING

LLM applications
AI agents
RAG & AI workflows
Computer Vision
Deep Learning

### ⚙️ SOFTWARE

Backend APIs
Full-stack systems
Async processing
Databases
Real-time systems

### ☁️ INFRASTRUCTURE

AWS
Docker
Linux
Nginx
CI/CD

---

# `03 — FEATURED ENGINEERING`

## 🏦 Agentic Trade Settlement Engine

### `Autonomous post-trade intelligence & triage platform`

A hybrid AI platform combining deterministic predictive machine learning with an autonomous LLM agent to triage post-trade settlement failures and execute remediation workflows.

```text
                  ┌───────────────────┐
                  │ Trade Exception   │
                  └─────────┬─────────┘
                            ↓
                  ┌───────────────────┐
                  │ LangGraph ReAct   │
                  │ AI Agent Loop     │
                  └────┬─────────┬────┘
                       ↓         ↓
            ┌──────────┴─┐     ┌─┴──────────┐
            │ Scikit-Learn │     │ ChromaDB   │
            │ ML Predict   │     │ Vector RAG │
            └──────────┬─┘     └─┬──────────┘
                       ↓         ↓
                  ┌────┴─────────┴────┐
                  │ API Remediation   │
                  │ Report (FastAPI)  │
                  └───────────────────┘

```

**Engineering focus**

`Python` `LangGraph` `Scikit-Learn` `ChromaDB` `FastAPI` `Agentic AI` `RAG`

---

## 🧪 AI Tester Agent

### `Autonomous AI-powered QA system`

An autonomous QA pipeline that uses LLMs to transform requirements into executable browser tests, analyze failures and generate actionable testing insights.

```text
                    ┌─────────────┐
                    │ Jira Story  │
                    └──────┬──────┘
                           ↓
                  ┌─────────────────┐
                  │ LLM Test Design │
                  └────────┬────────┘
                           ↓
                  ┌─────────────────┐
                  │ Playwright      │
                  │ Browser Agent   │
                  └────────┬────────┘
                           ↓
                  ┌─────────────────┐
                  │ Failure Analysis│
                  └────────┬────────┘
                           ↓
             ┌──────────────────────────┐
             │ Risk + Regression Plan   │
             └──────────────────────────┘

```

**Engineering focus**

`LLMs` `AI Agents` `Playwright` `FastAPI` `React` `TypeScript` `Supabase` `PostgreSQL`

---

## 🧹 Data-Saab

### `Event-driven data processing platform`

A high-throughput CSV validation and preprocessing platform designed around asynchronous workers and real-time processing telemetry.

```text
              CSV Upload
                  │
                  ↓
          ┌───────────────┐
          │ API / Gateway │
          └───────┬───────┘
                  ↓
              Redis Queue
                  │
                  ↓
              BullMQ Jobs
                  │
          ┌───────┴───────┐
          ↓               ↓
      Validation      Processing
          │               │
          └───────┬───────┘
                  ↓
            WebSocket Events
                  ↓
          Real-time Dashboard

```

**Engineering focus**

`Node.js` `TypeScript` `Next.js` `Redis` `BullMQ` `WebSockets` `Streaming`

---

## 🧠 Maeven CRM

### `AI-native customer intelligence platform`

A conversational CRM architecture where natural-language instructions can drive customer segmentation, campaign creation and asynchronous execution.

```text
                User
                 │
                 ↓
        Natural Language
                 │
                 ↓
       ┌──────────────────┐
       │ AI Campaign      │
       │ Composer         │
       └────────┬─────────┘
                ↓
       ┌──────────────────┐
       │ Customer         │
       │ Segmentation     │
       └────────┬─────────┘
                ↓
       ┌──────────────────┐
       │ Async Campaign   │
       │ Execution        │
       └────────┬─────────┘
                ↓
          Analytics

```

**Engineering focus**

`Next.js` `FastAPI` `PostgreSQL` `Supabase` `LLM APIs` `Async Workflows`

---

# `04 — AI / RESEARCH`

## 🔬 CNN vs Vision Transformer

### `Medical image classification study`

Comparative evaluation of **ResNet50** and **ViT-B/16** for lung and colon cancer histopathology classification.

| Model | Test Accuracy | Macro F1 |
| --- | --- | --- |
| ResNet50 | 97.07% | 0.9699 |
| ResNet50 + Macenko | 96.53% | 0.9645 |
| **ViT-B/16** | **97.36%** | **0.9729** |
| **ViT-B/16 + Macenko** | **97.36%** | **0.9729** |

**Stack**

`Python` `PyTorch` `ResNet50` `Vision Transformer` `Computer Vision`

---

## 👶 Smart Baby Monitoring

### `Computer Vision + Audio Intelligence`

An IoT-oriented monitoring system combining infant-cry classification with computer-vision-based object detection.

**Focus**

`Computer Vision` `Deep Learning` `MobileNet` `Audio Classification` `IoT`

---

# `05 — OTHER SYSTEMS`

### 🏥 Health Record System

A cloud-deployed healthcare management platform with API-driven architecture, PostgreSQL persistence and production infrastructure.

**AWS EC2 · RDS · Nginx · PM2 · GitHub Actions · PostgreSQL**

---

### 📊 TeamPulse

Engineering productivity platform combining GitHub activity, sprint tracking, real-time updates and AI-generated insights.

**React · Node.js · Express · MongoDB · Socket.IO · Groq**

---

# `06 — AI ENGINEERING STACK`

### Languages

### AI / ML

### Full Stack

### Cloud / Infrastructure

### Data & Infrastructure

---

# `07 — EXPERIENCE`

## Vadoo AI

**Software Developer Intern · June 2025 — July 2025**

Worked on **Muapi**, an image-generation API platform.

* Built a mobile-friendly web interface
* Integrated image-generation APIs
* Worked across frontend and API integration layers
* Built product experiences around generative AI workflows

---

# `08 — LEADERSHIP`

### Robothinkers Robotics Club

**Secretary**

Contributing to technical initiatives, student projects and robotics-focused activities.

---

# `09 — CERTIFICATION`

---

# `10 — CURRENTLY BUILDING`

```text
┌──────────────────────────────────────────┐
│              CURRENT FOCUS               │
├──────────────────────────────────────────┤
│ → AI Agents & LLM Applications           │
│ → AI-powered Developer Tools             │
│ → Backend & Distributed Systems          │
│ → Cloud Architecture                     │
│ → Computer Vision                        │
│ → Data Structures & Algorithms           │
│ → Open Source                            │
└──────────────────────────────────────────┘

```

---

# `11 — GITHUB ACTIVITY`

---

# `12 — LET'S CONNECT`





### `Build → Learn → Ship → Repeat`
