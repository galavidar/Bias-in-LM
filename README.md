# Bias-in-LLM
# JustiLM – Bias-Aware Pretrial Risk Assessment Using Language Models

## 🧠 Overview

**JustiLM** is an AI-based decision-support system designed to assist judges in pretrial detention decisions. The system takes a short textual summary of a criminal case and returns a **numerical risk estimate** — the likelihood that a defendant will commit another offense if released before trial.

This project explores the **ethical, legal, and societal implications** of deploying such a system, with a focus on **bias detection and mitigation** in language models. It includes the implementation of the model, generation of synthetic data, and a structured auditing plan.

---

## ⚖️ Motivation

Pretrial decisions affect the liberty of individuals who have not been convicted. Human judgments in such cases are subject to inconsistencies and unconscious biases. JustiLM aims to:

- Promote consistency in judicial decisions.
- Reduce bias based on gender, ethnicity, or socioeconomic status.
- Enhance transparency and accountability in legal AI systems.

However, language models trained on biased or synthetic data can reinforce or introduce new biases. This repository addresses that through technical design, documentation, and auditing.

---

## 🧪 How It Works

1. **Input**: A short text summary of a legal case.
2. **Output**: A risk percentage (e.g., `72%`).
3. **Policy Recommendation**:
   - < 40% → Release
   - 40–70% → Release with Bail
   - > 70% → Pretrial Detention

Model outputs are suggestions only; final decisions remain with the judge.


---

*This project is for academic purposes only

