# 🦸 Marvel Characters — Stats Analysis using Python

An exploratory data analysis of Marvel superhero and villain character stats, comparing attributes like Speed, Power, Intelligence, and Combat across **good** and **bad** aligned characters.

---

## 📌 Project Overview

This project analyzes the Marvel character statistics dataset (`charcters_stats.csv`) to uncover which heroes and villains are the most powerful, fastest, and most intelligent in the Marvel universe. Characters are split by alignment — **good vs bad** — for a head-to-head comparison.

---

## 📂 Dataset

- **Source:** [Kaggle — Marvel Character Stats](https://www.kaggle.com/datasets/jonathanbesomi/superheroes-nlp-dataset)
- **File used:** `charcters_stats.csv`
- **Key columns:** `Name`, `Alignment`, `Speed`, `Power`, `Intelligence`, `Combat`, `Total`

---

## 🔍 Analysis Breakdown

### ⚖️ Alignment Distribution
- Count of **good**, **bad**, and **neutral** aligned characters

### 🦸 Good Characters Analysis
- Top 5 heroes ranked by **Speed**
- Top 5 heroes ranked by **Power**
- Heroes with **maximum Power score (100)**
- Top 5 heroes by **Total stats** — bar chart
- Distribution histogram of **Speed** across all good characters

### 🦹 Bad Characters Analysis
- Top 5 villains ranked by **Speed**
- Top 5 villains ranked by **Intelligence**
- Top 5 villains ranked by **Total stats**
- Distribution histogram of **Combat** across all bad characters

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3 | Core language |
| Pandas | Data loading & manipulation |
| Matplotlib | Bar charts & histograms |
| Google Colab | Development environment |

---

## 🚀 How to Run

### Option 1 — Open in Google Colab
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

*(Replace with your actual Colab notebook link)*

### Option 2 — Run Locally
```bash
git clone https://github.com/anshu1516/Marvel-Data-Analysis.git
cd Marvel-Data-Analysis

pip install pandas matplotlib

jupyter notebook Marvel_.ipynb
```

> **Note:** Download `charcters_stats.csv` from Kaggle and place it in the same directory before running.

---

## 💡 Key Insights

- A select group of heroes achieve a **perfect Power score of 100**
- Villains tend to score highly in **Combat** and **Intelligence**
- The **Total stats** distribution reveals a clear gap between top-tier and average characters

---

## 👤 Author

**Anshu** — [GitHub](https://github.com/anshu1516)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
