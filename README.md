# Clinical Decision Making & Pattern Recognition in Health Care
### Cotiviti Intern Assessment — Topic 2

**Author:** Sree Vardhan Sunkara
**University:** University of Houston — M.S. Engineering Data Science
**Date:** June 2026
**Contact:** sreevardhan23@gmail.com

---

## Overview

This repository contains my complete submission for the Cotiviti Intern Assessment.
I selected **Topic 2: Clinical Decision Making and Pattern Recognition in Health Care**,
covering agentic generative AI, classification, prediction, and anomaly detection for
Treatment, Payment, and Operations (TPO).

The proof of concept is a working **3-agent AI pipeline** that detects anomalous
healthcare claims using:

- **XGBoost** — gradient boosting classifier with SMOTE class balancing
- **SHAP** — explainable AI attribution for every individual prediction
- **FAISS + Sentence Transformers** — retrieval-augmented generation (RAG) for semantic policy retrieval
- **3-Agent Orchestration** — Classifier Agent → RAG Agent → Summary Agent

---

## Repository Contents

| File | Description |
|---|---|
| `Cotiviti_FINAL_SUBMISSION_REPORT.docx` | Written report — concept, trends, opportunities & threats, strategic recommendations, APA bibliography |
| `CotivitiPOC_Vardhan_FINAL.ipynb` | Hackathon proof of concept — fully executable Google Colab notebook |
| `Cotiviti_Presentation_Final.pptx` | Slide presentation — 16 slides with real model results |
| `VIDEO_LINK.md` | Link to the recorded video presentation and POC demo walkthrough |

---

## How to Run the POC

The notebook runs entirely in **Google Colab** with zero setup required.

1. Open [Google Colab](https://colab.research.google.com)
2. Click **File → Upload notebook** and upload `CotivitiPOC_Vardhan_FINAL.ipynb`
3. Click **Runtime → Run all**
4. All libraries install automatically — no API keys needed
5. Total runtime: approximately **3 minutes**

---

