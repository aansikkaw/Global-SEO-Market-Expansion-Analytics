# 📈 Global SEO & Market Expansion Analytics

<div align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white" alt="Matplotlib" />
  <img src="https://img.shields.io/badge/Data_Strategy-00599C?style=for-the-badge" alt="Data Strategy" />
</div>

## 📌 Executive Summary
This project analyzes the organic search performance of a global sports media brand across four key international markets (English, Italian, Brazilian, French). The objective was to translate raw Google Search Console and competitive keyword data into an actionable business strategy.

Through rigorous data wrangling and exploratory data analysis (EDA), I identified a **critical site architecture flaw affecting 74% of international traffic**. I then developed a targeted market expansion framework to optimize content depth against primary competitors, specifically leveraging high-efficiency markets to fund aggressive expansion in lagging territories.

---

## 🛠️ Data Science Methodology & Market Analysis

### 1. Data Quality & Anomaly Detection
Before analyzing market trends, the dataset was subjected to rigorous hygiene checks:
* **Integrity Audits:** Identified impossible tracking anomalies (6 rows where Clicks > Impressions resulting in CTRs > 100%), isolating these errors to prevent skewed market averages.
* **Architecture Mapping:** Uncovered a severe Hreflang/URL mismatch where **74% of regional keywords** (e.g., ranking in Italy) were being served by non-localized URLs (e.g., English or French), actively cannibalizing international SEO growth.

### 2. Market Segmentation & Performance Analysis
Conducted comprehensive EDA to isolate high-value growth vectors:
* **Efficiency vs. Scale:** Identified **Italy (IT)** as the most efficient market, generating the highest number of clicks (78.5k) and an 11.4% CTR, despite the **English (EN)** market having a larger raw Search Volume (1.5M but only a 10.0% CTR).
* **Top Performing Clusters:** Isolated the primary drivers of current organic traffic:
  1. *MMA results* (22.7k clicks)
  2. *NFL highlights* (19.7k clicks)
  3. *La Liga standings* (18.9k clicks)

### 3. Competitor Gap Analysis
Mapped the delta between internal URL rankings and competitor rankings across high-volume clusters to find "Low-Hanging Fruit" (high volume, poor rank):
* **France (NBA Playoffs):** Severe gap (Internal Rank #27.0 vs. Competitor Rank #4.1).
* **Brazil (Cricket Live Updates):** Severe gap (Internal Rank #27.9 vs. Competitor Rank #8.0).
* **Italy (Best Bookmakers):** High-value gap (Internal Rank #19.6 vs. Competitor Rank #1.0).

---

## 📊 Strategic Business Recommendations

Based on the data analysis, I developed a 4-point strategic roadmap for the stakeholders:

**1. Immediate Technical Remediation**
Implement automated 301 redirects and strict Hreflang tags to resolve the 74% URL/Country mismatch. Google must be forced to serve the correct regional URL to the correct searcher to restore geographic targeting.

**2. Defend & Attack Market Strategy**
* **Defend Italy:** Continue high-frequency publishing (news, scores) to maintain dominance in our most efficient, highest-CTR market.
* **Attack France:** Aggressively close the competitor gap on the "NBA Playoffs" cluster by building a dedicated French-language guide, moving from rank #27 to compete with the #4 incumbent.

**3. Content Depth Optimization (Page 2 to Page 1)**
Target high-volume keywords ranking between positions 11-20. For example, "La Liga Standings" in France and Brazil commands 97k in search volume but ranks #18.6 and #10.8 respectively. By auditing the #1 competitor and matching their semantic depth (adding live tables, history, and stats), we can triple traffic without creating net-new URLs.

**4. Resolve Intent Mismatches**
Correct heuristic mismatches where generalized pages are ranking for unrelated queries (e.g., a "Tennis Live Score" URL ranking for "F1 Results"). We must create dedicated pages for missing clusters and fix internal linking to improve relevance scores and reduce bounce rates.

---

## 📁 Repository Structure
* `SEO_Data_Analysis.ipynb`: The Python analytics pipeline (EDA, anomaly detection, visualizations).
* `big-sports.csv`: The cleaned dataset.
* `requirements.txt`: Environment dependencies.

## 🚀 How to Explore the Analysis
git clone https://github.com/aansikkaw/seo-market-analysis.git
cd seo-market-analysis
