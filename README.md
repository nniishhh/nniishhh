# Hi, I'm Nish 👋

**MS Operations Research @ Columbia** · ex-Data Scientist @ SWAT Mobility (Singapore) · BEng Robotics & AI

I build end-to-end AI systems — from messy real-world data to deployed, production-ready pipelines. My work lives at the intersection of **LLMs**, **statistical analysis**, and **data engineering**, applied to transit, logistics, and NLP.

---

## 🚇 Subway OTP Diagnostics

> *AI-powered on-time performance diagnostic tool for transit systems*

Upload a GTFS-style delay CSV and get an **executive-ready AI diagnosis** of what's going wrong — in seconds.

**What makes it interesting under the hood:**

- **Two-stage intelligence pipeline** — a rule-based pre-analysis engine runs first (IQR outlier detection, delay-jump analysis, stop-sequence gap detection, match-status scoring), then passes a structured JSON payload to **Gemini** for natural-language interpretation. The LLM never sees raw data — only a curated evidence summary.
- **Auto-schema detection** — the app fuzzy-matches column names so it works with any transit dataset out of the box, no config needed.
- **7 diagnostic checks** with scored signals: sensor anomaly, missing records, join mapping quality, service pattern mismatch, operational disruption, quality pressure, insufficient evidence.
- **5 real-world scenario patterns** — isolated extreme delays, recurring bottleneck, schedule vs. actual mismatch, missing trip records, network-wide slowdown — each with curated sample data.
- **Chart-ready outputs** — delay distributions, station-hour heatmaps, per-trip OTP, delay jump event tables.
- Fully **Dockerized** with **GitHub Actions CI/CD** deployment.

`Python` `Streamlit` `Gemini` `Plotly` `Pandas` `Docker` `GitHub Actions`

🔗 [github.com/nniishhh/subway-otp-diagnostics](https://github.com/nniishhh/subway-otp-diagnostics)

---

## 🚗 Automatic License Plate Recognition (ANPR)

> *End-to-end computer vision pipeline for license plate detection and OCR*

Detects and reads license plates from car images using **WPOD-Net** (Warped Planar Object Detection), a specialized neural network that handles skewed and angled plates. Includes trained model weights and 10 real-world test samples.

`Python` `Jupyter Notebook` `WPOD-Net` `OpenCV` `OCR` `Computer Vision`

🔗 [github.com/nniishhh/Automatic-License-Plate-Recognition-ANPR-](https://github.com/nniishhh/Automatic-License-Plate-Recognition-ANPR-)

---

## 🤖 ATS Resume Builder

> *LLM pipeline that tailors resume bullets to job descriptions*

End-to-end resume generation using **Gemini via LiteLLM**. Parses job-description signals, generates bullets with self-repair loops that enforce a 190–220 character constraint, and compiles polished PDFs via LaTeX.

`Python` `LiteLLM` `Gemini` `LaTeX` `Prompt Engineering`

🔗 [github.com/nniishhh/ats-resume-builder](https://github.com/nniishhh/ats-resume-builder)

---

## 📧 Email Prime — AI Gmail Assistant *(Columbia, 2025)*

AWS Bedrock-powered assistant that auto-classifies email threads and generates structured summaries. Implements **RAG with Titan embeddings + FAISS** to handle long-context threads beyond model token limits. Deployed via Streamlit.

`Python` `AWS Bedrock` `RAG` `FAISS` `LangChain` `Streamlit`

---

## 📊 Airbnb Data Analyst Agent *(Columbia, 2025)*

Agentic analytics assistant that translates natural-language business questions into **SQL/Pandas workflows**, auto-generates visualizations, and produces narrative insights on pricing, occupancy, and listing trends.

`Python` `Agentic AI` `SQL` `Pandas` `LLMs`

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)

---

## 📈 GitHub Stats

![Nish's GitHub Stats](https://github-readme-stats.vercel.app/api?username=nniishhh&show_icons=true&theme=default&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=nniishhh&layout=compact&hide_border=true&theme=default)

---

## 📬 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/oranich-jamkachornkiat)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:oj2191@columbia.edu)
