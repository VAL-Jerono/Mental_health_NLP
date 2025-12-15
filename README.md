# Mental Health NLP - Optimization Study 🧠

> NLP-based optimization approach to analyzing mental health research literature

**Languages**: Python (primary) | R (secondary) | **Team**: 7 members

---

## 🎯 Overview

This project applies **NLP techniques** to analyze 180+ mental health research PDFs to detect emotional patterns, identify themes, and optimize text classification/clustering approaches.

### Objectives
- Extract and preprocess text from academic PDFs
- Theme detection and topic modeling
- Network analysis of concept relationships
- Optimization of feature selection, clustering, and topic models

---

## 📊 Dataset

Located in `Mental Health Study/` — 180+ PDFs covering:
- **Populations**: Students, adolescents, health workers, athletes
- **Topics**: Depression, anxiety, COVID-19 impact, digital interventions, peer support

---

## 🛠️ Setup

```bash
# Python
python -m venv venv && source venv/bin/activate
pip install pandas numpy scikit-learn nltk spacy PyPDF2 pdfplumber networkx gensim

# R
install.packages(c("tidyverse", "tm", "quanteda", "pdftools", "igraph", "topicmodels"))
```

---

## 🌿 Branch Strategy

**Main branch** = verified, working code | **Personal branches** = individual exploration

```bash
# Create your branch
git checkout -b member-[your-name]

# Daily workflow
git checkout main && git pull origin main
git checkout member-[your-name] && git merge main
# ... work, commit, push
git push origin member-[your-name]
```

---


## 🚀 Getting Started

- [ ] Clone repo & create your branch
- [ ] Set up Python/R environment
- [ ] Explore PDFs in `Mental Health Study/`
- [ ] Review existing `.png` visualizations
- [ ] Document exploration in notebooks

---

## 📚 Resources

- [NLTK Book](https://www.nltk.org/book/) | [spaCy Docs](https://spacy.io/usage) | [Hugging Face](https://huggingface.co/course)
- [Text Mining with R](https://www.tidytextmining.com/) | [SciPy Optimize](https://docs.scipy.org/doc/scipy/reference/optimize.html)
