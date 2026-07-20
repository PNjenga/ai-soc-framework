# AI-Driven Security Operations Center (SOC) Framework

![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![GitHub](https://img.shields.io/github/v/release/PNjenga/ai-soc-framework)

**Capstone Project** | **AI-Powered SOC with Explainability & Governance**

---

## 📋 Overview

This project presents a **conceptual AI-driven Security Operations Center (SOC) framework** designed to address key challenges in modern cybersecurity:

- Alert fatigue and high false-positive rates
- Limited interpretability of AI decisions
- Lack of proper governance and human oversight

The framework integrates **Machine Learning (XGBoost + LSTM)**, **Explainable AI (SHAP + LIME)**, **MITRE ATT&CK** mapping, and **Human-in-the-Loop Governance**.

---

## ✨ Key Features

- **Four-Layer Architecture**: Ingestion → Detection → XAI Triage → Governed Response
- **Hybrid Detection**: XGBoost for structured data + LSTM for sequential behavior
- **Explainable AI**: SHAP and LIME for transparent decision-making
- **MITRE ATT&CK Integration**: Contextual threat intelligence
- **Responsible AI**: Human validation, audit logging, and override capabilities

---

## 📁 Project Structure

```bash
ai-soc-framework/
├── docs/                          # Documentation & Full Report
├── src/                           # Prototype Source Code
│   ├── layer1-ingestion/
│   ├── layer2-detection/
│   ├── layer3-xai/
│   └── layer4-hitl/
├── images/                        # Architecture & Dashboard Diagrams
├── models/                        # ML Models
├── appendices/                    # Supporting Materials
├── reports/                       # Evaluation Outputs
└── tests/                         # Unit Tests
