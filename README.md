# 💼 Portfolio – Code Writing & AI Systems Development

Welcome to my technical portfolio. Below are selected projects showcasing my work across multilingual NLP, AI agent development, model fine-tuning, and database integration.

---

## 🔁 Multilingual Neural Machine Translation (NMT)  
**Fine-Tuning Facebook’s NLLB-200-distilled-600M**

**Technologies:** `Hugging Face Transformers`, `PEFT (QLoRA)`, `BitsAndBytes`, `PyTorch`, `Seq2Seq`, `TensorBoard`, `FAISS`

Fine-tuned a high-capacity multilingual translation model (`facebook/nllb-200-distilled-600M`) for low-resource African languages:

- 🌍 **Target Languages:** Yoruba, Igbo, Hausa, Wolof, Swahili, Zulu  
- 🧠 **Fine-tuning Strategy:** Seq2Seq with parameter-efficient training using QLoRA  
- 🗜️ **Optimization:** 8-bit quantization via `BitsAndBytes`  
- 📊 **Evaluation:** Metrics like BLEU, SacreBLEU, ChrF++  
- 📁 **Data Handling:** Used `DataCollatorForSeq2Seq`, custom preprocessing pipelines, and dataset balancing  

> ✅ Result: Produced a robust, efficient translation model capable of accurate English-to-African-language translations.

---

## 🤖 Multi-Agent AI Language Routing System  
**Modular Agent System with CrewAI & LangChain**

**Technologies:** `CrewAI`, `LangChain`, `FAISS`, `Python`, `Hugging Face`, `nomic-embed-text, llama-based models`

Built an intelligent **multi-agent architecture** to route translation requests based on detected language and task complexity:

- 👥 **13 AI Agents** built using `CrewAI`, each with domain-specific responsibilities  
- 🧠 **Vector-Based Context Retrieval:** Using `FAISS` + `nomic-embed-text` for retrieval-augmented workflows  
- 📦 **Routing Logic:** Conditional delegation to specific translation agents based on language & complexity  
- 🔗 **LLM Integration:** Hooked up fine-tuned NLLB models and LangChain tools for autonomous reasoning  

> ✅ Result: Deployed a functional agent-based translation router with end-to-end orchestration and memory buffers.

---

## 👨🏽‍💻 Tech Lead, Data & Generative AI Group  
**Tecvinson Academy [https://www.linkedin.com/company/tecvinson-academy | www.tecvinsonacademy.com]**

- 🧑‍🏫 **Role:** Led a team of aspiring ML engineers and data scientists  
- 📚 **Curriculum Design:** LLM fine-tuning, LangChain agent systems, Hugging Face workflows  
- ⚙️ **Mentorship:** Guided junior members through MLOps, SQL, NLP, and deployment strategies  
- 🛠️ **Project Focus:** Translation pipelines, generative agents, real-world use-case simulations  

> ✅ Result: Spearheaded AI initiatives and helped deploy several experimental NLP tools within the academy.

---

## 🗄️ SQL & Relational Databases  
**Structured Querying & Data Engineering for NLP**

**Technologies:** `SQL`, `MySQL`, `SQLite`, `LangChain SQLAgent` (ongoing)

- 📂 Designed normalized relational databases for multilingual corpora  
- 🧮 Built SQL queries for evaluation metrics logging and feature extraction  
- 🔄 Exploring use of SQL + LangChain for semantic querying of structured datasets  

> ✅ Result: Solid foundational experience in relational data modeling and querying pipelines for AI workflows.

---

## 🛠️ Technical Skillset

| Domain                 | Tools & Technologies                                                                       |
|------------------------|----------------------------------------------------------------------                      |
| **ML/NLP**             | Hugging Face, PyTorch, PEFT (QLoRA), Transformers, BitsAndBytes                            |
| **AI Agents**          | CrewAI, LangChain, FAISS, ChromaDB, nomic-embed-text, Retrieval-Augmented Gen., LangGraph  |
| **Quantization**       | 8-bit Inference, ONNX Export, BitsAndBytes                                                 |
| **Data Engineering**   | SQL, MySQL, Pandas, DataCollatorForSeq2Seq                                                 |
| **Monitoring**         | TensorBoard, BLEU/SacreBLEU/ChrF++                                                         |
| **Deployment**         | Chainlit, Streamlit                                                                        |

---

## 📌 Featured Repositories

- [NLLB Multilingual Translation Fine-Tuning](#)
- [AI Agent Routing System](#)

---

## 📬 Contact

- 📧 **Email:** tkevin.dibia@gmail.com 
- 🐙 **GitHub:** [github.com/your-username](https://github.com/DibiaCorp85)  
- 🔗 **LinkedIn:** [linkedin.com/in/your-profile](www.linkedin.com/in/kevin-t-dibia)

---
