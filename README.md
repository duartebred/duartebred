<h1 align="center">Duarte Velho</h1>

<p align="center">
  <b>Data Science & Analytics · Machine Learning · MSc Bioinformatics</b><br>
  Turning biological and scientific data into models, pipelines and tools people can actually use.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/duartevelho1"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:duartealvesvelho@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Braga,%20Portugal-2F4F6F?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location">
  <img src="https://img.shields.io/badge/Open%20to%20work-2ea44f?style=for-the-badge" alt="Open to work">
</p>

---

- [About me](#about-me)
- [Tech stack](#tech-stack)
- [Selected projects](#selected-projects)
- [Background](#background)
- [What I'm looking for](#what-im-looking-for)
- [Contact](#contact)

---

## About me

I'm from Ponte de Lima and studied at the University of Minho, where an **MSc in Bioinformatics** was, in practice, a training in data: programming, machine learning, statistics and databases, applied to problems where the dataset is large, noisy and rarely behaves the way the textbook says.

What I enjoy is the full path from raw data to something usable — exploring and cleaning the data, choosing and validating a model, and then building the interface or pipeline that puts the result in someone's hands. Most of my work sits at the intersection of **data science and software engineering**: not just a notebook with an accuracy score, but code that is documented, tested and reproducible.

The project that taught me the most was extending **KEGGCharter**, a published open-source tool used by other researchers. Working inside someone else's codebase, on software people depend on, forces a discipline that writing from scratch never does.

---

## Tech stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Data & ML**  
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Bioconductor](https://img.shields.io/badge/Bioconductor-1F6FEB?style=flat-square)
![Biopython](https://img.shields.io/badge/Biopython-3776AB?style=flat-square&logo=python&logoColor=white)

**Databases**  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-018BFF?style=flat-square&logo=neo4j&logoColor=white)

**Tooling**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

---

## Selected projects

### 🧬 [KEGGCharter — interactive metabolic map visualisation](https://github.com/duartebred/KEGGCharter)
`Python` · `Biopython` · `data visualisation` · `open source`

KEGGCharter is a published open-source tool that maps genomic and transcriptomic data onto KEGG metabolic pathways. Its output was static images: accurate, but impossible to explore — taxonomy and gene expression were drawn as separate layers, so you could not read microbial identity and expression in a single view.

I extended the tool with an **interactive charting interface**, adding multi-level taxonomic representation, on-click access to the underlying numeric values, and cross-references to external databases. Developed as an MSc project in collaboration with the **Centre of Biological Engineering (CEB, University of Minho)**, under the guidance of the tool's author.

→ Project write-up: [Mapping Omics datasets on KEGG Metabolic Pathways](https://github.com/duartebred/Mapping-Omics-datasets-on-KEGG-Metabolic-Pathways)

---

### 💊 [Drug response prediction — GDSC1](https://github.com/duartebred/ML-data-analysis)
`Python` · `scikit-learn` · `clustering` · `dimensionality reduction`

End-to-end machine learning analysis on the GDSC1 dataset (IC50 responses for 208 drugs across ~1000 cancer cell lines). Exploratory analysis, feature engineering and missing-value treatment, followed by unsupervised learning (dimensionality reduction and clustering) and supervised models predicting drug response from a gene-expression profile and a compound's SMILES representation.

---

### 🔬 [RNA-Seq analysis — uterine corpus endometrial carcinoma](https://github.com/duartebred/Analise-RNASeq-Cancro-Utero)
`R` · `Bioconductor` · `differential expression` · `machine learning`

Analysis of gene expression data from the GDC Data Portal: preprocessing, descriptive statistics and visualisation, univariate analysis and differential expression, then clustering, dimensionality reduction, predictive modelling with model comparison, and gene selection by importance. Reports generated with R Markdown.

---

### 🧠 [Machine learning algorithms from scratch](https://github.com/duartebred/si)
`Python` · `NumPy` · `pandas` · `algorithm implementation`

Implementation of core machine learning algorithms from first principles using only NumPy and pandas, following a common scikit-learn-style API. Built to understand what happens under `.fit()` rather than to call it.

---

### 🗄️ [Relational → NoSQL migration](https://github.com/duartebred/NOSQL-DATABASES)
`MySQL` · `MongoDB` · `Neo4j` · `data modelling`

Migration of a hospital management relational database into two non-relational paradigms — document-oriented (MongoDB) and graph-based (Neo4j) — including schema redesign for each paradigm, query implementation and a critical comparison of performance and modelling trade-offs against the original relational system.

---

### ⚙️ [Advanced algorithms for bioinformatics](https://github.com/duartebred/Algoritmos-Avancados-Bioinformatica)
`Python` · `unit testing` · `type hinting` · `documentation`

Original implementations of motif discovery (Gibbs sampling), evolutionary computation, pattern matching (finite automata, tries, suffix trees), Burrows-Wheeler alignment, graphs and biological networks. The repository is deliberately written as production-style code: documented, type-hinted and covered by unit tests.

---

<details>
<summary><b>More repositories</b></summary>

- [**Flux Balance Analysis**](https://github.com/duartebred/fba-Flux-Balance-Analysis) — constraint-based metabolic modelling of *Chlamydomonas reinhardtii* with COBRApy and MEWpy, predicting metabolic flux under different environmental and genetic conditions.
- [**Linear regression in R**](https://github.com/duartebred/Regressao-Linear-em-R) — statistical modelling and diagnostics.
- [**Bioinformatics laboratories**](https://github.com/duartebred/Laboratorios-de-Bioinformatica-G2-MBI2023-24) — systematic gene analysis pipelines with Biopython.
- [**Web scraping + MySQL**](https://github.com/duartebred/Web_Scraping-MBI2023-24) — data collection and database population in Python.
- [**Databases**](https://github.com/duartebred/Bases-de-Dados) and [**NoSQL exercises**](https://github.com/duartebred/exercises-NoSQLDataBases) — SQL and NoSQL practice.

</details>

---

## Background

**MSc in Bioinformatics** — University of Minho, School of Engineering · 2023–2026  
Programming, machine learning, statistics, databases and systems biology.  
Dissertation: metabolic prediction in the gut microbiome using rule-based pipelines (RetroRules), supervised by Prof. Miguel Rocha.

**BSc in Applied Biology** — University of Minho, School of Sciences · 2020–2023  
Final project at CBMA: microplastic contamination in water bodies using an artificial intelligence approach — data processing and analysis in Python, with statistical analysis in GraphPad Prism and IBM SPSS.

Also: elected course representative for the MSc cohort (2023–2025) and part of the organising committee of the Bioinformatics Open Days for two editions.

---

## What I'm looking for

A first professional role working with data — **data analytics, data science, data engineering or machine learning engineering**.

📍 Porto · Braga · Aveiro · Guimarães · Lisboa, or remote within Europe  
🗓️ Available immediately

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/duartevelho1)
[![Email](https://img.shields.io/badge/duartealvesvelho@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:duartealvesvelho@gmail.com)

---

<div align="center">
  <img height="150" src="./assets/stats.svg" alt="GitHub stats">
  <img height="150" src="./assets/top-langs.svg" alt="Top languages">
</div>
