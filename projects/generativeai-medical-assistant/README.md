# GenerativeAI Medical Assistant — RAG-based Medical Plan Q&A

## 📌 Problem Statement
Build a Generative AI assistant that answers medical plan / healthcare questions using a trusted knowledge base (documents), minimizing hallucinations and clearly communicating when information is not available.

This project demonstrates an end-to-end **Retrieval-Augmented Generation (RAG)** workflow:
- Document ingestion → chunking → embeddings
- Vector retrieval (top-k context)
- LLM answer generation grounded in retrieved sources
- Safety-oriented response behavior

---

## 🎯 Objectives
- Improve accuracy and trustworthiness of responses using document-grounded answers
- Reduce hallucinations via retrieval + refusal behavior when context is insufficient
- Provide an architecture that can be extended to production systems

---

## 🧩 Solution Overview (High Level)
1. **Ingestion**
   - Load knowledge documents
   - Clean/normalize text
   - Chunking strategy for retrieval

2. **Indexing / Embeddings**
   - Create embeddings for chunks
   - Store vectors in a searchable index

3. **Retrieval**
   - Query → retrieve top-k relevant chunks
   - (Optional) reranking

4. **Generation**
   - Prompt the LLM with retrieved context
   - Enforce “answer only from provided context” behavior

5. **Guardrails**
   - Refuse or return “no context” when insufficient evidence exists
   - Avoid medical diagnosis; provide informational responses with appropriate language

---

## 🛠 Tools & Technologies
- Python
- Jupyter Notebook
- NLP libraries (as used in notebook)
- Embeddings + Vector Search (RAG)
- LLM prompting (GenAI)

---

## ✅ Evaluation Approach
Typical evaluation methods used in RAG systems:
- Spot-check correctness against known answers in KB
- Evaluate grounding (does answer cite or reflect retrieved content?)
- Measure “no answer” behavior when retrieval has no relevant content

---

## 🔑 Key Learnings
- RAG improves factuality versus pure LLM responses
- Chunking and retrieval quality strongly impact answer quality
- Clear refusal behavior is essential for user trust in healthcare use cases

---

## 📁 Repository Structure

