# 🌍 Africa Fiscal Sustainability Analysis

**Data-driven framework for assessing fiscal health in African economies using machine learning and predictive analytics**

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

---

## 📋 Overview

This project develops an integrated analytical framework to assess fiscal sustainability across African economies, addressing critical challenges of persistent deficits, accelerating debt, and revenue volatility.

**Key Features:**
- Multi-country fiscal data analysis (40+ African nations)
- Anomaly detection using Z-score and Isolation Forest
- Composite risk scoring framework
- Time series forecasting with scenario analysis
- Policy recommendations aligned with SDGs

---

## 🎯 Problem Statement

African economies face structural fiscal challenges:
- **Persistent deficits** exceeding -3% of GDP
- **Accelerating debt** surpassing sustainability thresholds
- **Revenue volatility** 3-5x higher in commodity-dependent economies

Traditional analysis lacks predictive capability for proactive intervention.

---

## 🔬 Methodology

### Data Sources
- World Bank Open Data
- IMF World Economic Outlook
- African Development Bank

### Key Indicators
- Fiscal Balance Ratio = (Revenue - Expenditure) / GDP
- Debt-to-GDP Ratio
- Revenue Volatility (5-year rolling std)
- Expenditure Growth Rate

### Analysis Modules

**1. Exploratory Data Analysis**
- Time series trends
- Cross-country heatmaps
- Correlation analysis

**2. Anomaly Detection**
- Statistical: Z-score method
- Machine Learning: Isolation Forest

**3. Risk Assessment**
- Composite Risk Score = 0.35×Deficit + 0.30×Debt + 0.25×Volatility + 0.10×Growth
- Risk categories: Low / Moderate / High / Critical

**4. Forecasting**
- 5-year projections
- Scenario analysis (optimistic, baseline, pessimistic)

---

## 📊 Key Findings

1. **Structural Deficit Crisis**: Majority of countries exceed -3% threshold
2. **Debt Acceleration**: Sharp increase post-2015
3. **Revenue Volatility**: Root cause identified - commodity dependence
4. **Risk Assessment**: Significant portion at high/critical risk
5. **Forecasts**: Policy window 2025-2027 for intervention

---

## 🛠️ Technologies

**Language:** Python 3.8+

**Libraries:**
- pandas - Data manipulation
- numpy - Numerical computing
- scikit-learn - Machine learning
- matplotlib & seaborn - Visualization
- scipy - Statistical analysis

**Environment:** Jupyter Notebook

---

## 📁 Repository Structure
```
├── data/                  # Datasets
├── notebooks/             # Analysis notebooks
├── visualizations/        # Generated charts
├── reports/              # Documentation
└── requirements.txt      # Dependencies
```

---

## 🚀 Getting Started

### Installation
```bash
# Clone repository
git clone https://github.com/[your-username]/africa-fiscal-sustainability-analysis.git

# Navigate to directory
cd africa-fiscal-sustainability-analysis

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

---

## 💡 Policy Recommendations

**Immediate (2025):**
- Emergency support for critical-risk countries
- IMF/multilateral engagement

**Short-term (2025-2027):**
- Revenue diversification
- Tax base broadening
- Debt restructuring

**Long-term (2027-2030):**
- Fiscal rules enforcement
- Institutional capacity building

---

## 🎓 Context

**Type:** Final Year Project / Hackathon Submission  
**Field:** Systems Engineering / Data Science  
**SDG Alignment:** SDG 8, 10, 16

---

## 📧 Contact

**[Your Name]**  
Systems Engineering Student  
[Your University]

LinkedIn: [your-profile]  
Email: [your-email]

---

## 📜 License

MIT License - See LICENSE file

---

## 🙏 Acknowledgments

- 10Alytics Hackathon
- World Bank, IMF, AfDB for data
- Dr. Orolu for supervision

---

⭐ **Star this repo if you find it useful!**
