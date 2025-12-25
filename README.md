# DSCP Steam Market Analyzer

This project explores recent Steam game releases (2021–2025) using Python and basic visualization tooling.  
The focus is on price distributions, temporal release patterns, genre structure, and play modes.

The results are summarized in a GitHub Pages site:

👉 **EDA Overview:** https://nimtandox.github.io/DSCP-steam-market-analyzer/pages/

## Contents

- `src/steamAnalyzer.ipynb` – data cleaning and exploratory analysis
- `data/steam_data_2021_2025.csv` – curated dataset of Steam releases
- `img/` – exported plots used in the report website
- `pages/` – static HTML/CSS site for presenting the findings

## Quick Start (Local)

```bash
# Create and activate virtual environment (optional)
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

# Install common dependencies (adjust as needed)
pip install pandas matplotlib scikit-learn

# Open the notebook
jupyter notebook src/steamAnalyzer.ipynb
```

## GitHub Pages

GitHub Pages is configured to serve the repository root.  
The report lives under the `/pages/` subfolder, so the public URL is:

- `https://nimtandox.github.io/DSCP-steam-market-analyzer/pages/`
