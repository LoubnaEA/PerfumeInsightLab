# PerfumeInsightLab 

From raw fragrance data to olfactory insights.   
A complete end-to-end **EDA** project combining **data quality assurance**, **exploratory analysis** and **visual storytelling**.

---

## Overview  
**PerfumeInsightLab** explores perfume data to uncover how brands, notes, accords, creative trends have evolved over time.  
The project bridges **QA methodology** and **Data Analysis**, ensuring that each analytical step is based on clean, validated and reproducible data.  

## Objectives
- Clean and structure raw perfume datasets (validation, deduplication, normalization)  
- Explore relationships between key features (brands, accords, perfumers, gender, ratings, years)  
- Visualize trends, popularity, olfactory patterns  
- Generate insights on fragrance composition, creative evolution, consumer perception  
- Prepare data for SQL-based exploration and future ML extensions  

## Tech Stack
- **Python 3**
- **Pandas, NumPy** (data cleaning & manipulation)  
- **Matplotlib, Seaborn, Plotly, WordCloud** (visualisation)
- **Custom Python scripts**, **Pandas profiling** (data valisation & QA)
- **SQL** / **SSMS** (queries and database exploration) 
- **Jupyter Notebooks**, **Markdown reports** (documentation)

## Notebooks
| Notebook | Description |
|----------|-------------|
| **01 Data Overview**   | Data loading, structure validation, missing-value analysis and duplicate removal. Defines the core cleaned dataset (`fra_cleaned_v2.csv`) and documents data quality metrics. |
| **02 Thematic EDA**    | Categorical exploration by brand, perfumer, gender, country, olfactory accords. Highlights patterns in brand output, creative collaborations, main scent families. |
| **03 Quantitative EDA**| Visual and numerical analysis of ratings, popularity, temporal trends. Weighted metrics (`C`, `m`) applied to evaluate perfume performance and stability over decades. |
| **04 Storytelling & Insights** | Integrates all previous findings into a coherent narrative. Analyzes unisex trends, olfactory patterns, brand evolution to draw data-driven insights on market dynamics. |

## Structure
├─ 📁 data/       → Raw perfume datasets, processed (cleaned) data, optional external sources (complementary data for enrichment)    
├─ 📁 notebooks/  → Jupyter notebooks for data exploration, cleaning, visualization and insights generation  
├─ 📁 scripts/    → Python scripts for reusable EDA functions, preprocessing and chart generation  
├─ 📁 reports/    → Visual outputs, summary notes, figures generated from the analysis  
└─ README.md     

## Dataset  
[Fragrantica.com Fragrance Dataset on Kaggle](https://www.kaggle.com/datasets/olgagmiufana1/fragrantica-com-fragrance-dataset)

## Last Note 🌸
This project reflects a **QA-minded approach to Data Analysis**, insights are not only visually appealing, but also **validated, reproducible** and **trustworthy**.
