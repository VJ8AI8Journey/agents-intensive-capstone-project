# Hierarchical Semantic Multi-Agent Document QA System

This project implements a multi-agent, document-grounded AI system that reads, summarizes, and answers questions from large policy documents with strict numerical accuracy and full traceability.

---

## 🚀 Features

- ✅ Multi-Agent LLM Architecture
- ✅ Hierarchical Semantic Memory (Tree-Based)
- ✅ Adaptive Summary vs Full-Text Answering
- ✅ Strict Numeric Extraction (No Hallucinated Deadlines)
- ✅ OCR + PDF Support
- ✅ Semantic Routing using Sentence Transformers
- ✅ Full Observability (Logs, Routing, Latency, Metrics)
- ✅ Automatic Evaluation (Exact Match & F1)
- ✅ Google Colab Deployment (GPU-Compatible)

---

## 🧠 Architecture Overview

PDF → OCR → Page Chunks → Hierarchical Summaries → Semantic Routing → Adaptive QA → Strict Numeric Validation → Evaluation

---

## 🔧 Installation (Google Colab)

```bash
pip install torch transformers sentence-transformers pytesseract pymupdf scikit-learn
