# Shipping ML & NLP Analysis

## Quick Access to Reports

- [1. EDA Report (PDF)](reports_for_results/1_EDA_report.pdf)
- [2. ML Modeling Report (PDF)](reports_for_results/2_ML_Modeling_report.pdf)
- [3. NLP Processing Report (PDF)](reports_for_results/3_NLP_Processing_report.pdf)

---

## Project Overview

This project contains three main analysis tasks:

1. **Exploratory Data Analysis (EDA)** - Dataset exploration and visualization
2. **ML Modeling** - On-time delivery prediction using classification models
3. **NLP Processing** - Product title matching and duplicate detection

---

## Requirements

- Python 3.12
- Dependencies listed in [requirements.txt](requirements.txt)

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Project Structure

```text
├── data/                          # Raw datasets
│   ├── ecommerce_shipping_data.csv
│   ├── product_titles.csv
│   └── transactions.csv
├── reports_for_results/           # Final analysis reports (PDF & DOCX)
│   ├── 1_EDA_report.pdf
│   ├── 2_ML_Modeling_report.pdf
│   └── 3_NLP_Processing_report.pdf
├── visualizations/                # Generated charts and graphs
│   ├── 1_EDA_images/
│   ├── 2_ML_Modeling_images/
│   └── 3_NLP_Process_images/
├── 1_EDA.ipynb                    # Notebook for EDA analysis
├── 2_ML_Modeling.ipynb            # Notebook for ML modeling
└── 3_NLP_Process.ipynb            # Notebook for NLP processing
```

---

## Analysis Notebooks

### 1. EDA Analysis

- Dataset inspection and quality assessment
- Distribution analysis and visualization
- Feature relationships exploration
- See [1_EDA.ipynb](1_EDA.ipynb)

### 2. ML Modeling

- On-time delivery prediction
- Model comparison and evaluation
- Feature importance analysis
- See [2_ML_Modeling.ipynb](2_ML_Modeling.ipynb)

### 3. NLP Processing

- Product title cleaning and preprocessing
- Duplicate detection using similarity metrics
- Product matching and grouping
- See [3_NLP_Process.ipynb](3_NLP_Process.ipynb)

---

## License

See [LICENSE](LICENSE)
