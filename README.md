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

```bash
llm-eval-guardrails/
├── llm_eval_guardrails.ipynb   # Notebook principal : évaluation et guardrails LLM
├── requirements.txt            # Dépendances Python nécessaires
├── README.md                   # Documentation du projet
├── LICENSE                     # Licence open source (MIT)
├── .env.example                # Exemple de configuration d’environnement
│
├── app/                        # (Optionnel) scripts Python modulaires
│   ├── metrics.py              # Calcul des métriques EM, F1, latence
│   ├── pii_detector.py         # Détection d’emails, numéros et IBAN
│   ├── redteam.py              # Prompts de red teaming / jailbreak
│   └── llm_client.py           # Client Ollama / HTTP API / mock
│
├── data/                       # Jeux de tests (Q&A, jailbreak, etc.)
│   ├── sample_tests.json       # Exemples de scénarios
│   └── redteam_prompts.txt     # Prompts d’attaque adversariale
│
├── artifacts/                  # Sorties et rapports générés
│   ├── results.csv             # Tableau de résultats métriques
│   └── results.json            # Résultats exportés en JSON
│
└── assets/                     # Images et illustrations du README
    ├── dashboard.png           # Exemple de dashboard
    └── latency_chart.png       # Distribution de latence

└── assets/ # Images et illustrations du README
├── dashboard.png # Exemple de dashboard
└── latency_chart.png # Distribution de latence

---
