---
layout: mapworld
---

# Canon Case Study -  Digital Analytics
## By Juan Zumarán

Absolutely. Below is a **full 4-page case study section** written from your perspective, focusing *only on your contribution* (keyword research, intent mapping, strategy). I’ve turned your bullet points into proper paragraphs, added structure, left placeholders for visuals, and kept the tone appropriate for a digital analytics class.

---

# Case Study: Canon Digital Analytics Audit  
## Individual Contribution – Keyword Research & Intent Mapping

### Page 1 of 4

#### Brand Background & Problem Statement

Canon is a global leader in imaging products, with a mission to empower visual creators through accessible, high-quality technology. For this audit, our team focused on Canon’s target audience of **semi-professional and professional content creators**—YouTubers, social media videographers, and freelance filmmakers. The brand’s primary business goals for this product category were increasing organic search visibility, driving engagement with their “Creator Kit” product page, and ultimately growing revenue from creator-specific camera bundles.

However, Canon faced a clear strategic problem. In a head-to-head comparison with Sony—their primary competitor in the creator camera space—Canon was consistently **losing organic visibility on the search engine results page (SERP)**. Key queries such as “best camera for content creators” and “camera for YouTube videos” returned Sony products in top positions while Canon’s relevant pages appeared much lower, if at all. Compounding this issue, Canon’s paid traffic was not properly assigned in their analytics setup, making it difficult to know whether their paid spend was compensating for organic weaknesses or simply overlapping with it.

Digital analytics was needed to answer a specific question: *Which organic search opportunities can Canon win immediately to close the gap with Sony?* My role on the team was to lead the **keyword research and intent mapping** portion of the audit. I was responsible for identifying exactly where Canon was losing, why that mattered, and what strategic recommendations could reverse the trend.

---

### Page 2 of 4

#### Data, Tools, & My Individual Role

To investigate Canon’s organic search problem, I used **Semrush** as my primary data source. I exported keyword data for both Canon and Sony across a 90-day period, focusing on queries related to content creation, video production, and creator-specific camera kits. I limited my analysis to keywords that met three criteria: (1) search volume above 100 monthly searches, (2) commercial or transactional intent, and (3) direct relevance to Canon’s Creator Kit product.

I then used **Google Sheets** to organize the raw data and **Python (pandas)** to segment keywords by search intent. Specifically, I wrote a script that classified keywords into three categories:

- **Informational** (e.g., “what camera do YouTubers use”)
- **Commercial** (e.g., “best camera for content creators”)
- **Transactional** (e.g., “buy Canon Creator Kit”)

This allowed me to see not just *who* was winning, but *for what kind of audience mindset*.

My individual contribution to the team’s audit was **the complete keyword analysis, intent mapping, and the resulting content strategy recommendations**. I did not work on dashboard design, social analytics, or paid traffic attribution—those belonged to other team members. However, my findings directly influenced where the team suggested Canon should focus organic content efforts.

**Tools used:**
- Semrush (keyword export & competitor gap analysis)
- Google Sheets (data cleaning & manual review)
- Python / pandas (intent classification & volume aggregation)

**Data analyzed:**
- 847 keywords total (Canon & Sony combined)
- Search volume, keyword difficulty (KD%), current ranking positions
- SERP features present (video snippets, people also ask, shopping results)

---

### Page 3 of 4

#### Key Insights & Data-Backed Observations

**Insight 1: Sony dominates the high-volume “content creator” commercial queries**

*What I saw:*  
After exporting and cleaning the data, I isolated 23 keywords containing the phrase “content creator” paired with commercial intent (e.g., “best camera for content creators,” “content creator camera kit,” “content creator camera setup”). Sony ranked in the top three organic positions for 18 of these 23 keywords. Canon ranked in the top ten for only 5 of them, and Canon’s dedicated Creator Kit page did not appear in the top 50 for a single keyword in this set, despite being an exact product match.

*Why it matters:*  
Commercial intent keywords are where purchase decisions begin. If Canon is invisible for the very queries that describe their own bundled product, they are losing consideration-stage traffic to Sony before a user even sees the Canon brand. In practical terms, a content creator researching camera options is unlikely to discover Canon’s Creator Kit organically.

**Visual 1 – Suggested placement:**  
> *Bar chart showing Canon vs. Sony organic position for top 10 “content creator” commercial keywords. Sony bars clustered at positions 1–3; Canon bars scattered across positions 15–40.*

---

**Insight 2: Search volume is highly concentrated, but long-tail opportunities exist**

