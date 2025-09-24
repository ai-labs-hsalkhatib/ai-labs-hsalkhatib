# Hassan S. Al-Khatib — AI & ML Portfolio

PhD in Computational Engineering • People Analytics & Healthcare AI

This public repository hosts a curated portfolio of end-to-end machine learning and analytics projects. Each project lives in its own subfolder with documentation, code, data samples (or data loaders), and reproducible environments.

---

## 🗂️ Table of Contents
- [About](#about)
- [Repository Structure](#repository-structure)
- [Featured Projects (in progress)](#featured-projects-in-progress)
- [Technical Focus](#technical-focus)
- [How to Explore](#how-to-explore)
- [Reproducibility & Standards](#reproducibility--standards)
- [Research & Writing](#research--writing)
- [Contact](#contact)

---

## ℹ️ About

I build practical AI systems for two domains:
1. **Workforce/People Analytics:** forecasting demand/supply and cost, retention risk, organizational network analysis, and decision support.
2. **Healthcare AI:** patient-journey modeling, knowledge graphs, similarity search, and outcomes analytics.

My work emphasizes statistical rigor, interpretability, and reproducibility.

---

## 📂 Repository Structure

```text
ai-ml-portfolio/
├─ projects/
│  ├─ workforce-forecasting/        # Time series & causal forecasting for demand/cost
│  ├─ ona-network-analytics/        # Organizational Network Analysis (graph metrics & viz)
│  ├─ patient-journey-modeling/     # Sequence models & pathway analytics
│  ├─ healthcare-kg-similarity/     # Knowledge-graph construction & similarity search
│  └─ ...                           # Additional projects added over time
├─ templates/                        # Cookie-cutter project scaffolds, notebook templates
├─ docs/                             # Shared docs, design notes, and methodology overviews
└─ README.md                         # This landing page

```
---
## 🏗️ Featured Projects (in progress)

### Workforce Demand & Cost Forecasting
Multivariate time series forecasting with hierarchical rollups; backtesting, confidence intervals, and scenario analysis.

### Organizational Network Analysis (ONA)
Graph construction from survey/communication data; centrality, communities, cross-region flows; interactive visualizations.

### Patient Journey Modeling
Sequence labeling and temporal similarity for clinical pathways; evaluation against guideline-aligned outcomes.

### Healthcare Knowledge Graphs & Similarity
Ontology-driven KG, entity/relation extraction, graph embeddings, and patient similarity for cohort discovery.

> As projects finalize, this section will link directly to subfolders with full documentation and results.

---

## 🎯 Technical Focus

- **Modeling:** classical ML, time series (ETS/ARIMA/Prophet), gradient boosting, sequence models, graph analytics  
- **Causality & Evaluation:** A/B design, uplift, causal diagrams, sensitivity analysis, robust validation  
- **Graphs & KGs:** Neo4j/NetworkX, entity/relation extraction, similarity search, path analytics  
- **MLOps & Reproducibility:** environment pinning, data versioning, experiment tracking, CI-friendly structure  
- **Explainability & Ethics:** interpretable models, documentation of assumptions, bias/impact assessments

---

## 🔍 How to Explore

1. Browse the `projects/` directory and open a project’s `README.md` for scope and results.  
2. Create the environment specified by `environment.yml` or `pyproject.toml`.  
3. Run notebooks in order (prefixed numerically) or use `src/` entry points as documented.  
4. Check `reports/` for figures, metrics, and executive summaries.

> **Note:** Real production data is not included. Where appropriate, synthetic data or loaders are provided.

---

## 📋 Reproducibility & Standards

- **Environments:** pinned dependencies via `conda` (`environment.yml`) or `uv/poetry` (`pyproject.toml`).  
- **Structure:** consistent, modular Python package layout per project.  
- **Testing:** lightweight unit tests for core utilities where applicable.  
- **Docs:** each project documents assumptions, metrics, and limitations.  
- **Licensing/Data:** code is open under the repository license; datasets respect original terms or are synthetic.

---

## ✍🏻 Research & Writing

Selected work may be distilled into:
- Method notes and implementation guides in `docs/`  
- Short tutorials and case studies within project `README.md`  
- Drafts of articles or slide decks summarizing findings and impact

---

## 🤝 Connect with Me
- 📄 [LinkedIn](https://linkedin.com/in/hassan-saadeddine-al-khatib)
- 🔬 [Google Scholar](https://scholar.google.com/citations?user=4gpOIugAAAAJ&hl=en)
- 📬 Email: alkhatib.hassan@outlook.com
- 🌐 Portfolio site coming soon...
