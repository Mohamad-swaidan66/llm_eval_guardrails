# 🧩 LLM Evaluation & Guardrails — Notebook Version

![Python](https://img.shields.io/badge/python-3.10%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Jupyter](https://img.shields.io/badge/Notebook-Ready-orange)

A single Jupyter Notebook to **evaluate**, **analyze**, and **stress-test** Large Language Models (LLMs).  
This project includes **metrics**, **PII detection**, **red teaming**, and **visual analytics** — all in one lightweight file.

---

## 🚀 Overview

**LLM Evaluation & Guardrails** provides a minimal yet powerful framework to test how reliable, safe, and robust a model is.  
It helps you measure **accuracy**, **PII safety**, and **robustness** with a simple notebook interface.

### ✨ Features
- 📊 **Metrics:** Exact Match (EM), token-level F1, latency tracking  
- 🔐 **PII Detection:** regex-based checks for emails, phone numbers, and IBAN-like patterns  
- 🧨 **Red Teaming:** jailbreak and adversarial prompt testing  
- ⚡ **Plug-and-Play LLM Client:** compatible with Ollama (local), HTTP APIs, or mock mode  
- 📈 **Visualization:** charts for accuracy and latency  
- 💾 **Export:** save results as `.csv` and `.json` for later analysis  

---

## 🧠 Motivation

Modern LLMs are powerful — but how **safe** and **consistent** are they?  
This notebook lets you locally benchmark any LLM, detect privacy leaks, and probe robustness without complex setup.

Perfect for:
- 🤖 AI / ML engineers  
- 🎓 Students & researchers in NLP or AI safety  
- 🧪 Developers testing local or hosted LLMs  

---

## 📁 Project Structure

llm-eval-guardrails/
├── llm_eval_guardrails.ipynb # Main notebook
├── requirements.txt # Dependencies
├── .env.example # Example environment config
├── .gitignore # Ignore virtualenv & secrets
│
├── artifacts/ # Output results
│ ├── results.csv
│ └── results.json
│
├── assets/ # (Optional) images for README
│ ├── dashboard.png
│ └── latency_chart.png
│
└── data/ # (Optional) test examples
├── sample_tests.json
└── redteam_prompts.txt
---
