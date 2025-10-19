# Research Paper Clustering System for Topic Discovery and Literature Organization

## 📌 Overview
This project aims to automatically cluster research papers based on their topics and semantic similarity using traditional machine learning techniques. It provides an intelligent, lightweight system for organizing and exploring large collections of academic publications.

By leveraging text preprocessing, TF-IDF vectorization, and clustering algorithms (K-Means, Hierarchical, and DBSCAN), the system helps researchers and students quickly identify related works, uncover cross-domain connections, and streamline the literature review process.

## 📂 Dataset
- Source: 
    - [arXiv Academic Papers Dataset (Kaggle)](https://www.kaggle.com/datasets/Cornell-University/arxiv)
- Data Description:
    - Contains metadata such as paper title, abstracts, authors, categories, and publication dates.
    - Covers multiple research domains from physics, computer science, mathematics, and more.
- Custom Extensions:
    - Additional papers may be scraped from public such as arXiv Xplore, and PubMed.
- Challenges:
    - Unstructured text data
    - High dimensionality and vocabulary sparsity
    - Semantic overlap between topics

## 🔎 Methodology
1. Data Input
    - Users upload a folder containing PDFs or structured CSV/JSON files with paper metadata.
2. Preprocessing
    - Clean and normalize text (remove punctuation, stopwords, and special symbols).
    - Tokenization and lemmatization for uniform text representation.
    - Extract relevant fields (titles, abstracts, and keywords).
3. Feature Extraction
    - Apply TF-IDF and CountVectorizer for numerical representation.
    - Optionally apply Latent Semantic Analysis (LSA) for dimensionality reduction and latent topic detection.
4. Clustering Analysis
    - Algorithms Used:
        - K-Means – baseline clustering for general topic grouping.
        - Agglomerative (Hierarchical) Clustering – shows relationships among subtopics.
        - DBSCAN – identifies niche or outlier topics.
5. Visualization
    - Use PCA or t-SNE to visualize paper clusters in 2D/3D.
    - Generate word clouds and keyword frequency plots per cluster.
6. Evaluation
    - Metrics: Silhouette Score, Davies-Bouldin Index, and topic coherence checks.
7. Reporting
    - Summarize each cluster with top keywords and representative papers.
    - Export interpretable reports as CSV, JSON, or PDF.
8. Deployment
    - Deploy via Streamlit web app, allowing users to upload datasets, explore clusters, and download topic summaries.

## 🚀 Usage
1. Clone the repo:
   ```bash
   git clone https://github.com/AISaturdaysLagos/C9-team-armah.git
   cd C9-team-armah
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run Jupyter notebooks for EDA and modeling:
   ```bash
   jupyter notebook
   ```
4. Launch the Streamlit app:
   ```bash
   streamlit run app.py


## 🌐 Deployment
  - Hosted on Streamlit Community Cloud
  - Access the live app: [App Link]()

## 📊 Expected Outcomes
  - Topic clusters that group semantically related research papers
  - 
  - 


## 👥 Team Members
  - [Latifat Olabisi Idris]()
  - [Abdusshakur Olabisi]()
  - [Nunsi Shiaki]()

