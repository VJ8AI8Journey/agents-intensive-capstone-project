# Generative AI Document Intelligence System (Hierarchical RAG)

Built a hierarchical Retrieval-Augmented Generation (RAG) system for semantic document intelligence and contextual question answering over unstructured multi-format documents.

The system combines embedding-based retrieval with LLM-driven response generation using a structured, multi-stage retrieval pipeline.

---

## 🚀 System Architecture

### 1️⃣ Document Ingestion
- Multi-format document support (PDF, images, text)
- OCR-based text extraction
- Text cleaning & normalization
- Metadata extraction

---

### 2️⃣ Hierarchical Chunking & Indexing
- Document-level segmentation
- Section-aware grouping
- Overlapping sliding-window chunking
- Token-length optimization for LLM compatibility
- Sentence-Transformer embedding generation

Chunks are stored in a vector index for semantic retrieval.

---

### 3️⃣ Multi-Stage Semantic Retrieval

Implemented a coarse-to-fine retrieval pipeline:

- **Stage 1:** Document-level semantic filtering
- **Stage 2:** Chunk-level similarity ranking
- **Stage 3:** Context aggregation for answer grounding

This hierarchical retrieval reduces noise and improves answer relevance.

---

### 4️⃣ Generation Layer (RAG)

- Retrieved evidence injected into structured prompts
- LLM-based answer synthesis
- Prompt engineering to reduce hallucination
- Modular separation between retrieval and generation

---

## 📊 Key Capabilities

- Hierarchical RAG architecture
- Embedding-based semantic search
- Coarse-to-fine retrieval strategy
- Context-aware document understanding
- Grounded LLM response generation

---

## 🛠 Tech Stack

- Python
- Sentence-Transformers
- Large Language Models (LLMs)
- OCR Processing
- Vector Similarity Search

---

## 🎯 Skills Demonstrated

- Retrieval-Augmented Generation (RAG)
- Hierarchical semantic retrieval
- Embedding-based indexing
- Prompt engineering
- LLM integration
- Scalable document intelligence system design
