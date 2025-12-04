[![Python CI](https://github.com/shreyapatil9480/job-transition-analytics-project/actions/workflows/python-ci.yml/badge.svg)](https://github.com/shreyapatil9480/job-transition-analytics-project/actions/workflows/python-ci.yml)
![Python](https://img.shields.io/badge/python-3.11-blue)
![pytest](https://img.shields.io/badge/tested%20with-pytest-0A9EDC)

# Job Transition Analytics Project

What basket characteristics predict high margin?

**Stakeholder:** Retail Analytics Manager

## Key Insights

- Promo baskets under 3 items rarely achieve high margin.
- Large-format stores show 14% higher high-margin conversion.
- Basket size above 8 items lifts margin odds even without promos.

## Dataset

Primary file: `data/retail_baskets.csv`  
Target variable: `high_margin`

## Getting Started

```bash
pip install -r requirements.txt
jupyter notebook notebooks/exploratory_analysis.ipynb
```



## Testing

```bash
pip install -r requirements.txt
pytest tests/ --cov=src
```

## Next Steps

Automate SQL exports into a weekly stakeholder report.

---
*Analytics portfolio project — 2025-08*

<!-- build 5 -->

### Implemented

```bash
pip install -r requirements.txt
python scripts/weekly_report.py
```
