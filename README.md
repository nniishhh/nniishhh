# Hi, I'm Nish

**MS Operations Research @ Columbia** · ex-Data Scientist @ SWAT Mobility · BEng Robotics & AI

Passionate about turning data into decisions — skilled in machine learning, LLMs, data engineering, statistical modeling, and building end-to-end AI pipelines.

---

## Subway OTP Diagnostics

*AI-powered on-time performance diagnostic tool for transit systems*

Upload a delay CSV and get an executive-ready AI diagnosis of what's going wrong.

Two-stage pipeline: rule-based pre-analysis using IQR outlier detection, delay-jump analysis, and stop-sequence gap detection. The pipeline feeds structured JSON to Gemini for natural-language interpretation. It auto-detects column schemas, runs 7 diagnostic checks, and covers 5 real-world failure patterns. Dockerized with GitHub Actions CI/CD.

`Python` `Streamlit` `Gemini` `Plotly` `Pandas` `Docker`  
[Repo](https://github.com/nniishhh/subway-otp-diagnostics)

---

## Automatic License Plate Recognition

*Computer vision pipeline for license plate detection and OCR*

Detects and reads license plates from car images using WPOD-Net, a neural network built to handle skewed and angled plates. Includes trained model weights and real-world test samples.

`Python` `WPOD-Net` `OpenCV` `OCR`  
[Repo](https://github.com/nniishhh/Automatic-License-Plate-Recognition-ANPR-)

---

## ATS Resume Builder

*LLM pipeline that tailors resume bullets to job descriptions*

Parses job-description signals with Gemini via LiteLLM, generates bullets with self-repair loops enforcing 190–220 character constraints, and compiles polished PDFs via LaTeX.

`Python` `LiteLLM` `Gemini` `LaTeX` `Prompt Engineering`  
[Repo](https://github.com/nniishhh/ats-resume-builder)

---

## Email Prime — AI Gmail Assistant

*Intelligent email triage and summarization on AWS Bedrock*

Auto-classifies threads and generates structured summaries. Implements RAG with Titan embeddings and FAISS to retrieve long-context content beyond model token limits. Deployed via Streamlit.

`Python` `AWS Bedrock` `RAG` `FAISS` `LangChain` `Streamlit`

---

## Airbnb Data Analyst Agent

*Natural-language analytics agent for Airbnb data*

Translates business questions into SQL/Pandas workflows, auto-generates visualizations, and produces narrative insights on pricing, occupancy, and listing trends.

`Python` `Agentic AI` `SQL` `Pandas` `LLMs`

---

## Stack

Python · SQL · PySpark · LangChain · AWS · Docker · Streamlit · Tableau

---

[LinkedIn](https://linkedin.com/in/oranich-jamkachornkiat)
