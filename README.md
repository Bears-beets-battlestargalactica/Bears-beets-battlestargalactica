<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:020617,35:1e1b4b,70:2563eb,100:06b6d4&text=Jibin%20Varghese&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=Security%20Engineering%20%E2%80%A2%20Applied%20AI%20%E2%80%A2%20Real-World%20Systems&descSize=18&descAlignY=60&animation=fadeIn" alt="Jibin Varghese banner" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jibin-varghese-a48b402a6/">
    <img src="https://img.shields.io/badge/LinkedIn-Jibin%20Varghese-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:jibinye@oregonstate.edu">
    <img src="https://img.shields.io/badge/Email-jibinye%40oregonstate.edu-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/Bears-beets-battlestargalactica">
    <img src="https://img.shields.io/badge/GitHub-Bears,%20Beets,%20Battlestar-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

<br>

<div align="center">

### I build software where security, AI, and messy real-world systems collide.

Not just clean demos. Not just benchmark numbers.  
I like the awkward middle ground: noisy logs, incomplete metadata, weird edge cases, and projects that need to work outside ideal conditions.

</div>

<br>

<table>
  <tr>
    <td width="50%" valign="top">

### Current lane

- Security analytics and SOC telemetry
- Applied AI/ML for security and research
- Full-stack tools that are actually usable
- Provenance graphs and intrusion detection
- Developer tooling, dashboards, and APIs

    </td>
    <td width="50%" valign="top">

### I like working on

- Turning messy data into useful systems
- Making research easier to inspect and explain
- Building tools that move past prototype stage
- Testing models against real operational noise
- Finding the gap between “works in paper” and “works in practice”

    </td>
  </tr>
</table>

<br>

<h2 align="center">Selected Work</h2>

---

## 01. ORTSOC Provenance-Based Intrusion Detection Research

<table>
  <tr>
    <td valign="top">

**Research dataset construction from operational SOC telemetry**

This is my main research work: deriving a machine-learning-ready intrusion detection dataset from real operational SOC telemetry and using it to evaluate provenance-based intrusion detection systems under realistic conditions.

Instead of starting with a clean benchmark dataset, this project asks:

> What happens when provenance-based IDS models leave curated datasets and meet noisy operational SOC telemetry?

| Area | Details |
|---|---|
| Input | Elastic EDR / Elastic Common Schema telemetry |
| Mapping | ECS events → CDM-like provenance graphs |
| Challenges | PID reuse, timestamp normalization, incomplete metadata, causal edge inference |
| Models | MAGIC, Orthrus, ThreaTrace |
| Focus | Temporal windows, class imbalance, operational robustness |

**Key idea:** benchmark performance is not deployment readiness. Models that look strong on DARPA Transparent Computing-style datasets can behave very differently on SOC-derived telemetry.

<p>
  <a href="https://drive.google.com/file/d/1qZX6T1KBS7JwzPhaQtCYFQgDf-DTtSDm/view?usp=drive_link">
    <img src="https://img.shields.io/badge/Read%20Paper-Operational%20SOC%20Telemetry-2563EB?style=for-the-badge&logo=googledrive&logoColor=white" alt="Read Paper" />
  </a>
</p>

<p>
  <img src="https://img.shields.io/badge/Provenance%20Graphs-111827?style=flat-square" alt="Provenance Graphs" />
  <img src="https://img.shields.io/badge/SOC%20Telemetry-111827?style=flat-square" alt="SOC Telemetry" />
  <img src="https://img.shields.io/badge/Elastic%20EDR-111827?style=flat-square" alt="Elastic EDR" />
  <img src="https://img.shields.io/badge/ECS%20to%20CDM-111827?style=flat-square" alt="ECS to CDM" />
  <img src="https://img.shields.io/badge/Intrusion%20Detection-111827?style=flat-square" alt="Intrusion Detection" />
</p>

  </td>
  </tr>
</table>

---

## 02. AI Code Review Assistant

<table>
  <tr>
    <td width="65%" valign="top">

**A full-stack AI tool for reviewing code**

A developer tool that analyzes code and provides review-style feedback. I built this to explore how AI can support engineering workflows beyond autocomplete, especially around readability, maintainability, and review quality.

    </td>
    <td width="35%" valign="top">

**Stack**

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" />
  <img src="https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black" alt="Render" />
</p>

    </td>
  </tr>
</table>

<p>
  <a href="https://ai-code-review-assistant-gold.vercel.app">
    <img src="https://img.shields.io/badge/Live%20Demo-View%20Project-7C3AED?style=for-the-badge" alt="Live Demo" />
  </a>
  <a href="https://github.com/Bears-beets-battlestargalactica/ai-code-review-assistant">
    <img src="https://img.shields.io/badge/Repository-GitHub-111827?style=for-the-badge&logo=github&logoColor=white" alt="Repository" />
  </a>
</p>

---

