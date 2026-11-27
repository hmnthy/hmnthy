# Hi, I'm Thy HUYNH 👋

**Data Scientist · Machine Learning, NLP & Generative AI** · Paris area, France

![AWS Certified Machine Learning Engineer – Associate](https://img.shields.io/badge/AWS%20Certified-ML%20Engineer%20Associate-FF9900)
![Available immediately](https://img.shields.io/badge/Available-immediately-2ea44f)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-hmnthy-0A66C2)](https://www.linkedin.com/in/hmnthy)

---

## About me

I build AI products end to end, from research to production: raw data, models, and live applications that people can use and check. With a background in both marketing and data science, I start from the business decision a team needs to make, then build the data, the model and the tool that support it.

- 🔬 **NLP research, writing scientific papers (2026–present)**
  - Research member of a joint project between the Faculty of Information Technology of the University of Engineering and Technology (VNU-UET, Vietnam National University, Hanoi) and AI VIET NAM, an advanced AI research and training community.
  - Topic: parameter-efficient continual relation extraction. A model learns new relation types over time without forgetting the ones it learned before (catastrophic forgetting).
  - Co-author a scientific paper to be submitted to PAKDD 2027 (Pacific-Asia Conference on Knowledge Discovery and Data Mining) https://www.pakdd2027.org/
- 🧵 **Building [Unthreaded](https://unthreaded-analytics.vercel.app)**
  - NLP and statistical analytics on my own Threads channel.
  - A live RAG retrieval demo.
- 🏦 **Data Scientist apprentice at Groupe BPCE (2024–2025)**
  - Deactivation scoring models (XGBoost, LightGBM) for the Professionals market.
  - The selected model goes to production across the Caisse d'Épargne network in 2026.
- 📏 **Methods I can defend**
  - Every result comes with its sample size, effect size and uncertainty.

---

## Featured project: Unthreaded

Analytics for a Threads channel (~1M views/month, French and Vietnamese content), where the platform's algorithm is a black box.

- **Pipeline:** scheduled collection from the Threads API → multilingual embeddings → topics found with UMAP + HDBSCAN, labeled by an LLM (Claude API).
- **Statistics:** topics compared with a rank-based permutation test and Holm correction. The decision rule was fixed before the results were seen.
- **RAG demo (retrieval only):** BM25, dense and hybrid search, then cross-encoder or LLM reranking, on fixed questions whose answers were chosen in advance.
- **Engineering:** FastAPI · Next.js · Vercel · pytest and GitHub Actions CI on every pull request.

[Live app](https://unthreaded-analytics.vercel.app) · [RAG demo](https://unthreaded-analytics.vercel.app/rag-pipeline) · [Code](https://github.com/hmnthy/threads-ai-content)

---

## Selected projects and challenges

| Project | Result | What I did |
|---|---|---|
| [Malicious behavior detection](https://github.com/hmnthy/malware-detection-sdc) · Sorbonne Data Challenge 2025 | 🥉 3rd prize | Multi-label prediction of 453 behaviors for 23,000+ Windows programs from their control-flow graphs (100 GB). CodeBERT + TF-IDF/SVD + structural features, One-vs-Rest XGBoost, per-behavior thresholds tuned by Bayesian optimization, SHAP. |
| [Bank churn prediction](https://github.com/hmnthy/bank-churn-prediction-kaggle) · Kaggle 2025 | 🥇 1st place · ROC AUC 0.937 | 15,000 customers. Stack of six models on out-of-fold predictions, with an Optuna-tuned meta-model. |

---

## Tech stack

Each group separates what I have **used in projects and work** from what I was **trained in** through my master's coursework, research and certification.

### 🤖 Machine learning & statistics
- **Used:** XGBoost · LightGBM · CatBoost · Random Forest · logistic regression · scikit-learn · pandas · NumPy · Optuna · Hyperopt · stacking · cross-validation · penalized logistic regression · time series · hypothesis testing · permutation tests with multiple-testing correction (Holm) · A/B testing
- **Trained:** Bayesian statistics · econometrics · high-dimensional statistics

### 🧠 Deep learning, NLP & generative AI
- **Used:** Hugging Face · sentence embeddings · CodeBERT · TF-IDF · topic modeling (LDA) · UMAP · HDBSCAN · BM25 · dense and hybrid retrieval · cross-encoder reranking · RAG · Claude API · OpenAI API · transfer learning (ResNet18)
- **Trained:** PyTorch · TensorFlow / Keras · CNN · RNN / LSTM · Transformers and BERT fine-tuning · LoRA / PEFT · LangChain / LangGraph · MCP · FAISS · Chroma · Qdrant · Pinecone

### 🔍 Explainable & responsible AI
- **Used:** SHAP
- **Trained:** LIME · bias and fairness auditing

### 🏗️ Data engineering & cloud
- **Used:** SQL · Google BigQuery · MySQL · Dataiku DSS · SAS · ETL · web scraping (BeautifulSoup)
- **Trained:** Apache Spark / PySpark · Apache Airflow · Apache Kafka · Databricks · AWS (SageMaker · S3 · Glue · Athena · Lambda · Step Functions · Bedrock) · GCP Vertex AI

### 🚀 MLOps & deployment
- **Used:** FastAPI · Docker · Git / GitHub · GitHub Actions CI · pytest · uv · Vercel
- **Trained:** model and data drift monitoring

### 💻 Programming
- Python · SQL · R · SAS · VBA · M language (Power Query)

### 📊 BI & ways of working
- **Used:** Power BI · Excel (VBA, Power Query)
- **Trained:** Tableau · Looker · Scrum / Agile

---

## Certifications and education

- **AWS Certified Machine Learning Engineer – Associate** (2026) · Microsoft Azure AZ-900 (2025) · Dataiku ML Practitioner and Core Designer (2025)
- **Master 2 MOSEF Data Science**, Université Paris 1 Panthéon-Sorbonne (2025, Mention Bien) · Master 1 Statistical Engineering & Data Science, ISUP – Sorbonne Université

🗣️ French (fluent) · English (fluent, TOEIC 935/990) · Vietnamese (native)

---

## Contact

You can reach me on [LinkedIn](https://www.linkedin.com/in/hmnthy) or by email at [hmnthy@gmail.com](mailto:hmnthy@gmail.com).
