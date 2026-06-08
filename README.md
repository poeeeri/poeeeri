# Hi, I'm Purbo-Suruna (Alexandra) 👋

ML Engineer focused on **NLP**, interested in **CV** and practical ML systems.  
I build pet projects end-to-end: from dataset preparation and model training to deployment, monitoring, and backend integration.

## Tech Stack

**ML / DL:** PyTorch, Scikit-learn, NLP, CV, sentence-transformers, Hugging Face  
**Data:** pandas, SQL, PostgreSQL, Oracle  
**Backend / APIs:** FastAPI, aiogram  
**MLOps / Infra:** Docker, Linux, ClearML, Apache Airflow, Grafana, Ansible, Git  

## Featured Projects

### [Chebubrya Memes Bot](https://github.com/poeeeri/chebubrya-memes-bot)
Telegram bot for semantic meme retrieval in group chats.

This project combines NLP, retrieval models, reranking, backend integration, deployment, and basic security automation.

- Built a dataset indexing pipeline for meme descriptions, OCR text, and semantic annotations
- Implemented semantic retrieval with **sentence-transformers** and **ChromaDB**
- Fine-tuned a local retrieval model based on multilingual embedding models
- Added reranking with a fine-tuned local **CrossEncoder** model
- Compared local retrieval/reranking with API-based models using **Recall@K** and **MRR**
- Integrated the retrieval pipeline into a Telegram bot with **aiogram**
- Added PostgreSQL logging for requests, selected candidates, and user feedback
- Collected feedback through inline buttons for future model improvement
- Deployed the service on a remote Linux server with **Docker Compose**
- Added security checks with **Bandit**, **pip-audit**
- Configured a GitHub Actions workflow for automated SAST and dependency scanning

**Stack:** `Python` `PyTorch` `sentence-transformers` `CrossEncoder` `ChromaDB` `PostgreSQL` `aiogram` `Docker` `Linux` `GitHub Actions` `Bandit` `pip-audit`

---

### [Mindly Memory Agent](https://github.com/poeeeri/Mindly-Memory-Agent)
Conversational LLM agent with persistent long-term user memory.

- Built a FastAPI backend for streaming LLM responses through OpenRouter
- Designed an agent workflow with **LangGraph**
- Implemented long-term memory with **MemPalace / ChromaDB**
- Added structured fact extraction from user messages
- Separated short-term chat history from persistent user memory
- Added PostgreSQL support for chat history persistence
- Dockerized the application and connected it with a React/Vite WebUI

**Stack:** `Python` `FastAPI` `LangGraph` `LLM` `OpenRouter` `MemPalace` `ChromaDB` `PostgreSQL` `React` `Docker`

---

### [License Detector](https://github.com/poeeeri/license-detector)
System for vehicle license plate detection and OCR.

- Prepared a custom dataset
- Trained **YOLOv8** for plate detection
- Integrated **TrOCR / Hugging Face** for text recognition
- Ran A/B testing with fine-tuned **PPOCRv5**
- Set up inference for video streams and camera input
- Added experiment tracking and monitoring with **ClearML**

**Stack:** `YOLOv8` `TrOCR` `Hugging Face` `ClearML` `CV`

---

### [Banking Support](https://github.com/poeeeri/Banking-Support)
NLP pipeline for banking support automation.

- Generated synthetic dialogues for dataset creation
- Trained an intent classifier based on **RuBERT**
- Tracked experiments with **ClearML**

**Stack:** `NLP` `RuBERT` `PyTorch` `ClearML`

---

### [DLS-course](https://github.com/poeeeri/DLS-course)
A collection of notebooks and experiments on ML, NLP, and CV.

- Implemented model architectures
- Fine-tuned classifiers
- Explored training pipelines and evaluation approaches

**Stack:** `PyTorch` `NLP` `CV` `Research`

---

### [Reverse-Gantt](https://github.com/poeeeri/Reverse-Gantt)
Reverse Gantt chart system for team project progress tracking.

- Mainly worked on backend development
- Participated in building a practical team product

## What I’m interested in

Right now, I’m especially interested in:

- NLP systems and text understanding
- Retrieval, reranking, and semantic search
- LLM-based applications
- Practical ML engineering
- End-to-end pet projects with real deployment

Although **NLP** is my main priority, I also enjoy working with **CV** and **DevOps-related** tasks when they help bring a project to production.

## Contact

- GitHub: [@poeeeri](https://github.com/poeeeri)
- Telegram: [@acchhe](https://t.me/sashxdlolkek)
- Email: [g2007gle@mail.ru](mailto:g2007gle@mail.ru)
- VK: [achooch](https://vk.ru/achooch)

---

⭐ I like building projects that combine machine learning with real user scenarios — especially when an idea can be taken from experimentation to a working product.
