# Hi, I'm Nish 👋

**MS Operations Research @ Columbia** · ex-Data Scientist @ SWAT Mobility · BEng Robotics & AI

Building end-to-end AI systems — LLMs, statistical analysis, and data engineering applied to transit, logistics, and NLP.

---

## 🚇 Subway OTP Diagnostics
*AI-powered on-time performance diagnostic tool for transit systems*

Upload a delay CSV → get an executive-ready AI diagnosis of what's going wrong.

- **Two-stage pipeline** — rule-based pre-analysis (IQR outlier detection, delay-jump analysis, stop-sequence gap detection) feeds a structured JSON to **Gemini** for natural-language interpretation. The LLM never sees raw data.
- **Auto-schema detection** — fuzzy-matches column names so it works with any transit dataset out of the box.
- **7 diagnostic checks**: sensor anomaly, missing records, join mapping quality, service pattern mismatch, operational disruption, quality pressure, insufficient evidence.
- **5 real-world scenario patterns** with curated sample data. Dockerized + GitHub Actions CI/CD.

`Python` `Streamlit` `Gemini` `Plotly` `Pandas` `Docker`

🔗 [github.com/nniishhh/subway-otp-diagnostics](https://github.com/nniishhh/subway-otp-diagnostics)

---

## 🚗 Automatic License Plate Recognition (ANPR)
Uses **WPOD-Net** to detect and read license plates from car images, handling skewed and angled plates. Includes trained model weights and real-world test samples.

`Python` `WPOD-Net` `OpenCV` `OCR` · 🔗 [repo](https://github.com/nniishhh/Automatic-License-Plate-Recognition-ANPR-)

---

## 🤖 ATS Resume Builder
Gemini + LiteLLM pipeline that tailors resume bullets to job descriptions with self-repair loops enforcing character constraints, compiled to PDF via LaTeX.

`Python` `LiteLLM` `Gemini` `LaTeX` · 🔗 [repo](https://github.com/nniishhh/ats-resume-builder)

---

## 📧 Email Prime — AI Gmail Assistant
AWS Bedrock assistant that auto-classifies threads and generates summaries using **RAG (Titan + FAISS)** to handle long-context content beyond token limits.

`AWS Bedrock` `RAG` `FAISS` `LangChain` `Streamlit`

---

## 📊 Airbnb Data Analyst Agent
Agentic assistant that translates natural-language questions into SQL/Pandas workflows, auto-generates visualizations and narrative insights.

`Agentic AI` `SQL` `Pandas` `LLMs`

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
