# Olist E-Commerce Logistics & Revenue Analytics

Strategic data analytics project analyzing 110,000+ orders from the Brazilian e-commerce platform Olist to identify logistics inefficiencies and revenue optimization opportunities.

## 📊 Project Overview

This analysis reveals that **shipping costs consume 20–35% of purchase value**, acting as a primary conversion barrier. The report provides three data-driven recommendations to drive **15–25% revenue growth** within 12 months.

**Dataset:** Olist Brazilian E-Commerce Public Dataset (2016–2018)  
**Sample Size:** 110,163 order items  
**Analysis Methods:** EDA, Correlation Analysis, Linear Regression, K-Means Clustering

---

## 🎯 Key Findings

| Finding | Impact |
|---------|--------|
| Median freight = 22% of purchase value | Exceeds industry best practice (15%) |
| Weight-freight correlation: r = 0.61 | Weight is dominant cost driver |
| Customer segmentation: 3 distinct clusters | Enables precision marketing |
| Free shipping threshold (>150 BRL) | 8–12% conversion lift potential |

---

## 📁 Repository Structure

```
olist-ecommerce-analytics/
├── README.md                    # This file
├── notebooks/
│   └── analysis.ipynb          # Complete reproducible analysis code
├── reports/
│   ├── Report.md               # Strategic analysis report (3 pages)
│   ├── FrequancyDistribution.png
│   └── CorrelationMatrix.png
├── data/
│   └── .gitignore              # Raw data not committed
└── requirements.txt            # Python dependencies
```

---

## 🔧 Setup Instructions

### Prerequisites
- Python 3.8+
- pip or conda

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/username/olist-ecommerce-analytics.git
   cd olist-ecommerce-analytics
   ```

2. **Create virtual environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Download dataset** (optional - notebook auto-downloads via kagglehub)
   - Download from [Kaggle: Olist Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
   - Place in `data/` folder

---

## 📈 Running the Analysis

```bash
# Jupyter notebook
jupyter notebook notebooks/analysis.ipynb

# Or VSCode
code notebooks/analysis.ipynb
```

The notebook contains:
- Data loading and preprocessing
- Exploratory data analysis (EDA)
- Statistical correlation analysis
- K-Means customer segmentation
- Regression modeling for freight prediction

---

## 📋 Dependencies

```
pandas==2.0.0
scikit-learn==1.3.0
matplotlib==3.7.0
seaborn==0.12.0
plotly==5.14.0
bokeh==3.2.0
kagglehub==0.1.0
numpy==1.24.0
```

Install all:
```bash
pip install -r requirements.txt
```

---

## 💡 Three Strategic Recommendations

### 1. Free Shipping Threshold Strategy
- **Impact:** High
- **Timeline:** 30–60 days
- **ROI:** 3–4 months
- **Expected Lift:** 8–12% conversion increase

### 2. Regional Fulfillment Hubs for Heavy Goods
- **Impact:** Medium-High
- **Timeline:** 90–180 days
- **ROI:** 6–12 months
- **Expected Lift:** 12–18% revenue uplift (heavy goods)

### 3. Precision Customer Segmentation
- **Impact:** Medium
- **Timeline:** 60–90 days
- **Difficulty:** Low
- **Expected Outcomes:** 3–5x email ROI, 8–12% churn reduction

Full details in [Report.md](reports/Report.md)

---

## 📊 Data Description

**Tables Analyzed:**
- **Orders**: Transaction timestamps, delivery milestones
- **Order Items**: Product-level pricing, freight costs
- **Customers**: Geographic distribution (27 states)
- **Products**: Weight, photo quantity, category

**Sample Size:** 110,163 order items (after removing 3% incomplete records)

---

## 📝 Report Contents

The [3-page strategic report](reports/Report.md) includes:

1. **Executive Summary** - Key findings and opportunity assessment
2. **Data Selection & Methodology** - Analytical approach and data quality
3. **Exploratory Analysis** - Summary statistics and distributions
4. **Statistical Analysis** - Correlation matrix and interpretation
5. **Strategic Recommendations** - Actionable interventions with ROI
6. **GitHub Repository Setup** - Project organization guidelines
7. **Conclusion** - Implementation roadmap (6–9 months)

---

## 🔍 Analysis Highlights

- **Data Quality:** No imputation; missing values removed to preserve integrity
- **Statistical Rigor:** Pearson correlations, K-Means clustering, Linear regression
- **Business Focus:** Every metric tied to revenue and conversion impact
- **Reproducibility:** Full code in Jupyter notebook with comments

---

## 📧 Contact & Attribution

**Author:** Data Analytics Team  
**Dataset Source:** [Olist Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) via Kaggle

---

## 📄 License

This project is provided for educational and analytical purposes. Dataset usage subject to Kaggle terms.

---

## 🚀 Next Steps

1. Review the [strategic report](reports/Report.md) (3 pages)
2. Run the [Jupyter notebook](notebooks/analysis.ipynb) to explore data
3. Implement recommendations in priority order (6–9 month timeline)
4. Monitor KPIs: conversion rate, AOV, customer churn, freight cost per order

**Expected Impact:** 15–25% gross revenue growth + improved customer lifetime value
