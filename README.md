# 🗂️ Portfolio

Welcome! Here’s a sneak peek into the projects I’ve been most passionate about. This is a snapshot of my work and technical growth so far.

![SQL (PostgreSQL)](https://img.shields.io/badge/SQL-PostgreSQL-blue?style=flat-square) 
![NoSQL (MongoDB)](https://img.shields.io/badge/NoSQL-MongoDB-green?style=flat-square) 
![GraphDB (Neo4j)](https://img.shields.io/badge/Graph-Neo4j-008CC1?style=flat-square) 
![Stats (SPSS)](https://img.shields.io/badge/Stats-SPSS-red?style=flat-square) 
![ML (Clinical NLP)](https://img.shields.io/badge/ML-Clinical%20NLP-orange?style=flat-square)
---

### 📑 Table of Contents
* [🧠 AI & Machine Learning](#-ai--machine-learning)
* [🧑🏻‍🔧 Data Engineering & Analytics](#-data-engineering--analytics)
* [🗄️ Database Engineering](#️-database-engineering-sql--nosql)
* [🛠️ Technical Stack](#️-technical-stack)

### 🧠 AI & Machine Learning

| Project Link | Tools | Project Description | Publication
| :--- | :--- | :--- | :-- |
| **🫀 Master’s Thesis: Medical NER** | Hugging Face, mBERT, XLM-R, GreekBERT, Stanza, Pytorch, W&B | Developed a **semi-supervised framework** for low-resource Greek clinical text by concatenating document-level metadata into model inputs. Engineered the dataset from raw EHRs (.docx, .txt) into HF format and benchmarked tokenizers to integrate Stanza.| [Thesis](https://ikee.lib.auth.gr/record/359896/?ln=en) |
| **[🫀 ElCardioCC (NER) BioASQ 2025 Baseline](https://github.com/Eleonwra/elcardiocc-baseline-ner.git)** | Hugging Face, mBERT, Stanza, PyTorch, W&B, Streamlit | **Official Supervised NER Baseline**. Scaled thesis research into a production-ready model to streamline **clinical coding**.  Developed custom PyTorch logic for subword reconstruction and deployed an inference demo in Streamlit.| [Paper](https://ceur-ws.org/Vol-4038/paper_4.pdf)
| [💰 **Cost-Sensitive Loan Default Prediction**](https://github.com/Eleonwra/cost-sensitive-ml-for-loan-default-prediction.git) | Scikit-learn, Imbalanced-learn, NumPy, Matplotlib | Developed a comparative framework to mitigate asymmetric financial risk (1:5 cost ratio). Implemented **Hybrid Resampling**, **Cost-Weighting**, and **Bayes Risk Minimization** across 3 model families to optimize for lowest financial loss rather than global accuracy. ||

### 🧑🏻‍🔧 Data Engineering & Analytics

| Project Link | Tools | Project Description | Medium Link |
| :--- | :--- | :--- | :-- |
|**🌐 TripAdvisor Data Mining** (Team Project)|Python (Selenium, NLTK, Gensim)|Developed a scraping pipeline using Selenium to extract TripAdvisor reviews, bypassing dynamic web obstacles and cookie banners. Processed raw text using NLTK (Lemmatization & Stop-word removal) and applied Latent Dirichlet Allocation (LDA).|[Read](https://medium.com/@ioannisprokopiou/web-scraping-with-python-41a728506d90)|
|[**⌚ FitBit Streamlit app** (Team Project)](https://github.com/Eleonwra/fitbit-wellness-tracker.git)|Fitbit API, MongoDB, Streamlit, Plotly| Architected an end-to-end pipeline using OAuth 2.0 and MongoDB to store heart rate and activity metrics. Built an interactive Streamlit dashboard with Plotly to visualize daily health fluctuations and personalized fitness insights.|[Read](https://medium.com/@ioannisprokopiou/a-hands-on-guide-to-fitbit-api-mongodb-and-streamlit-553e8cdd6ccd)|
|**📊 Exploratory Research & Survey Analysis**|SPSS, Google Forms|Research Collaboration:: Engineered a digital questionnaire for data collection and performed end-to-end statistical analysis. Conducted Hypothesis Testing, Correlation Analysis, and descriptive statistics to validate research variables.||

### 🗄️ Database Engineering (SQL & NoSQL)

| Project Link | Tools | Project Description | Medium Link |
| :--- | :--- | :--- | :--- |
|[**🌍 Static Spatial RDBMS: Global Air Transport**](https://github.com/Eleonwra/airlines-sdbms.git)|PostgreSQL, PostGIS, Python, QGIS| **Relational Architecture:** Executed **the complete database lifecycle**, from conceptual **ER Diagramming** to physical implementation. Populated via a custom ETL pipeline and performed advanced analysis using **Window Functions, CTEs, and Spatial queries**.||
|[**🐦‍⬛ Graph DBMS: Twitter Network Analysis** (Team Project)](https://github.com/Eleonwra/twitter-network-analysis.git)|Neo4j, Cypher, Python, MongoDB|**Graph Architecture**. Architected a non-tabular schema to map social interactions (Users, Tweets, Hashtags). Implemented an ETL flow from **MongoDB to Neo4j** and applied **PageRank** and **Louvain** algorithms to detect influential users and hidden communities. | [Read](https://medium.com/@ioannisprokopiou/analysis-of-twitter-data-with-the-help-of-neo4j-graph-database-and-python-c844784baedb)

---

### 🛠️ Technical Stack

* **Languages**: Python (PyTorch, Scikit-learn, NLTK), SQL, Cypher, SPSS

* **Databases**: Relational: PostgreSQL (PostGIS) | Graph: Neo4j | Document: 

* **Statistical Analysis**: SPSS (Hypothesis Testing, Correlation, ANOVA)

* **MLOps & Experiment Tracking**: Hugging Face, Weights & Biases (W&B)

* **Deployment & UIData Extraction**: Streamlit, Selenium
