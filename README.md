# 🗂️ Portfolio

Welcome! Here’s a sneak peek into the projects I’ve been most passionate about. This is a snapshot of my work and technical growth so far.

### 📑 Table of Contents
* [🧠 AI & Machine Learning](#-ai--machine-learning)
* [🧑🏻‍🔧 Data Engineering & Analytics](#data-engineering)
* [🗄️ Database Engineering](#️-database-engineering-sql--nosql)
* [🛠️ Technical Stack](#️-technical-stack)

### 🧠 AI & Machine Learning

| Project Link | Tools | Project Description | Publication
| :--- | :--- | :--- | :-- |
| **🫀 Master’s Thesis: Medical NER** | Hugging Face, mBERT, XLM-R, GreekBERT, Stanza, Pytorch, W&B | Developed a **semi-supervised framework** for low-resource Greek clinical text by concatenating document-level metadata into model inputs. Engineered the dataset from raw EHRs (.docx, .txt) into HF format and benchmarked tokenizers to integrate Stanza.| [Thesis](https://ikee.lib.auth.gr/record/359896/?ln=en) |
| **[🫀 ElCardioCC (NER) BioASQ 2025 Baseline](https://github.com/Eleonwra/elcardiocc-baseline-ner.git)** | Hugging Face, mBERT, Stanza, PyTorch, W&B, Streamlit | **Official Supervised NER Baseline**. Scaled thesis research into a production-ready model to streamline **clinical coding**.  Developed custom PyTorch logic for subword reconstruction and deployed an inference demo in Streamlit.| [Paper](https://ceur-ws.org/Vol-4038/paper_4.pdf) & [Demo](https://huggingface.co/spaces/Stoikopoulou/elcardiocc_baseline_ner)
| [💰 **Cost-Sensitive Loan Default Prediction**](https://github.com/Eleonwra/cost-sensitive-ml-for-loan-default-prediction.git) | Scikit-learn, Imbalanced-learn, NumPy, Matplotlib | Developed a comparative framework to mitigate asymmetric financial risk (1:5 cost ratio). Implemented **Hybrid Resampling**, **Cost-Weighting**, and **Bayes Risk Minimization** across 3 model families to optimize for lowest financial loss rather than global accuracy. ||

### 🧑🏻‍🔧 Data Engineering & Analytics

| Project Link | Tools | Project Description | Report |
| :--- | :--- | :--- | :-- |
|**🌐 TripAdvisor Data Mining** (Team Project)|Python (Selenium, NLTK, Gensim)|Developed a scraping pipeline using Selenium to extract TripAdvisor reviews, bypassing dynamic web obstacles and cookie banners. Processed raw text using NLTK (Lemmatization & Stop-word removal) and applied Latent Dirichlet Allocation (LDA).|[Medium](https://medium.com/@ioannisprokopiou/web-scraping-with-python-41a728506d90)|
|[**⌚ FitBit Streamlit app** (Team Project)](https://github.com/Eleonwra/fitbit-wellness-tracker.git)|Fitbit API, MongoDB, Streamlit, Plotly| Architected an end-to-end pipeline using OAuth 2.0 and MongoDB to store heart rate and activity metrics. Built an interactive Streamlit dashboard with Plotly to visualize daily health fluctuations and personalized fitness insights.|[Medium](https://medium.com/@ioannisprokopiou/a-hands-on-guide-to-fitbit-api-mongodb-and-streamlit-553e8cdd6ccd)|
|[**🏥 Hospital Billing and Patient report**](https://github.com/Eleonwra/hospital-billing-and-patient-report.git)|Excel, Power BI, Teams/SharePoint|End-to-end cloud automation of 55,000+ patient records. Engineered a live-sync pipeline from SharePoint to Power BI with automated refreshes. Implemented a Star Schema and custom DAX to power dynamic, interactive dashboards, including KPIs, trend analysis, and monthly reports.||

|**📊 Statistical Research Support**|SPSS, Google Forms|Undergraduate Thesis Collaboration: Technical Lead for the research pipeline. Optimized and approved the digital questionnaire structure for data integrity, followed by full-scale Descriptive Analysis, **Correlation Studies**, and **Hypothesis Testing**.|🔒 Restricted Access|

<a name="data-engineering"></a>
### 🗄️ Database Engineering (SQL & NoSQL)

| Project Link | Tools | Project Description | Report |
| :--- | :--- | :--- | :--- |
|[**🌍 Static Spatial RDBMS: Global Air Transport**](https://github.com/Eleonwra/airlines-sdbms.git)|PostgreSQL, PostGIS, Python, QGIS| **Relational Architecture:** Executed **the complete database lifecycle**, from conceptual **ER Diagramming** to physical implementation. Populated via a custom ETL pipeline and performed advanced analysis using **Window Functions, CTEs, and Spatial queries**.||
|[**🐦‍⬛ Graph DBMS: Twitter Network Analysis** (Team Project)](https://github.com/Eleonwra/twitter-network-analysis.git)|Neo4j, Cypher, Python, MongoDB|**Graph Architecture**. Architected a non-tabular schema to map social interactions (Users, Tweets, Hashtags). Implemented an ETL flow from **MongoDB to Neo4j** and applied **PageRank** and **Louvain** algorithms to detect influential users and hidden communities. | [Medium](https://medium.com/@ioannisprokopiou/analysis-of-twitter-data-with-the-help-of-neo4j-graph-database-and-python-c844784baedb)

### 🏛️ Archive 
| Project Link | Tools | Project Description | Report |
| :--- | :--- | :--- | :--- |
|**🌱 The origin story**|R, nnet, e1071, DAAG| **The project that sparked my passion for ML**. Conducted an extensive study transitioning from descriptive statistics to machine learning. Applied a comparative study of machine learning algorithms to identify critical survival factors in a dataset of 26k+ accident records.| [Report in Greek](https://drive.google.com/drive/folders/1nq6HYgmBRGeSVvsSFTJMUBWLjJ_HS8wd?usp=drive_link)

### 🛠️ Technical Stack

| Category | Tools |
| :--- | :--- |
| **🧠 AI & Machine Learning** | `PyTorch` • `Hugging Face` • `Transformers` • `W&B` |
| **🐍 Python & Data Science** | `NumPy` • `Pandas` • `Scikit-learn` • `Matplotlib` • `OOP` |
| **🗄️ Databases** | `PostgreSQL` • `PostGIS` • `Neo4j` • `MongoDB`  |
| **📊 Stats & Research** | `R` • `Power Bi` • `SPSS` • `LaTeX`|
| **🌐 Deployment & Scraping** | `Streamlit` • `Selenium` • `Git/GitHub` |
