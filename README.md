![GitHub stats](https://github-readme-stats.vercel.app/api?username=SaidIbenariba&show_icons=true&theme=default&hide=issues)

## Hi, I'm Said 👋

**AI Developer & Engineer · Data Scientist · Rabat, Morocco · English / Français / العربية**

I build AI automation and LLM apps that take repetitive work off your team: reading documents and emails, moving data between systems, checking numbers. Every system is measured before you rely on it, anything uncertain goes to a person, and it can run privately on your own servers.

At **Orange Business** I took a vision-language model from prototype to production, building the data and quality-control pipelines that validated more than **1,000 real carrier invoice formats**. I defined the F1, precision, recall and latency benchmarks that gated each release, and served the models with FastAPI and Docker on an air-gapped network.

### What I build

- **AI agents and automation.** Agents that call your systems through tools, and workflows that turn emails, PDFs, forms and messages into structured data in Google Sheets, Excel, a database or your system's API. Python and FastAPI, n8n or MCP, with OpenAI, Claude or private open models, and checks in code plus a review step for anything uncertain.
- **Document AI.** Invoices, purchase orders, delivery notes, receipts and contracts: fields extracted with vision-language models, checked against business rules, and matched to your own records, such as your product catalog or purchase orders.
- **Document Q&A (RAG).** Ask a question about a contract or a manual and get the answer with the exact passage and its page, or "Not found" when the document doesn't say it.
- **Machine learning and data science.** Classification and NLP in English, French and Arabic (including Moroccan Darija), evaluated with precision, recall and latency. Data pipelines and Power BI dashboards for the numbers that come out.
- **Private AI.** Open models (Qwen2.5-VL, Mistral) on Ollama or vLLM, on your own machine or server, when data can't go to a cloud API.
- **The app around it.** FastAPI services, review screens, and full-stack web apps (React, Next.js, Node.js).

### Featured projects

| Project | What it shows |
|---|---|
| [**invoice-agent-ai**](https://github.com/SaidIbenariba/invoice-agent-ai) | An AI agent checks supplier invoices against the purchase order and the goods receipt before payment: 12 tools, the 3-way match in code, and a guard that re-checks everything before an invoice is approved. Local models, run from an n8n workflow or over MCP. Held-out synthetic test: 24/24 decisions right, 0 wrong payments. |
| [**order-intake-ai**](https://github.com/SaidIbenariba/order-intake-ai) | Customer order emails, PDFs and phone photos to ERP-ready orders, every line matched to a catalog SKU (English and French), with a review screen that remembers each confirmation. Held-out test: 0 wrong automatic matches on 761 lines; 0 errors reached the ERP on 30 emails. |
| [**private-invoice-ai**](https://github.com/SaidIbenariba/private-invoice-ai) | Invoices, scans and phone photos to validated data with a local vision-language model, 9 business checks, Excel export and a review screen. Held-out test: 24/24 invoices fully correct, 8/8 planted errors caught. |
| [**contract-qa-ai**](https://github.com/SaidIbenariba/contract-qa-ai) | Questions about a contract answered with the exact quote and its page, or "Not found", on a local model. Held-out test on public contracts: right 90.9% of the time when it answers, right page 58/58, no invented quotes, and "Not found" 94.9% of the time when the contract doesn't say it. |
| [**invoiceops**](https://github.com/SaidIbenariba/invoiceops) | Built in public: mapping heterogeneous supplier invoice columns to one schema (alias, fuzzy and multilingual-embedding stages), with ablations and bootstrap confidence intervals. |
| [**AraHateSpeech_Detection**](https://github.com/SaidIbenariba/AraHateSpeech_Detection_Twitter_Master2) | Hate-speech detection for Arabic tweets across dialects and Moroccan Darija: Arabic normalization pipeline, TF-IDF + Linear SVC baseline, transformer fine-tuning. Master's project. |

### Stack

**AI / ML** &nbsp; Python · PyTorch · TensorFlow · scikit-learn · Hugging Face · LangChain · FAISS · Sentence Transformers  
**LLM, agents & documents** &nbsp; Qwen2.5-VL · Mistral 7B · Ollama · vLLM · OpenAI · Anthropic · OpenRouter · n8n · MCP · IBM Docling · Label Studio  
**Data** &nbsp; Pandas · NumPy · PostgreSQL · pgvector · PySpark · Kafka · Power BI  
**Engineering** &nbsp; FastAPI · Flask · Docker · React · Next.js · Node.js · Git

### Background

- **Intelligent Document Processing Engineer**, Orange Business Morocco · Mar 2026 - Aug 2026
- **Co-founder & full-stack developer**, [illico.ma](https://illico.ma) · home-services marketplace · 2026 - present
- **Master's in Data Science & Engineering**, Mohammed V University, Rabat · 2024 - 2026
- **Bachelor's in Computer Science**, Mohammed V University, Rabat · 2021 - 2024

### Work with me

Available for AI automation, agent and document-processing projects. Tell me which task eats your team's time and send me a few real examples; I'll tell you what can be automated and how I'd measure it.

[![Hire me on Upwork](https://img.shields.io/badge/Hire%20me%20on-Upwork-14a800?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~01940599324880c3de)
