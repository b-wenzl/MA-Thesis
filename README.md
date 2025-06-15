# Dutch Algorithm Register: Thesis Dataset & Analysis

This repository contains the dataset, analysis code, and notebooks used in my Master's thesis:

**Algorithmic Transparency and Open Government: Evaluating Public-Sector Algorithm Disclosures in the Dutch Algorithm Register (University of Amsterdam, 2025).**

---

## Project Overview

This research analyzes the Dutch Algorithm Register to evaluate the degree of transparency provided in public-sector algorithm disclosures. Using a combination of manual coding, automated GPT-4 scoring, and statistical analysis, the project assesses whether such registers enable meaningful public scrutiny or risk producing symbolic transparency.

The work combines:

- Dataset preparation & preprocessing
- Manual qualitative analysis
- Automated GPT-4 based transparency scoring
- Statistical validation and visualizations

---

## Repository Structure

- `notebooks/` — Jupyter (Colab) notebooks used for data preparation, GPT analysis, qualitative coding, and validation
- `data/raw/` — Raw dataset files extracted from the Dutch Algorithm Register
- `data/processed/` — Processed datasets used for scoring and analysis (GPT scoring files, filtered subsets, etc.)

---

## Datasets

The main dataset is derived from the **Dutch Algorithm Register** ([algoritmes.overheid.nl](https://algoritmes.overheid.nl/)).

| File | Description |
|------|-------------|
| `MA_Dataset Full.csv` | Complete dataset extracted from the register |
| `sampled_50_unique_filtered.csv` | Filtered sample used for manual analysis and additional GPT-4 results validation |
| `gpt4_full_transparency_scoring.csv` | Full GPT-4 coded transparency scores |
| `gpt4_transparency_scoring_sample.csv` | GPT-4 scoring of the sample subset used for manual review to prevent GPT hallucinations |

*Note: Sensitive or non-public data has been excluded. The dataset only includes public information.*

---

## Methods

The analysis combined:

- Data collection and cleaning (Python)
- Manual scoring of transparency dimensions (goals, logic, limitations)
- GPT-4 assisted coding using OpenAI API
- Statistical validation of AI-generated scores
- Thematic qualitative analysis

---

## Running the Notebooks

All notebooks are compatible with **Google Colab**.  
Click below to open directly:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/MA-Thesis/)


---

## Requirements

Main packages used:

- pandas
- numpy
- matplotlib
- seaborn
- openai
- scikit-learn


