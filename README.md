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
│   └── wise_case_study.ipynb    # Full exploratory analysis
│
├── presentation/
│   └── Wise_MXN_USD_Analysis_Final.pptx    # Executive slides
│
└── README.md    # This file
```

---

## 🔍 Key Insights

### 1. Primary Driver Identified
User Experience (New vs Existing) shows 2-3x more variance than Region or Platform:
- **User Experience gap:** 19.6pp
- Region variance: 10.4pp  
- Platform variance: 9.0pp

### 2. Root Cause: Payment Step
Funnel breakdown reveals bottleneck at Created→Funded:
- New users: 34.9% payment success
- Existing users: 60.9% payment success
- **26pp gap** (2x larger than payout step)

### 3. Validated Across Regions
Cross-analysis confirms pattern is consistent:
- LatAm: 33pp gap (New vs Existing)
- NorthAm: 29pp gap
- Other: 29pp gap

Not a regional issue - it's a systemic New user experience problem.

### 4. February Performance Decline
Both segments declined in February:
- New users: 19.0% → 17.3% (-1.7pp)
- Existing users: 40.9% → 38.3% (-2.6pp)

Not just mix effect - suggests product or market change requiring investigation.

---

## 💡 Recommendations

### Priority 1: Optimize New User Payment Experience
**Problem:** 26pp gap at payment step

**Actions:**
- Investigate friction points (session replays, user interviews)
- Test solutions: simplified UX, trust signals, local payment methods
- Target 50% gap closure = +15.9% volume

**Timeline:** 3-6 months

### Priority 2: Investigate February Decline
**Finding:** Both New (-1.7pp) and Existing (-2.6pp) segments declined

**Actions:**
- Review late Jan/early Feb product deployments
- Analyze seasonal patterns in comparable routes
- Check for external market factors

---

## 🛠️ Methodology

**Approach:**
- Hypothesis-driven exploration (tested Region, Platform, User Experience)
- Root cause analysis via funnel step breakdown
- Cross-validation (Region × Experience) to rule out confounding factors
- Impact quantification through payment-focused scenarios

**Tools:**
- Python (pandas, numpy, matplotlib)
- Jupyter Notebook for exploratory analysis
- PowerPoint for executive communication

**Data Limitations:**
- No access to internal Wise benchmarks (BRL→USD, CLP→USD performance)
- Demand estimation based on external market data + methodology framework
- Targets defined through gap closure % (defensible without internal benchmarks)

---

## 📊 Business Impact Scenarios

Assumption: Improve Created→Funded for New users only (payout step constant)

| Scenario | Payment Rate | Overall Conv. | Additional Transfers | Impact |
|----------|--------------|---------------|---------------------|---------|
| Conservative (30%) | 42.9% | 21.9% | +1,007 | +9.5% |
| **Base Case (50%)** | **48.3%** | **24.6%** | **+1,678** | **+15.9%** |
| Optimistic (70%) | 53.6% | 27.4% | +2,350 | +22.3% |
| Best Case (100%) | 61.6% | 31.4% | +3,357 | +31.8% |

Base Case: Realistic with dedicated product improvements (simplified flow + trust signals + guided onboarding).

---

## 📈 Quick Start

1. **[View Analysis Notebook](analysis/wise_case_study.ipynb)** - Full exploratory analysis with code
2. **[Download Presentation](presentation/Wise_MXN_USD_Analysis_Final.pptx)** - Executive summary slides

---

## 📧 Contact

Joseph Cozer Saadia  
[LinkedIn](https://www.linkedin.com/in/your-profile) | [Email](mailto:your.email@example.com)

---

*Case study completed February 2026*
