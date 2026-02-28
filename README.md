<h1 align="center">🛡️ Argus</h1>
<p align="center">
  <b>Structural Code Plagiarism Detection Engine</b><br/>
  Detecting logical similarity using Abstract Syntax Trees (AST)
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-blue.svg" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg" />
  <img src="https://img.shields.io/badge/Status-Active%20Development-orange" />
  <img src="https://img.shields.io/badge/Hackathon-OVERLOCK24-purple" />
</p>

---

## 🔎 Overview

Argus is an AST-powered structural plagiarism detection system designed to analyze the **logical architecture of code** rather than relying on superficial string or token matching.

Traditional plagiarism detectors can be bypassed by:
- Renaming variables  
- Changing formatting  
- Reordering functions  
- Adding cosmetic modifications  

Argus solves this by parsing submissions into **Abstract Syntax Trees (ASTs)** and comparing structural patterns to detect logically equivalent implementations.

---

## 🚀 Why Argus?

✔ Detects renamed identifiers  
✔ Ignores formatting tricks  
✔ Identifies reordered logic  
✔ Highlights structural equivalence  
✔ Visualizes similarity clusters  
✔ Scalable for batch submissions  

Argus compares **how code behaves structurally**, not how it looks textually.

---

## 🧠 How It Works


Code
↓
AST Parsing
↓
Identifier Normalization
↓
Structural Fingerprint Extraction
↓
Similarity Scoring
↓
Cluster & Diff Visualization


### Step-by-Step Pipeline

1. Parse submitted files into AST representations  
2. Normalize variable names and literals  
3. Extract structural fingerprints  
4. Compute similarity metrics (e.g., cosine similarity)  
5. Flag suspicious submission pairs  
6. Visualize similarity matrix and clusters  

---

## 📊 Core Features

- 🔍 AST-based structural comparison  
- 📈 Pairwise similarity matrix  
- 🕸 Interactive similarity cluster graph  
- ⚖ Confidence scoring for suspicious pairs  
- 📂 Batch submission upload  
- 🆚 Side-by-side structural diff viewer  

---

## 🏗 Tech Stack

### Backend
- Python  
- FastAPI  
- Built-in `ast` module  
- NumPy / Scikit-learn  
- NetworkX  

### Frontend
- React / HTML + JavaScript  
- Chart.js (heatmaps)  
- D3.js (graph visualization)  

---

## 🎯 Objective

Argus aims to enable fair, scalable, and accurate academic integrity enforcement by detecting plagiarism at the **logical structure level** instead of relying on surface-level similarity.

---

## 🛡 License

This project is licensed under the **MIT License**.  
Free to use, modify, and contribute.

---

## 👥 Built By

**Lala Warriors** 🚀  
Hackathon Project — OVERLOCK 24

This is:

Clean

Professional

Visually structured

Hackathon-level polished

GitHub-ready

If you want, next I can:

Make it even more premium with a banner design layout

Add contribution guidelines section

Add installation & usage commands

Or help you design the folder structure

Tell me what’s next. 🚀
