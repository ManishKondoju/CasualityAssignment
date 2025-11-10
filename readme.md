# Does Doomscrolling Before Sleep Cause Poor Sleep Quality?
## Causal Inference Analysis with Data Preparation

![Header](https://images.unsplash.com/photo-1541781774459-bb2af2f05b55?w=1200&h=300&fit=crop)

---

## 📋 Overview

Investigates whether doomscrolling **causes** poor sleep quality using causal inference methods and comprehensive data preparation.

**Research Question:** Does scrolling social media before bed cause sleep loss, or do insomniacs simply scroll more?

**Answer:** Doomscrolling causes **0.6-0.9 hours (40-55 minutes)** of sleep loss per night.

---

## 🎯 Key Results

### Dataset 1: General Population (n=5,000)
- **PSM:** -0.67h (16% error) ✅
- **Regression:** -0.61h (24% error) ✅
- **Stratification:** -0.89h (11% error) ✅
- **Range:** 0.6-0.9 hours sleep loss

### Dataset 2: College Students (n=3,000)
- **Effect:** -1.0h (60 minutes) - **25% stronger!**
- **Prevalence:** 75% doomscroll (vs 50% general)
- **Impact:** Students critically sleep-deprived (<5h with scrolling)

---

## 🔬 Methods

**Data Preparation:**
- Missing data: Median imputation (10% missing)
- Outliers: Winsorization at 5th/95th percentile
- Categorical: One-hot encoding
- Features: DAG-based selection (age, stress, baseline sleep)

**Causal Analysis:**
1. Propensity Score Matching
2. Regression with Controls
3. Stratification by Age

**Validation:** All three methods converged (0.6-0.9h range)

---

## 🎥 Resources

**📹 Video (5 min):** [Watch Presentation](https://drive.google.com/file/d/1czgUCx2DBVkaSfSkIcjFXIHEEwGshVeq/view?usp=drive_link)

**📝 Quiz:** [Test Your Knowledge (15 questions)](https://form.typeform.com/to/xOa7aN72)

**📓 Notebook:** `doomscrolling_causality.ipynb`

---

## 🚀 Quick Start
```bash
# Clone
git clone https://github.com/ManishKondoju/CasualityAssignment.git

# Install
pip install pandas numpy matplotlib seaborn scikit-learn scipy

# Run
jupyter notebook doomscrolling_causality.ipynb
```

**Or:** Open in [Google Colab](link-to-colab)

---

## 💡 Key Insights

1. **Doomscrolling causes real sleep loss** - 40-55 min/night
2. **Students more affected** - 60 min/night (25% stronger)
3. **Data prep is critical** - Proper preprocessing enabled accurate estimates
4. **Method convergence validates findings** - All three methods agreed

---

## 🎓 Course Info

**Course:** INFO 7390 - Crash Course in Causality  
**Instructor:** Prof. Nik Bear Brown  
**Institution:** Northeastern University  
**Author:** Manish Kumar  
**Date:** November 9, 2025

---

## 📄 License

MIT License - Copyright (c) 2025 Manish Kumar

---

## 📧 Contact

**Email:** kumar.man@northeastern.edu  
**GitHub:** [@ManishKondoju](https://github.com/ManishKondoju)

---

**⭐ Star if helpful! | 💤 Put your phone away and sleep better!**