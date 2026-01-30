# 📊 Marketing Campaign Performance Analysis


## 🎯 Project Overview

Analyzed 2,600 Google Ads campaigns for a Data Analytics Course to identify optimization opportunities. Discovered **$450K-$600K potential profit increase (15-20%)** through data-driven budget reallocation.

**Key Achievement:** Transformed messy marketing data into actionable insights using Python and PowerBI.

---

## 💼 Business Problem

Marketing team invested $538K in digital advertising but lacked visibility into:
- Which device platforms (Desktop, Mobile, Tablet) deliver best ROI
- Which keywords waste budget vs. generate profit
- Optimal device-keyword combinations
- Best days/times to run campaigns
- How much money is lost on underperforming campaigns

---

## 🔧 Technical Approach

### Data Cleaning & Preparation
- **Python (Pandas, NumPy)**: Cleaned 2,600 records
- Fixed 205 business logic errors (impossible data like conversions > clicks)
- Standardized 4 campaign name variations → 1
- Corrected 3 keyword spelling errors
- Handled 626 missing values across 7 columns
- Unified mixed date formats (MM/DD/YYYY + DD-MM-YYYY)

### Feature Engineering
Created 7 key performance metrics:
- **CTR** (Click-Through Rate)
- **CPC** (Cost Per Click)
- **CPA** (Cost Per Acquisition)
- **ROAS** (Return on Ad Spend)
- **ROI** (Return on Investment)
- **LTV** (Lifetime Value)
- **CAC** (Customer Acquisition Cost)

### Analysis & Visualization
- Built **5-page interactive PowerBI dashboard**
- Analyzed 18 device-keyword combinations
- Identified temporal patterns (day-of-week performance)
- Created conversion funnel analysis
- Developed ROI projection models

---

## 📈 Key Findings

| Metric | Value | Insight |
|--------|-------|---------|
| **Total Campaigns** | 2,600 | Comprehensive dataset |
| **Success Rate** | 91% | Most campaigns profitable |
| **Current Profit** | $3.15M | From $538K investment |
| **Average ROAS** | 6.6x | Strong overall performance |
| **Wasted Budget** | $50K+ | 9% losing campaigns |

### 🔍 Deep Insights

1. **Device Performance**
   - Desktop: $1.08M profit (ROAS: 6.57x) ✅ **Best performer**
   - Mobile: $1.05M profit (ROAS: 6.41x)
   - Tablet: $1.02M profit (ROAS: 6.37x)
   - **Action:** Shift 10-15% from Tablet to Desktop = +$75K

2. **Keyword Analysis**
   - "Learn data analytics" = Top performer
   - "Analytics for data" = Weakest (but still profitable)
   - 40% performance gap between best and worst
   - **Action:** Reallocate budget to top keywords

3. **Winning Combinations**
   - Top 10 device-keyword combos generate **3× profit** of bottom 10
   - Desktop + "learn data analytics" = Best combination
   - **Action:** Focus budget on proven winners

4. **Temporal Patterns**
   - Thursday = 25% more profitable than Tuesday
   - Clear day-of-week variance
   - **Action:** Adjust daily budgets based on performance

---

## 💰 Business Impact

### ROI Projections

| Scenario | Profit | Increase | Timeline |
|----------|--------|----------|----------|
| **Current** | $3.15M | Baseline | - |
| **Conservative** | $3.32M | +$175K (5.5%) | 2-4 weeks |
| **Aggressive** | $3.75M | +$600K (19%) | 2-3 months |

### Quick Wins (30 Days)
- Pause 234 losing campaigns → **+$50K**
- Increase Desktop budget 10% → **+$50K**
- Reduce weakest keyword spend → **+$15K**
- **Total:** +$115K in first month

---

## 🛠️ Tools & Technologies

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![PowerBI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

- **Python:** Data cleaning, transformation, analysis
- **Pandas & NumPy:** Data manipulation
- **PowerBI:** Interactive dashboard development
- **DAX:** Custom measures and calculations
- **Excel:** Date format standardization
- **Jupyter Notebook:** Analysis documentation

---

## 📊 Dashboard Preview

### Page 1: Executive Overview
![Executive Dashboard]

### Page 2: Device Performance
![Device Analysis]

### Page 3: Keyword Analysis
![Keyword Performance]

### Page 4: Device × Keyword Combinations
![Heatmap]

### Page 5: Temporal Analysis
![Time Patterns]

---

## 📁 Project Structure
```
marketing-campaign-analytics/
├── data/                      # Clean datasets
├── notebooks/                 # Jupyter notebooks
├── powerbi/                   # PowerBI dashboard file
├── reports/                   # PDF case studies
├── images/                    # Screenshots
└── scripts/                   # Python scripts
```

---

## 🚀 How to Use This Repository

### Prerequisites
```bash
- Python 3.8+
- PowerBI Desktop
- Jupyter Notebook
```

### Installation
```bash
# Clone the repository
git clone https://github.com/[your-username]/marketing-campaign-analytics.git

# Navigate to project directory
cd marketing-campaign-analytics

# Install required packages
pip install pandas numpy jupyter
```

### Run the Analysis
```bash
# Open Jupyter Notebook
jupyter notebook notebooks/data_cleaning_analysis.ipynb
```

### View Dashboard
1. Open PowerBI Desktop
2. File → Open → Select `powerbi/Marketing_Dashboard.pbix`
3. Interact with visuals and filters

---

## 📄 Documentation

- **[Full Case Study](reports/Case_Study_Full.pdf)** - Comprehensive analysis (10 pages)
- **[Executive Summary](reports/Executive_Summary_1Pager.pdf)** - One-page overview
- **[Project Poster](reports/Poster.pdf)** - Visual summary

---

## 💡 Key Learnings

1. **Data Quality is Critical:** 205 business logic errors would have led to wrong decisions
2. **Small Optimizations = Big Impact:** 15-20% profit increase without new ad spend
3. **Combination Analysis:** Device × Keyword matrix revealed hidden patterns
4. **Visualization Matters:** PowerBI dashboard enabled stakeholder buy-in

---

## 📞 Contact

**Danial Adnan Khan**
- LinkedIn: https://www.linkedin.com/in/danialadnankhan/
- Email: danialadnanseven@outlook.com


---

## 🙏 Acknowledgments

- Dataset source: Marketing campaign data (2024)
- Tools: Python, PowerBI, Jupyter Notebook
- Inspiration: Real-world business problem solving

---

⭐ **If you found this project helpful, please give it a star!**
