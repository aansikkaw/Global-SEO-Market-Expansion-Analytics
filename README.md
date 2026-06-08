# 📈 Global SEO & Market Expansion Analytics

<div align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white" alt="Matplotlib" />
  <img src="https://img.shields.io/badge/Seaborn-4C4C4C?style=for-the-badge&logo=python&logoColor=white" alt="Seaborn" />
  <img src="https://img.shields.io/badge/Data_Strategy-00599C?style=for-the-badge" alt="Data Strategy" />
</div>

## 📌 Executive Summary
This project analyzes the organic search performance of a global sports media brand across four key international markets (English, Italian, Brazilian, French). The objective was to translate raw Google Search Console and competitive keyword data into an actionable business strategy.

Through rigorous data wrangling and exploratory data analysis (EDA), I identified a **critical site architecture flaw affecting 74% of international traffic** and developed a targeted market expansion framework to optimize content depth against primary competitors.

---

## 🛠️ Data Science Methodology

### 1. Data Quality & Anomaly Detection
Before analyzing market trends, the dataset was subjected to rigorous hygiene checks:
* **Integrity Audits:** Identified impossible tracking anomalies (e.g., Clicks > Impressions resulting in CTRs > 100%), isolating these rows to prevent skewed market averages.
* **Architecture Mapping:** Uncovered a severe Hreflang/URL mismatch where 74% of regional keywords (e.g., Italy) were being served by non-localized URLs (e.g., English or French), actively cannibalizing international SEO growth.

### 2. Market Segmentation & Performance Analysis
Conducted comprehensive EDA to isolate high-value growth vectors:
* **Efficiency vs. Scale:** Identified Italy (IT) as the most efficient market (11.4% CTR; 78.5k clicks) despite the English (EN) market having a larger raw Search Volume (1.5M).
* **Competitor Gap Analysis:** Mapped the delta between internal URL rankings and competitor rankings across high-volume clusters (e.g., "NBA", "La Liga"), identifying "Page 2" keywords (Positions 11-20) as the highest-ROI targets for content remediation.

---

## 📊 Strategic Business Recommendations

Based on the data analysis, I developed a 4-point strategic roadmap for the stakeholders:

1. **Immediate Technical Remediation:** Implement automated 301 redirects and strict Hreflang tags to resolve the 74% URL/Country mismatch, restoring correct geographic targeting.
2. **Defend & Attack Market Strategy:** Defend the highly efficient Italian market through high-frequency publishing while aggressively attacking the French market by closing the competitor gap on the "NBA Playoffs" cluster (Internal Rank #27 vs. Competitor Rank #4).
3. **Content Depth Optimization:** Target high-volume keywords ranking between positions 11-20 (e.g., "La Liga"). Audit the #1 competitor's page and match semantic depth to push these URLs to Page 1.
4. **Resolve Intent Mismatches:** Correct heuristic mismatches where generalized pages (e.g., "Tennis Live Score") are ranking for unrelated queries (e.g., "F1 Results") to improve relevance scores and reduce bounce rates.

---

## 🚀 How to Explore the Analysis

**1. Clone the repository**
```bash
git clone [https://github.com/YOUR_GITHUB_HANDLE/YOUR_REPO_NAME.git](https://github.com/YOUR_GITHUB_HANDLE/YOUR_REPO_NAME.git)
cd YOUR_REPO_NAME