## 03. Automatic Pith Detection Using Deep Learning

<table>
  <tr>
    <td width="65%" valign="top">

**Computer vision for scientific image analysis**

A deep learning research project focused on detecting pith in tree cross-section images. This project explores how modern vision architectures perform on a specialized biological imaging task.

    </td>
    <td width="35%" valign="top">

**Stack**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/YOLO-111827?style=flat-square" alt="YOLO" />
  <img src="https://img.shields.io/badge/Swin%20Transformer-111827?style=flat-square" alt="Swin Transformer" />
</p>

    </td>
  </tr>
</table>

<p>
  <a href="https://github.com/Bears-beets-battlestargalactica/Automatic_Pith_Detection">
    <img src="https://img.shields.io/badge/Repository-GitHub-111827?style=for-the-badge&logo=github&logoColor=white" alt="Repository" />
  </a>
  <a href="https://arxiv.org/abs/2512.00625">
    <img src="https://img.shields.io/badge/Paper-arXiv-B31B1B?style=for-the-badge&logo=arxiv&logoColor=white" alt="arXiv" />
  </a>
  <a href="https://arxiv.org/pdf/2512.00625">
    <img src="https://img.shields.io/badge/PDF-Read-DC2626?style=for-the-badge" alt="PDF" />
  </a>
</p>

---

## 04. Depression Detection Using Tweets

<table>
  <tr>
    <td width="65%" valign="top">

**NLP project using social media text**

An early machine learning project that analyzes tweets from a single user to detect signs of depression. This helped me explore NLP, sentiment patterns, feature extraction, and ML-based classification.

    </td>
    <td width="35%" valign="top">

**Stack**

<p>
  <img src="https://img.shields.io/badge/NLP-111827?style=flat-square" alt="NLP" />
  <img src="https://img.shields.io/badge/Machine%20Learning-111827?style=flat-square" alt="Machine Learning" />
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter" />
</p>

    </td>
  </tr>
</table>

<p>
  <a href="https://github.com/Bears-beets-battlestargalactica/Webappfordepressiondetectionontweets-main">
    <img src="https://img.shields.io/badge/Repository-GitHub-111827?style=for-the-badge&logo=github&logoColor=white" alt="Repository" />
  </a>
</p>

---

## 05. Twitter-Like Social Media App

<table>
  <tr>
    <td width="65%" valign="top">

**MERN-stack social media application**

A full-stack social media app with posting, authentication, user interactions, and timeline-style features. This helped me go deeper into frontend state, backend APIs, and database-backed user experiences.

    </td>
    <td width="35%" valign="top">

**Stack**

<p>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
</p>

    </td>
  </tr>
</table>

<p>
  <a href="https://github.com/Bears-beets-battlestargalactica/Twitter_new">
    <img src="https://img.shields.io/badge/Repository-GitHub-111827?style=for-the-badge&logo=github&logoColor=white" alt="Repository" />
  </a>
</p>

---

<h2 align="center">Technical Toolkit</h2>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,c,js,ts,react,nodejs,express,mongodb,postgres,docker,kubernetes,aws,azure,linux,git,github,html,css,tailwind,pytorch,tensorflow,opencv,vscode" alt="Technical skills" />
</p>

<table>
  <tr>
    <td width="25%" valign="top">
      <b>Security</b><br><br>
      Microsoft Defender XDR<br>
      Azure Sentinel<br>
      Zeek<br>
      Elastic / Kibana<br>
      SIEM workflows
    </td>
    <td width="25%" valign="top">
      <b>AI / ML</b><br><br>
      PyTorch<br>
      TensorFlow<br>
      scikit-learn<br>
      NLP<br>
      Computer Vision
    </td>
    <td width="25%" valign="top">
      <b>Engineering</b><br><br>
      React<br>
      Node.js<br>
      Express<br>
      REST APIs<br>
      Docker
    </td>
    <td width="25%" valign="top">
      <b>Data</b><br><br>
      PostgreSQL<br>
      MongoDB<br>
      Elasticsearch<br>
      Pandas<br>
      JSONL pipelines
    </td>
  </tr>
</table>

<br>

<h2 align="center">Operating Principles</h2>

<p align="center">
  <b>Build things that survive contact with real systems.</b>
</p>

<p align="center">
  Useful over flashy · Explain the messy parts · Benchmarks are a starting point · Ship, test, learn, repeat
</p>

<br>

<h2 align="center">Connect</h2>

<p align="center">
  <a href="https://www.linkedin.com/in/jibin-varghese-a48b402a6/">
    <img src="https://img.shields.io/badge/LinkedIn-Jibin%20Varghese-2563EB?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:jibinye@oregonstate.edu">
    <img src="https://img.shields.io/badge/Email-jibinye%40oregonstate.edu-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/Bears-beets-battlestargalactica">
    <img src="https://img.shields.io/badge/GitHub-Bears,%20Beets,%20Battlestar-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>
