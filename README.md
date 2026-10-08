## Hi, I'm Said 👋

**Data Scientist & AI Engineer · Rabat, Morocco · English / Français / العربية**

I turn invoices, PDFs and scanned documents into clean, validated data, and I put the models that do it into production.

At **Orange Business** I took a vision-language model from prototype to production, building the data and quality-control pipelines that validated more than **1,000 real carrier invoice formats**. I defined the F1, precision, recall and latency benchmarks that gated each release, and served the models with FastAPI and Docker on an air-gapped network.

### What I build

- **Document data extraction.** Invoices, receipts, delivery notes and statements to a fixed schema, checked against business rules, with anything doubtful sent to a person.
- **Order and catalog matching.** Customer orders written in their own words, matched to your SKUs, checked for price, quantity and duplicates before they reach the ERP.
- **Private AI.** Open models (Qwen2.5-VL, Mistral) on Ollama or vLLM, on your own machine or server, when documents can't go to a cloud API.
- **The app around the model.** FastAPI services, review screens, and full-stack web apps (React, Next.js).
- **Arabic and French NLP.** Text cleaning and classification for Arabic, including Moroccan Darija.

### Featured projects

| Project | What it shows |
|---|---|
| [**private-invoice-ai**](https://github.com/SaidIbenariba/private-invoice-ai) | Invoices, scans and phone photos to validated data with a local vision-language model, 9 business checks, Excel export and a review screen. Held-out test: 24/24 invoices fully correct, 8/8 planted errors caught. |
| [**order-intake-ai**](https://github.com/SaidIbenariba/order-intake-ai) | Customer order emails, PDFs and phone photos to ERP-ready orders, every line matched to a catalog SKU (English and French), with a review screen that remembers each confirmation. Held-out test: 0 wrong automatic matches on 761 lines; 0 errors reached the ERP on 30 emails. |
| [**invoiceops**](https://github.com/SaidIbenariba/invoiceops) | Built in public: mapping heterogeneous supplier invoice columns to one schema (alias, fuzzy and multilingual-embedding stages), with ablations and bootstrap confidence intervals. |
| [**AraHateSpeech_Detection**](https://github.com/SaidIbenariba/AraHateSpeech_Detection_Twitter_Master2) | Hate-speech detection for Arabic tweets across dialects and Moroccan Darija: Arabic normalization pipeline, TF-IDF + Linear SVC baseline, transformer fine-tuning. Master's project. |

### Stack

**AI / ML** &nbsp; Python · PyTorch · TensorFlow · scikit-learn · Hugging Face · LangChain · FAISS · Sentence Transformers  
**LLM & documents** &nbsp; Qwen2.5-VL · Mistral 7B · Ollama · vLLM · IBM Docling · Label Studio  
**Data** &nbsp; Pandas · NumPy · PostgreSQL · pgvector · PySpark · Kafka · Power BI  
**Engineering** &nbsp; FastAPI · Flask · Docker · React · Next.js · Git

### Background

- **Intelligent Document Processing Engineer**, Orange Business Morocco · Mar 2026 - Aug 2026
- **Co-founder & full-stack developer**, [illico.ma](https://illico.ma) · home-services marketplace · 2026 - present
- **Master's in Data Science & Engineering**, Mohammed V University, Rabat · 2024 - 2026
- **Bachelor's in Computer Science**, Mohammed V University, Rabat · 2021 - 2024

### Work with me

Available for document-processing and applied-AI projects. Send me a few sample documents and I'll show you what can be extracted before we start.

[![Hire me on Upwork](https://img.shields.io/badge/Hire%20me%20on-Upwork-14a800?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~01940599324880c3de)
