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
│
├── 📄 README.md                  # Description complète du projet (vue sur GitHub)
├── 📦 requirements.txt           # Liste des dépendances Python
├── ⚙️ .env.example               # Exemple de configuration d'environnement
├── 🚫 .gitignore                 # Fichiers à ignorer par Git
│
├── 📓 llm_eval_guardrails.ipynb  # Notebook principal (le cœur du projet)
│
├── 📂 app/                       # (optionnel) modules Python si tu sépares ton code
│   ├── metrics.py                # Calcul des métriques EM, F1, etc.
│   ├── pii_detector.py           # Détection PII (emails, phones, etc.)
│   ├── redteam.py                # Prompts de red teaming / jailbreaks
│   └── llm_client.py             # Client pour Ollama / HTTP API
│
├── 📂 data/                      # Jeux de tests et entrées de validation
│   ├── sample_tests.json
│   └── redteam_prompts.txt
│
├── 📂 artifacts/                 # Sorties générées
│   ├── results.csv
│   └── results.json
│
├── 📂 assets/                    # Images, graphiques, captures d’écran
│   ├── dashboard.png
│   └── latency_chart.png
│
└── 📜 LICENSE                    # Licence (MIT, Apache 2.0, etc.)

---
