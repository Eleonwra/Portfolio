# 🗂️ Portfolio

Case studies in database architecture, network analysis, and machine learning. Focusing on building clean foundations and solving technical data challenges.

![SQL (PostgreSQL)](https://img.shields.io/badge/SQL-PostgreSQL-blue?style=flat-square) ![](https://img.shields.io/badge/NoSQL-Neo4j%20|%20Mongo-green?style=flat-square) ![](https://img.shields.io/badge/ML-Clinical%20NLP-orange?style=flat-square)
---

### 📑 Table of Contents
* [🧠 AI & Machine Learning](#-ai--machine-learning)
* [📊 Data Analysis](#-data-analysis)
* [🗄️ Database Engineering](#️-database-engineering-sql--nosql)
* [🛠️ Technical Stack](#️-technical-stack)

### 🧠 AI & Machine Learning

| Project Link | Tools | Project Description | Publication
| :--- | :--- | :--- | :-- |
| **🫀 Master’s Thesis: Medical NER** | Hugging Face, mBERT, XLM-R, GreekBERT, Stanza, Pytorch, W&B | Developed a **semi-supervised framework** for low-resource Greek clinical text by concatenating document-level metadata into model inputs. Engineered the dataset from raw EHRs (.docx, .txt) into HF format and benchmarked tokenizers to integrate Stanza.| [Thesis](https://ikee.lib.auth.gr/record/359896/?ln=en) |
| **[🫀 ElCardioCC (NER) BioASQ 2025 Baseline](https://github.com/Eleonwra/elcardiocc-baseline-ner.git)** | Hugging Face, mBERT, Stanza, PyTorch, W&B, Streamlit | **Official Supervised NER Baseline**. Scaled thesis research into a production-ready model to streamline **clinical coding**.  Developed custom PyTorch logic for subword reconstruction and deployed an inference demo in Streamlit.| [Paper](https://ceur-ws.org/Vol-4038/paper_4.pdf)
| [💰 **Cost-Sensitive Loan Default Prediction**](https://github.com/Eleonwra/cost-sensitive-ml-for-loan-default-prediction.git) | Scikit-learn, Imbalanced-learn, NumPy, Matplotlib | Developed a comparative framework to mitigate asymmetric financial risk (1:5 cost ratio). Implemented **Hybrid Resampling**, **Cost-Weighting**, and **Bayes Risk Minimization** across 3 model families to optimize for lowest financial loss rather than global accuracy. ||

### 📊 Data Analysis

| Project Link | Tools | Project Description | Medium Link |
| :--- | :--- | :--- | :-- |
|**Web Scraping**|Python (Selenium, NLT)|Developed a scraping pipeline using Selenium to extract TripAdvisor reviews, bypassing dynamic web obstacles and cookie banners. Processed raw text using NLTK (Lemmatization & Stop-word removal) and applied Latent Dirichlet Allocation (LDA).|[Read](https://medium.com/@ioannisprokopiou/web-scraping-with-python-41a728506d90)|
|**FitBit Streamlit app**|Fitbit API,Time Series, Plotly, Streamlit|Architected a health data pipeline using Fitbit API and OAuth 2.0 to store heart rate and activity metrics in MongoDB. Built an interactive Streamlit dashboard with Plotly to visualize daily health fluncuations and personalized fitness insights.|[Read](https://medium.com/@ioannisprokopiou/a-hands-on-guide-to-fitbit-api-mongodb-and-streamlit-553e8cdd6ccd)|
|**SPSS projects**||||
|||||

### 🗄️ Database Engineering (SQL & NoSQL)
| Project Link | Tools | Project Description | Medium Link |
| :--- | :--- | :--- | :--- |
|[🌍 Static Spatial RDBMS: Global Air Transport](https://github.com/Eleonwra/airlines-sdbms.git)|PostgreSQL, PostGIS, Python, QGIS| **Relational Architecture:** Executed **the complete database lifecycle**, from conceptual **ER Diagramming** to physical implementation. Populated via a custom ETL pipeline and performed advanced analysis using **Window Functions, CTEs, and Spatial queries**.||
|[🐦‍⬛ Graph DBMS: Twitter Network Analysis](https://github.com/Eleonwra/twitter-network-analysis.git)|Neo4j, Cypher, Python, MongoDB|**Graph Architecture (Joint Development)**. Architected a non-tabular schema to map social interactions (Users, Tweets, Hashtags). Implemented an ETL flow from **MongoDB to Neo4j** and applied **PageRank** and **Louvain** algorithms to detect influential users and hidden communities. | [Read](https://medium.com/@ioannisprokopiou/analysis-of-twitter-data-with-the-help-of-neo4j-graph-database-and-python-c844784baedb)

---
### 🛠️ Technical Stack
* **Languages:** Python, SQL, Cypher
* **Databases:** Neo4j, PostgreSQL, MongoDB
