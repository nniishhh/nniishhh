# Nish Jamkachornkiat

**MS Operations Research @ Columbia University**  
**Data Science · Optimization · Analytics Engineering · Agentic AI**

I build data and AI systems that turn messy operational data into clear decisions — from transit performance diagnostics and forecasting workflows to LLM-powered analytics tools.

Currently focused on **data science, operations research, transportation analytics, and practical AI systems**.

[LinkedIn](https://linkedin.com/in/oranich-jamkachornkiat) · [GitHub](https://github.com/nniishhh)

---

## Selected Projects

| Project | What it does | Stack |
|---|---|---|
| [Subway OTP Diagnostics](https://github.com/nniishhh/subway-otp-diagnostics) | Diagnoses subway on-time performance issues from delay data and produces executive-ready explanations. | Python, Streamlit, Gemini, Plotly, Pandas, Docker |
| [Airbnb Data Analyst Agent](https://github.com/Agentic-AI-Project-Columbia/airbnb-data-analyst-agent) | Natural-language analytics agent that converts business questions into SQL/Pandas workflows, charts, and narrative insights. | Python, SQL, Pandas, LLMs, Agentic AI |
| Email Prime — AI Gmail Assistant | Classifies email threads, summarizes long-context content, and supports email triage using retrieval-augmented generation. | Python, AWS Bedrock, RAG, FAISS, LangChain, Streamlit |
| [ATS Resume Builder](https://github.com/nniishhh/ats-resume-builder) | LLM pipeline that tailors resume bullets to job descriptions and compiles polished PDFs with LaTeX. | Python, LiteLLM, Gemini, LaTeX |
| [Automatic License Plate Recognition](https://github.com/nniishhh/Automatic-License-Plate-Recognition-ANPR-) | Computer vision pipeline for license plate detection and OCR using WPOD-Net. | Python, OpenCV, OCR, WPOD-Net |

---

## Project Highlights

### Subway OTP Diagnostics

An AI-assisted diagnostic tool for transit performance analysis. Upload a delay CSV and receive a structured diagnosis of what is going wrong, where the issue is concentrated, and whether the pattern looks operational or data-related.

- Runs rule-based pre-analysis using IQR outlier detection, delay-jump analysis, and stop-sequence gap detection.
- Auto-detects column schemas and performs 7 diagnostic checks across 5 real-world failure patterns.
- Feeds structured JSON into Gemini for concise, executive-ready interpretation.
- Dockerized with GitHub Actions CI/CD for reproducible deployment.

**Tools:** Python, Streamlit, Gemini, Plotly, Pandas, Docker  
**Repo:** [subway-otp-diagnostics](https://github.com/nniishhh/subway-otp-diagnostics)

### Airbnb Data Analyst Agent

A multi-agent analytics system that helps users explore Airbnb market data through natural-language questions.

- Translates business questions into SQL/Pandas workflows.
- Generates charts and written insights on pricing, availability, demand, and investment potential.
- Designed with specialized agents for pricing, demand, and investment analysis.

**Tools:** Python, SQL, Pandas, LLMs, Agentic AI  
**Repo:** [airbnb-data-analyst-agent](https://github.com/Agentic-AI-Project-Columbia/airbnb-data-analyst-agent)

### Email Prime — AI Gmail Assistant

An AI assistant for email triage and summarization using AWS Bedrock and retrieval-augmented generation.

- Auto-classifies email threads and generates structured summaries.
- Uses Titan embeddings and FAISS to retrieve long-context content beyond model token limits.
- Built as a Streamlit application for interactive review and workflow support.

**Tools:** Python, AWS Bedrock, RAG, FAISS, LangChain, Streamlit

### ATS Resume Builder

An LLM-powered resume tailoring pipeline that converts job descriptions into targeted resume bullets.

- Parses job-description signals using Gemini via LiteLLM.
- Generates resume bullets with self-repair loops for length and formatting constraints.
- Compiles polished PDF outputs through LaTeX.

**Tools:** Python, LiteLLM, Gemini, LaTeX, Prompt Engineering  
**Repo:** [ats-resume-builder](https://github.com/nniishhh/ats-resume-builder)

### Automatic License Plate Recognition

A computer vision pipeline for license plate detection and OCR.

- Uses WPOD-Net to detect skewed and angled license plates.
- Includes trained model weights and real-world test samples.
- Applies OpenCV and OCR techniques for end-to-end plate recognition.

**Tools:** Python, WPOD-Net, OpenCV, OCR  
**Repo:** [Automatic-License-Plate-Recognition-ANPR-](https://github.com/nniishhh/Automatic-License-Plate-Recognition-ANPR-)

---

## Technical Toolkit

**Languages:** Python, SQL  
**Data & ML:** Pandas, NumPy, scikit-learn, statistical modeling, forecasting, clustering  
**AI & LLMs:** Gemini, AWS Bedrock, LangChain, RAG, FAISS, prompt engineering  
**Visualization & Apps:** Streamlit, Plotly, Tableau  
**Engineering:** Docker, GitHub Actions, CI/CD, Git

---

## What I like building

- Decision-support tools for operations and transportation teams
- Forecasting and diagnostics workflows for messy business data
- LLM-powered analytics agents that turn questions into structured analysis
- Clear dashboards and summaries for non-technical stakeholders
