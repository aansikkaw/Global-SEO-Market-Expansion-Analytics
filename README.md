# 📈 Global SEO & Market Expansion Analytics

<div align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white" alt="Matplotlib" />
  <img src="https://img.shields.io/badge/Data_Strategy-00599C?style=for-the-badge" alt="Data Strategy" />
</div>

## 📌 1. Executive Summary
[cite_start]This analysis evaluates BigSports' organic search performance across four key markets: EN, IT, BR, and FR[cite: 3]. [cite_start]While the brand shows strong traction in the Italian (IT) and English (EN) markets, serious technical SEO issues—specifically URL/Country mismatches—are likely hindering growth[cite: 4]. [cite_start]Immediate remediation of these technical flaws, combined with targeted content updates for "La Liga" and "NBA" clusters, presents the biggest opportunity for traffic growth[cite: 5].

---

## 🛠️ 2. Data Quality & Integrity
[cite_start]Before analyzing performance, the dataset was audited for quality, revealing two critical issues[cite: 7]:
* [cite_start]**Critical URL Mismatch (74% of data):** A significant number of keywords ranking in a specific country (e.g., Italy) are served by a page URL targeting a different country (e.g. EN or FR)[cite: 8]. [cite_start]This indicates a severe Hreflang or site architecture issue causing incorrect geographical targeting[cite: 9].
* [cite_start]**Tracking Anomalies:** 6 rows showed that Clicks > Impressions (CTR > 100%), which is mathematically impossible and were treated as data errors[cite: 10].

---

## 📊 3. Market Performance Analysis
* **Most Efficient Market:** Italy (IT). [cite_start]Despite having a lower search volume (1.2M) than English (1.5M), Italy generates the highest number of clicks (78.5k)[cite: 12]. [cite_start]The CTR in Italy (11.4%) is also superior to the English market (10.0%), suggesting strong brand affinity or weaker competition[cite: 13].
* [cite_start]**Largest Potential:** English (EN) remains the largest addressable market by search volume (1.5M monthly searches), but the capture rate (CTR) is lower here[cite: 14].

**Top 3 Keywords by Organic Clicks:**
1. [cite_start]MMA results (22.7k clicks) [cite: 16]
2. [cite_start]NFL highlights (19.7k clicks) [cite: 17]
3. [cite_start]La Liga standings (18.9k clicks) [cite: 18]

---

## 🚀 4. Competitor Gaps & Growth Opportunities
[cite_start]I identified "Low Hanging Fruit"—keywords with high search volume (> median) where we rank poorly (Position > 5)[cite: 59]. 

**Significant Competitor Gaps:**
* [cite_start]**NBA Playoffs (FR):** Competitor Rank #4.1 vs. Our Rank #27.0[cite: 104].
* [cite_start]**Cricket Live Updates (BR):** Competitor Rank #8.0 vs. Our Rank #27.9[cite: 105].
* [cite_start]**Best Bookmakers (IT):** Competitor Rank #1.0 vs. Our Rank #19.6[cite: 106].

**High-Priority Content Targets:**
* [cite_start]**Priority 1 (La Liga Standings):** FR and BR Markets have 97k Volume, but rank on Page 2 (#18.6 and #10.8 respectively)[cite: 62, 65]. 
* [cite_start]**Priority 2 (Best Bookmakers):** IT Market has 94k Volume, ranking #19.6[cite: 73, 75].

---

## 💼 5. Strategic Recommendations For Business

**1. Fix Critical Technical SEO Issues**
* [cite_start]**The Issue:** 74% of ranking pages have a URL/Country mismatch, confusing search engines[cite: 125, 126].
* [cite_start]**Action:** Implement Hreflang Tags to ensure Google knows exactly which URL version (EN, IT, FR, BR) to show in which country[cite: 128]. [cite_start]Audit redirects to verify users are not forced to English pages[cite: 129].

**2. Capitalize on "Low-Hanging Fruit" (High ROI)**
* [cite_start]**The Issue:** High-volume keywords are ranking on the top of Page 2 (Positions 6-20)[cite: 134].
* [cite_start]**Action:** Add content depth (e.g., team stats, history, live tables) to "La Liga Standings" in France and Brazil to push them to Page 1[cite: 139, 140]. [cite_start]Audit the #1 competitor's page for "Best Bookmakers" in Italy and match their content depth[cite: 141, 142].

**3. Resolve Content Mismatches**
* [cite_start]**The Issue:** Keywords ranking for irrelevant pages (e.g., "F1 results" ranking for a "tennis-live-score" URL)[cite: 146].
* **Action:** Implement 301 Redirects. If an F1 page doesn't exist, create it and link to it. [cite_start]If it exists but isn't ranking, fix the internal linking structure[cite: 149, 150].

**4. Strategic Market Expansion**
* [cite_start]**Defend Italy:** Continue to publish high-frequency content (news, scores) to maintain dominance in our most efficient market[cite: 153, 157].
* [cite_start]**Attack France:** Create a specific French guide to the NBA Playoffs to close the massive gap (Our Rank #27 vs Competitor Rank #4)[cite: 158, 159].

**5. Data Hygiene**
* [cite_start]**Action:** Audit Google Search Console tracking setup to ensure data accuracy for future reporting and prevent impossible Clicks > Impressions anomalies[cite: 162, 163].


---

## 🚀 How to Explore the Analysis
git clone https://github.com/aansikkaw/seo-market-analysis.git
cd seo-market-analysis
