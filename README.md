# 📉 Global Tech Layoff Analysis (2020 - 2025)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Looker Studio](https://img.shields.io/badge/Looker_Studio-4285F4?style=for-the-badge&logo=google-looker-studio&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

> **Uncovering the patterns behind the massive wave of tech layoffs: A deep dive into geography, industry risks, and financial health.**

---

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Business Background](#-business-background)
- [Data & Methodology](#-data--methodology)
- [Key Insights](#-key-insights)
- [Critical Alerts](#-critical-alerts)
- [Recommendations](#-recommendations)
- [Author](#-author)

---

## 📖 Project Overview
The tech sector experienced a massive shock post-pandemic, marked by unprecedented mass layoffs. This project analyzes a dataset of **2,000+ tech companies** involving over **558,000+ affected employees** from 2020 to Q1 2025.

The goal is to dissect layoff patterns based on **Geography, Industry, Company Stage, and Financial Health** to provide actionable insights for job seekers and investors.

**Key Metrics:**
* **Total Layoffs:** 558,109 employees
* **Avg Layoff Rate:** 25.01% of workforce
* **Total Companies:** 1,521 analyzed
* **Capital Affected:** $1.2M+ (Money Raised)

---

## ❓ Business Background
Post-pandemic market corrections led to significant uncertainty. Key questions addressed in this analysis:
1.  **Who is most affected?** Big Tech giants or small startups?
2.  **Does funding equal safety?** Does raising millions protect a company from bankruptcy?
3.  **Sector Risk:** Which industries are cutting "fat" vs. cutting "limbs"?

---

## 🛠 Data & Methodology
**Source:** [Layoffs.fyi](https://layoffs.fyi/) (Combined dataset 2020 - 2025).

**Tech Stack:**
* **Python (Pandas, NumPy):** Used for data cleaning, date standardization, missing value imputation (logic-based), and entity name normalization.
* **Looker Studio:** For interactive dashboarding and geospatial visualization.

**Data Cleaning Process:**
1.  **Date Standardization:** Converted inconsistent formats to standard datetime.
2.  **Imputation:** Calculated missing `Laid_Off` counts using `Company_Size * (Percentage/100)`.
3.  **Entity Fixing:** Corrected company name typos and standardized industry categories (e.g., merging "Transportion" into "Transportation").

---

## 💡 Key Insights

### 1. Geographic Hotspots
* **The US is the epicenter:** With over **400,000+ layoffs**, the USA far outpaces other regions, followed by India, Germany, the UK, and Sweden.

### 2. The "January Purge" (Temporal Trends)
* **Peak Crisis:** Q1 2023 saw the highest spike in layoffs, signaling a massive market correction post-pandemic.
* **Cyclical Pattern:** Layoffs tend to spike in **January** following end-of-year performance reviews and budget restructuring.

### 3. Sector Vulnerability
* **Highest Volume:** Retail, Consumer, and Transportation sectors lost the most people (headcount), correlating with declined global consumer spending.
* **Highest Risk:** Motor Vehicle (EV) and Hardware sectors had the highest **percentage** cuts (up to 60%), making them the most volatile career paths.

### 4. The Funding Paradox
* **Money $\neq$ Safety:** Analysis shows that companies with massive funding (>$100M) are not immune.
* **Size Impact:** Small companies (<100 employees) had the highest average layoff rate (**47.04%**), often cutting nearly half their workforce to survive.

---

## 🚨 Critical Alerts: Bankruptcy Watch
The analysis identified **138 companies** that went completely out of business (100% layoffs).
* **Notable Case:** **Lilium** (Aerospace), a Post-IPO company, laid off 100% of its staff (1,000 people).
* **Insight:** "IPO" status does not guarantee sustainability. Cash flow health is more critical than total capital raised.

---

## 🚀 Recommendations

### For Talent (Job Seekers)
* **Sector Safety:** Prioritize **B2B SaaS** sectors which showed more stability compared to capital-intensive sectors like Hardware/EV or Consumer Retail.
* **Timing:** Be cautious of career moves in **Q4**, as the "January Purge" cycle poses a risk for new hires.

### For Investors
* **New Metrics:** Shift evaluation focus from "Valuation" to **"Sustainability & Burn Rate"**.
* **Diversification:** Avoid over-exposure in consumer-based sectors (Retail/Transport) which are highly sensitive to purchasing power fluctuations.

---

## 👤 Author

**Irfan Maulana**
*Data Analyst | SQL & Python Enthusiast*

* [LinkedIn](https://www.linkedin.com/in/maulana-irfan/)
* [GitHub](https://github.com/fafnir96)
* [Instagram](https://www.instagram.com/i.ipaang)

---
*Project completed as part of DQLab Data Analyst Bootcamp.*
