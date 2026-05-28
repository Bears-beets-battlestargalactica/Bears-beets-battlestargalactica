<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:020617,35:1e1b4b,70:2563eb,100:06b6d4&text=Jibin%20Varghese&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=Security%20Engineering%20%E2%80%A2%20Applied%20AI%20%E2%80%A2%20Real-World%20Systems&descSize=18&descAlignY=60&animation=fadeIn" alt="Jibin Varghese banner" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jibin-varghese-a48b402a6/"><img src="https://img.shields.io/badge/LinkedIn-Jibin%20Varghese-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:jibinye@oregonstate.edu"><img src="https://img.shields.io/badge/Email-jibinye%40oregonstate.edu-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/Bears-beets-battlestargalactica"><img src="https://img.shields.io/badge/GitHub-Bears,%20Beets,%20Battlestar-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

---

## `whoami`

I build software where **security engineering**, **applied AI**, and **messy real-world systems** meet.

Not just clean demos. Not just benchmark numbers. I like the awkward middle ground: noisy logs, incomplete metadata, uneven labels, weird edge cases, and projects that need to work outside ideal conditions.

> The username is an Office reference. The work is mostly security, AI, and systems.

---

## Current Focus

| Security Analytics | Applied AI / ML | Systems + Engineering |
|---|---|---|
| SOC telemetry | ML for security | React / Node.js |
| SIEM + EDR workflows | NLP + computer vision | APIs + dashboards |
| Provenance graphs | Model evaluation | Full-stack tools |
| Intrusion detection | Research-to-practice gaps | Usable developer tooling |

---

## What I Like Working On

- Turning messy data into useful systems
- Making research easier to inspect and explain
- Building tools that move past prototype stage
- Testing models against real operational noise
- Finding the gap between “works in paper” and “works in practice”

---

## Selected Work

### 01. ORTSOC Provenance-Based Intrusion Detection Research

**Research dataset construction from operational SOC telemetry**

This is my main research work: deriving a machine-learning-ready intrusion detection dataset from real operational SOC telemetry and using it to evaluate provenance-based intrusion detection systems under realistic conditions.

Instead of starting with a clean benchmark dataset, this project asks:

> What happens when provenance-based IDS models leave curated datasets and meet noisy operational SOC telemetry?

| Area | Details |
|---|---|
| **Input** | Elastic EDR / Elastic Common Schema telemetry |
| **Mapping** | ECS events → CDM-like provenance graphs |
| **Challenges** | PID reuse, timestamp normalization, incomplete metadata, causal edge inference |
| **Models** | MAGIC, Orthrus, ThreaTrace |
| **Focus** | Temporal windows, class imbalance, operational robustness |

**Key idea:** benchmark performance is not deployment readiness. Models that look strong on DARPA Transparent Computing-style datasets can behave very differently on SOC-derived telemetry.

[![Read Paper](https://img.shields.io/badge/Read%20Paper-Operational%20SOC%20Telemetry-2563EB?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1qZX6T1KBS7JwzPhaQtCYFQgDf-DTtSDm/view?usp=drive_link)

![Provenance Graphs](https://img.shields.io/badge/Provenance%20Graphs-111827?style=flat-square)
![SOC Telemetry](https://img.shields.io/badge/SOC%20Telemetry-111827?style=flat-square)
![Elastic EDR](https://img.shields.io/badge/Elastic%20EDR-111827?style=flat-square)
![ECS to CDM](https://img.shields.io/badge/ECS%20to%20CDM-111827?style=flat-square)
![Intrusion Detection](https://img.shields.io/badge/Intrusion%20Detection-111827?style=flat-square)

---

### 02. AI Code Review Assistant

**A full-stack AI tool for reviewing code**

A developer tool that analyzes code and provides review-style feedback. I built this to explore how AI can support engineering workflows beyond autocomplete, especially around readability, maintainability, and review quality.

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

[![Live Demo](https://img.shields.io/badge/Live%20Demo-AI%20Code%20Reviewer-7C3AED?style=for-the-badge)](https://ai-code-review-assistant-gold.vercel.app)
[![GitHub Repository](https://img.shields.io/badge/GitHub%20Repository-ai--code--review--assistant-111827?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Bears-beets-battlestargalactica/ai-code-review-assistant)

---

### 03. Automatic Pith Detection Using Deep Learning

**Computer vision for scientific image analysis**

A deep learning research project focused on detecting pith in tree cross-section images. This project explores how modern vision architectures perform on a specialized biological imaging task.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-111827?style=flat-square)
![Swin Transformer](https://img.shields.io/badge/Swin%20Transformer-111827?style=flat-square)

[![GitHub Repository](https://img.shields.io/badge/GitHub%20Repository-Automatic%20Pith%20Detection-111827?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Bears-beets-battlestargalactica/Automatic_Pith_Detection)
[![arXiv Paper](https://img.shields.io/badge/arXiv%20Paper-2512.00625-B31B1B?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2512.00625)
[![Paper PDF](https://img.shields.io/badge/Paper%20PDF-Read-DC2626?style=for-the-badge)](https://arxiv.org/pdf/2512.00625)

---

### 04. Depression Detection Using Tweets

**NLP project using social media text**

An early machine learning project that analyzes tweets from a single user to detect signs of depression. This helped me explore NLP, sentiment patterns, feature extraction, and ML-based classification.

![NLP](https://img.shields.io/badge/NLP-111827?style=flat-square)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-111827?style=flat-square)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

[![GitHub Repository](https://img.shields.io/badge/GitHub%20Repository-Depression%20Detection%20Using%20Tweets-111827?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Bears-beets-battlestargalactica/Webappfordepressiondetectionontweets-main)

---

### 05. Twitter-Like Social Media App

**MERN-stack social media application**

A full-stack social media app with posting, authentication, user interactions, and timeline-style features. This helped me go deeper into frontend state, backend APIs, and database-backed user experiences.

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

[![GitHub Repository](https://img.shields.io/badge/GitHub%20Repository-Twitter--Like%20Social%20Media%20App-111827?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Bears-beets-battlestargalactica/Twitter_new)

---

## Technical Toolkit

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,c,js,ts,react,nodejs,express,mongodb,postgres,docker,kubernetes,aws,azure,linux,git,github,html,css,tailwind,pytorch,tensorflow,opencv,vscode" alt="Technical skills" />
</p>

| Security | AI / ML | Engineering | Data |
|---|---|---|---|
| Microsoft Defender XDR | PyTorch | React | PostgreSQL |
| Azure Sentinel | TensorFlow | Node.js | MongoDB |
| Zeek | scikit-learn | Express | Elasticsearch |
| Elastic / Kibana | NLP | REST APIs | Pandas |
| SIEM workflows | Computer Vision | Docker | JSONL pipelines |

---

## Operating Principles

> Build things that survive contact with real systems.

Useful over flashy · Explain the messy parts · Benchmarks are a starting point · Ship, test, learn, repeat

---

## Connect

<p align="center">
  <a href="https://www.linkedin.com/in/jibin-varghese-a48b402a6/"><img src="https://img.shields.io/badge/LinkedIn-Jibin%20Varghese-2563EB?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:jibinye@oregonstate.edu"><img src="https://img.shields.io/badge/Email-jibinye%40oregonstate.edu-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/Bears-beets-battlestargalactica"><img src="https://img.shields.io/badge/GitHub-Bears,%20Beets,%20Battlestar-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>