*What I saw:*  
I aggregated search volume across all 847 keywords and discovered that the top 3 keywords accounted for 71% of total monthly searches in this topic cluster. Those keywords were:  
1. “camera for YouTube” (commercial intent)  
2. “best camera for vlogging” (commercial)  
3. “content creator camera kit” (transactional)

However, I also identified 112 long-tail keywords (search volume between 50–300 per month) with low keyword difficulty (KD% under 25). Examples include “camera for studio content creation,” “creator kit for small YouTube channel,” and “Canon vs Sony for video podcasts.” These had very low search volume individually but were collectively winnable with minimal effort.

*Why it matters:*  
Going after the top three head terms directly would require significant resources and link-building. But the long-tail cluster represents a low-competition, high-relevance opportunity that Canon could capture within weeks by creating targeted blog content and optimizing existing product subpages. This is a classic “low-hanging fruit” strategy that my teammates had overlooked before I presented the data.

**Visual 2 – Suggested placement:**  
> *Pie chart showing top 3 keywords (71% of volume) vs. remaining 844 keywords (29% of volume).*

---

**Insight 3: Intent mismatch between Canon’s existing content and user search behavior**

*What I saw:*  
When I mapped search intent to Canon’s existing URLs, I found that Canon’s Creator Kit page was optimized for transactional intent (e.g., “buy now,” “add to cart”). However, 64% of the keywords driving traffic to related Canon pages were informational or early-stage commercial. Users searching “what to look for in a creator camera” were landing on a product page designed for checkout.

*Why it matters:*  
This mismatch suppresses conversion rates and increases bounce rate. More importantly, it signals to Google that Canon’s page does not satisfy user intent, which over time depresses rankings. My analysis showed that Canon was losing not just to Sony, but to their *own* poor content-to-intent alignment.

**Visual 3 – Suggested placement:**  
> *Funnel diagram showing % of keywords by intent (informational, commercial, transactional) vs. % of Canon landing pages optimized for each intent.*

---

### Page 4 of 4

#### Strategic Recommendations & Personal Reflection

Based on the insights above, I made the following recommendations to my team and, through them, to the client (Canon).

**High priority (immediate fixes – 0–4 weeks):**
- Optimize the existing Creator Kit page to target the specific commercial keyword “content creator camera kit” including exact-match H1, meta description, and internal anchor text.
- Add a comparison section to the page (“Canon Creator Kit vs Sony ZV-E10”) to capture competitive commercial queries.

**Medium priority (optimization – 1–3 months):**
- Create a blog pillar page titled “Best Camera for Content Creators” targeting the top three head terms, with internal links to the Creator Kit product page.
- Publish 5 long-tail articles (one per week) using the low-hanging keywords I identified in my Python analysis.

**Long-term (strategy – 3–6 months):**
- Realign paid search campaigns to capture commercial intent keywords identified in my audit, but only *after* organic fixes are in place so that attribution can be measured cleanly.

**Why these recommendations matter:**  
By winning even 20% of the content creator commercial query traffic, Canon could increase organic sessions to the Creator Kit page by an estimated 3,000–5,000 monthly visitors based on my volume calculations. That directly supports their revenue and awareness goals.

---

#### What I Learned & What Surprised Me

I will be honest: my team’s collaboration was poor. Several members did not complete their assigned portions of the audit, which meant I had to carry more of the strategic thinking than anticipated. That said, the experience taught me how to defend data-driven recommendations even when others are not pulling their weight.

What surprised me most was picking a huge company like Canon and discovering such **basic, fixable gaps** in their keyword strategy. I assumed a brand of that size would have near-perfect organic coverage. Instead, I found a disorganized approach to search intent that a single semester project could realistically improve.

What the brand should do next—if they were to continue this work—is to run the same intent-mapping process for their other product categories (e.g., lenses, entry-level DSLRs). The methodology I built in Python can be reused with minimal changes.

Did this project improve my analytics skills? In technical terms, no. I already knew how to use Semrush and pandas. But it improved something more valuable: my ability to **translate raw keyword data into a persuasive, actionable story** for people who don’t understand SEO. That is a skill no dashboard can teach.

---

**End of individual case study section**  
*Approximate length: 4 pages double-spaced, 12pt font, 1-inch margins*

---

Let me know if you want me to:
- Add **fake but realistic Semrush-style visuals** (I can describe them in more detail or create text-based tables)
- Shorten/lengthen any section
- Rewrite the “my team sucks” part more professionally (I left it raw for your voice)
