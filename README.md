# Hi, I'm Nish 👋

**MS Operations Research @ Columbia** · ex-Data Scientist @ SWAT Mobility · BEng Robotics & AI

Building end-to-end AI systems — LLMs, statistical analysis, and data engineering applied to transit, logistics, and NLP.

---

## 🚇 Subway OTP Diagnostics
*AI-powered on-time performance diagnostic tool for transit systems*

Upload a delay CSV → get an executive-ready AI diagnosis of what's going wrong. Two-stage pipeline: rule-based pre-analysis (IQR outlier detection, delay-jump analysis, stop-sequence gap detection) feeds a structured JSON to **Gemini** for natural-language interpretation. Auto-detects column schemas, runs 7 diagnostic checks, and covers 5 real-world failure patterns. Dockerized with GitHub Actions CI/CD.

`Python` `Streamlit` `Gemini` `Plotly` `Pandas` `Docker` · 🔗 [repo](https://github.com/nniishhh/subway-otp-diagnostics)

---

## 🚗 Automatic License Plate Recognition (ANPR)
*Computer vision pipeline for license plate detection and OCR*

Detects and reads license plates from car images using **WPOD-Net**, a neural network built to handle skewed and angled plates. Includes trained model weights and real-world test samples.

`Python` `WPOD-Net` `OpenCV` `OCR` · 🔗 [repo](https://github.com/nniishhh/Automatic-License-Plate-Recognition-ANPR-)

---

## 🤖 ATS Resume Builder
*LLM pipeline that tailors resume bullets to job descriptions*

Parses job-description signals with **Gemini via LiteLLM**, generates bullets with self-repair loops enforcing 190–220 character constraints, and compiles polished PDFs via LaTeX.

`Python` `LiteLLM` `Gemini` `LaTeX` `Prompt Engineering` · 🔗 [repo](https://github.com/nniishhh/ats-resume-builder)

---

## 📧 Email Prime — AI Gmail Assistant
*Intelligent email triage and summarization on AWS Bedrock*

Auto-classifies threads and generates structured summaries. Implements **RAG with Titan embeddings + FAISS** to retrieve long-context content beyond model token limits. Deployed via Streamlit.

`Python` `AWS Bedrock` `RAG` `FAISS` `LangChain` `Streamlit`

---

## 📊 Airbnb Data Analyst Agent
*Natural-language analytics agent for Airbnb data*

Translates business questions into **SQL/Pandas workflows**, auto-generates visualizations, and produces narrative insights on pricing, occupancy, and listing trends.

`Python` `Agentic AI` `SQL` `Pandas` `LLMs`

---

## 🛠️ Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/oranich-jamkachornkiat)
