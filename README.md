# Global Mental Health Network Analysis 🧠

> **Computational Topology of Mental Health Narratives**: A Multi-Dimensional Framework for Analyzing Symptom Flow, Structural Cores, and Psycholinguistic Focus.

This project goes beyond simple keyword counting. We transform unstructured mental health research into a **structured knowledge graph**, allowing us to map the complex "flow" of symptoms and identify the dense cores of various mental health disorders.

---

## 🛠 The Stack

*   **Language**: ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
*   **NLP**: ![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white) ![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
*   **Graph Theory**: ![NetworkX](https://img.shields.io/badge/NetworkX-000000?style=for-the-badge)
*   **Data Ops**: ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
*   **Visualization**: ![Seaborn](https://img.shields.io/badge/Seaborn-444444?style=for-the-badge) ![Matplotlib](https://img.shields.io/badge/Matplotlib-ffffff?style=for-the-badge&logo=matplotlib&logoColor=black)

---

## 📖 The Story: From Text to Topology

### The Problem
Most mental health text analysis treats words as isolated units ("Bag-of-Words"). This misses the **direction** (does stress lead to insomnia or vice-versa?) and the **structure** of how symptoms cluster together.

### The Solution: Graphs & Math
We model the literature as a **Directed Weighted Graph** $G = (V, E, W)$:
- **Nodes ($V$):** Concepts like *Anxiety*, *Depression*, or *Trauma*.
- **Edges ($E$):** The narrative flow—how often one symptom transitions into another.
- **Weights ($W$):** The strength of these relationships based on frequency and TF-IDF relevance.

---

## 🚀 Research Highlights

1.  **Symptom Flow**: Identifying "Source" symptoms (triggers) vs. "Sink" outcomes using **PageRank**.
2.  **The Diamond Core**: Using **Maximum Clique Detection** to find the most inseparable, dense clusters of symptoms.
3.  **Thematic Universes**: Breaking down the global network into **Communities** (using Louvain Modularity) to see local symptom "ecosystems."
4.  **Self-Focus**: Measuring internal vs. external focus using the **Self-Attentional Ratio**.

---

## ⚡ Quick Start (Simplified)

Follow these 3 steps to get the project running locally:

### 1. Clone & Enter
```bash
git clone https://github.com/VAL-Jerono/Mental_health_NLP.git
cd Mental_health_NLP
```

### 2. Setup Environment
```bash
python -m venv venv && source venv/bin/activate  # macOS/Linux
# OR: venv\Scripts\activate                     # Windows
```

### 3. Install Everything
```bash
pip install -r requirements.txt || pip install pandas numpy scikit-learn nltk spacy networkx community matplotlib seaborn PyPDF2 pycountry
python -m spacy download en_core_web_sm
```

---

## 📂 Dataset & Team

**Source Data**: `Mental Health Study/` folder containing 180+ localized research PDFs covering students, athletes, and pandemic-era mental health.

### 👥 The Team
- **Assumpta Mwikali** (134022)
- **Olive Mideva Muloma** (135792)
- **Rutendo Julia Kandeya** (168332)
- **Trevor Anjeyo Vuhyah** (224038)
- **Valerie Jerono** (222331)

---
