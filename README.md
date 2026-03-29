<div align="center">

# Anas Abd El-Aziz
### AI Engineer · LLM Agents · Multi-Agent Systems · Production AI

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anas-abd-el-aziz-22a277218/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anas.abdelaziz.dev@gmail.com)
[![Location](https://img.shields.io/badge/Cairo,%20Egypt-00A86B?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

## 👋 About Me

I'm an AI Engineer focused on **LLM agents and multi-agent systems**, with a track record of shipping production AI — from a real-time voice call center with sub-second latency to a multimodal RAG platform processing full academic curricula.

I work across the full stack of AI deployment: agent architecture, retrieval design, and the infrastructure to run it reliably.

```
Voice Pipelines · Multi-Agent Orchestration · RAG Systems · CI/CD · Docker
```

---

## 🚀 Featured Projects

### 🎙️ [Real-Time AI Voice Call Center](https://github.com/Anas-Abd-ElAziz/AI-Call-Center)
> **Production-deployed** multi-agent voice system built with LiveKit

- 4 role-specialized agents (onboarding → tier-1 → escalation → feedback) with live mid-call handoff
- Sub-second end-to-end pipeline: **Deepgram STT** + **Silero VAD** → **OpenAI** tool-calling → **Cartesia TTS**
- Post-call feedback loop writing to Google Sheets + automated SMTP confirmation emails
- Containerized with **Docker**, auto-deployed via **GitHub Actions CI/CD** on every push

`Python` `LiveKit` `LangGraph` `OpenAI` `Docker` `GitHub Actions`

---

### 📊 [LLM Data Analysis Agent](https://github.com/Anas-Abd-ElAziz/Data-science-agent)
> **Conversational agent** that dynamically executes LLM-generated Python against user CSV datasets

- Custom `START → Agent → Tools → Store → END` LangGraph graph with Gemini 2.5 Flash
- `python_repl` tool with runtime library injection (Pandas, Plotly, scikit-learn) and LLM code sanitization
- Full multi-turn memory via **LangGraph checkpointing**, DataFrame embedded directly in graph state
- **Streamlit** UI with CSV upload, interactive Plotly charts, and per-turn tool execution logs

`Python` `LangGraph` `LangChain` `Gemini 2.5` `Streamlit` `Plotly`

---

### 🎓 AI-Powered Educational Automation Platform *(Private)*
> End-to-end **n8n automation pipeline** + multimodal RAG for academic content

- Ingests eBooks via **Mistral OCR**, extracts TOC/exercises/Q&A, annotates images with Mistral Vision
- Custom chunking at section/subsection level with per-page metadata → indexed in **Supabase** via Gemini embeddings
- Multi-agent teacher system routing queries to specialized explanation, problem-solving, and assessment agents
- Optimized token usage by replacing inline Base64 images with hosted URLs

`n8n` `Mistral` `Gemini` `Supabase` `RAG` `Multi-Agent`

---

### 🔍 [Real-Time Anomaly Detection](https://github.com/Anas-Abd-ElAziz/Realtime-Anomaly-Detection)
> Graduation project — **95.6% AUC** on surveillance video anomaly scoring

- Two-stage pipeline: **YOLOv8** object detection (0.25s/frame) → **I3D** spatiotemporal features → **RTFM** anomaly scoring
- Engineered for real-time constraints on GTX 1660 GPU, multi-camera feed support
- Automated email alerting on anomaly detection
- Published as graduation thesis at **Ain Shams University**

`Python` `YOLOv8` `PyTorch` `I3D` `RTFM` `Computer Vision`

---

## 🛠️ Tech Stack

<div align="center">

| Category | Tools |
|---|---|
| **Languages** | Python, SQL |
| **AI / LLM** | LangChain, LangGraph, OpenAI API, Gemini API, Mistral, Claude |
| **ML Frameworks** | PyTorch, TensorFlow, scikit-learn |
| **RAG & Retrieval** | Supabase Vector DB, custom chunking, embedding pipelines |
| **Automation** | n8n, API integrations |
| **Databases** | MSSQL Server, Supabase, Vector DBs |
| **Deployment** | Docker, GitHub Actions, Flask, Streamlit |
| **Data** | Pandas, NumPy, Plotly, Matplotlib, Seaborn |

</div>

---

## 📈 GitHub Stats

<div align="center">

![Anas's GitHub stats](https://github-readme-stats.vercel.app/api?username=Anas-Abd-ElAziz&show_icons=true&theme=tokyonight&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Anas-Abd-ElAziz&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## 🎓 Education & Certifications

- 🎓 **B.Sc. Computer Science** — Ain Shams University, Cairo *(2019–2023)*
  - Graduation Project: Real-Time Anomaly Detection in Surveillance Videos
- 📜 **Certified Data Scientist Professional** — Epsilon AI *(2021–2022)*

---

<div align="center">

*Open to AI engineering roles — building intelligent systems at scale.*

[![LinkedIn](https://img.shields.io/badge/Let's%20Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anas-abd-el-aziz-22a277218/)

</div>
