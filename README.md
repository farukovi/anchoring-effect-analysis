# Anchoring Effect Analysis

This project investigates the **anchoring effect**, a cognitive bias where people rely heavily on initial numerical values (anchors) when making estimates. Using replicated data from Chandler (2015), based on Janiszewski and Uy (2008), we analyze how **anchor precision** and **motivation to underestimate** affect estimation behavior.

## 📊 Dataset

- **Source**: Chandler (2015) replication study
- **Structure**: Participants estimated values for 9 items (e.g., price, weight) under one of four experimental conditions:
  - Low vs. high anchor precision
  - Weak vs. strong motivational phrasing

## 🧪 Methods

- Relative difference from anchor was calculated per item and averaged per participant
- A **Two-Way ANOVA** tested main and interaction effects of anchor precision and motivation
- **Shapiro-Wilk** and **Levene’s Test** checked model assumptions
- **Tukey's HSD** explored pairwise differences across 4 conditions

## 📈 Key Findings

- High precision anchors led to estimates closer to the anchor
- Strong motivation led to larger underestimation
- No significant interaction effect was found

## 🛠 Tools Used

- Python
- pandas, seaborn, statsmodels, scipy, matplotlib

## 📂 Folder Structure

├── Chandler.csv # Dataset
├── analysis.ipynb # Main analysis notebook
├── results/ # Summary tables and ANOVA results
└── README.md # This file
