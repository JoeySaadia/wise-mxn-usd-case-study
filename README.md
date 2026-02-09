# MXN→USD Route Launch - Case Study

Product Analyst case study analyzing Wise's MXN→USD route launch performance.

**Period:** Q1 2024 (January - March)

---

## 🎯 Executive Summary

**Key Finding:** New users drive 62.7% of volume but convert at **18.6%** vs **38.2%** for Existing users (19.6pp gap).

**Root Cause:** Payment step friction - New users at 34.9% vs Existing at 60.9% (26pp gap at Created→Funded).

**Impact:** Improving New user payment experience from 34.9% to 47.9% yields **+1,678 transfers (+15.9% volume)**.

**Decision:** Route is viable. Focus on New user payment experience optimization.

---

## 📁 Repository Structure
```
├── analysis/
│   ├── break_down_analysis.md       # Detailed analysis & methodology
│   └── wise_case_study.ipynb        # Exploratory notebook
│
├── presentation/
│   └── Wise_MXN_USD_Analysis_Final.pptx
│
└── README.md                         # This file
```

---

## 🚀 Quick Start

**Want the full story?**
1. **[Read Full Analysis](analysis/break_down_analysis.md)** - Complete methodology, hypothesis testing, and insights
2. **[View Notebook](analysis/wise_case_study.ipynb)** - Exploratory analysis with code
3. **[Download Slides](presentation/Wise_MXN_USD_Analysis_Final.pptx)** - Executive presentation

---

## 💡 Key Insights (TL;DR)

### 1. Primary Driver Identified
User Experience (New vs Existing) shows 2-3x more variance than Region or Platform.

### 2. Root Cause: Payment Step
New users stuck at 34.9% payment success vs 60.9% for Existing (26pp gap).

### 3. Validated Across Regions
Pattern consistent everywhere - not a regional issue, it's systemic.

### 4. Clear Impact Path
50% gap closure = +1,678 transfers (+15.9% volume). Realistic with product improvements.

---

## 🛠️ Methodology

- **Approach:** Hypothesis-driven exploration (tested Region, Platform, User Experience)
- **Root Cause:** Funnel step breakdown to identify bottleneck
- **Validation:** Cross-analysis to rule out confounding factors
- **Impact:** Payment-focused scenarios quantifying improvement potential

**Tools:** Python (pandas, numpy, matplotlib), Jupyter Notebook

---

## 📊 Recommendations

**Priority 1:** Optimize New user payment experience (26pp gap)
- Investigate friction points (session replays, user interviews)
- Test solutions: simplified UX, trust signals, local payment methods
- Timeline: 3-6 months

**Priority 2:** Investigate February performance decline
- Both New (-1.7pp) and Existing (-2.6pp) segments declined
- Review late Jan/early Feb deployments and seasonal patterns

---

*Case study completed February 2026*
