**PQ Browser Rater – Official Page Quality Rating Skill**  
**Version 1.0 – September 2025**  
**Strictly follows the General Guidelines (Copyright 2025)**

This skill teaches any AI agent how to use a web browser to explore any URL + website and assign a correct Page Quality (PQ) rating **exactly** as defined in the official guidelines.  
No opinions. No shortcuts. 100% guideline-compliant.

---

### 1. Core Principles (Direct from Guidelines)

- **Purpose first** (2.2): Every page has a purpose. Determine the true purpose. If harmful or deceptive about its purpose or who is responsible → **Lowest**.
- **Harm screen before everything** (4.0): Check for harm to people/society, untrustworthy pages, or spammy behavior → **Lowest**.
- **YMYL check** (2.3): Topics affecting health, financial stability, safety, or society welfare require **much higher** standards for accuracy, E-E-A-T, and Trust.
- **Page parts** (2.4):
  - **Main Content (MC)**: Directly achieves the purpose (text, video, features, title, user reviews in some cases).
  - **Supplementary Content (SC)**: Supports experience (navigation, sidebars).
  - **Ads/Monetization**: Neutral by itself.
- **E-E-A-T** (3.4): Experience, Expertise, Authoritativeness, **Trust** (the most important). Center of every rating.
- **Reputation** (3.3): Must research using independent sources only (never trust self-claims alone).

---

### 2. Browser Exploration Protocol (Follow Every Time)

1. Open the **exact URL** in a clean browser (no ad blockers).
2. Identify MC / SC / Ads by reading, clicking tabs, testing interactive features.
3. Navigate to the **homepage** (click logo or trim URL after .com/.org/etc.).
4. Locate About Us, Contact, Customer Service, author bios.
5. Perform **reputation research** in new tabs:
   - `[website-name -site:website.com]`
   - `[“website-name” reviews -site:website.com]`
   - Wikipedia, news articles, expert reviews.
6. Fully test the MC (read full article, watch video, add to cart, use calculator, play game, etc.).
7. For YMYL or money-related pages: extra checks for contact info and accuracy.

---

### 3. Exact Rating Decision Process (Follow in Strict Order)

**Step 1 – Harm / Purpose Screen (Lowest Check)**  
If **any** of these are true → **Lowest** (or Lowest+ if borderline):
- Harmful purpose or deceptive about purpose/who created it (4.5.3)
- Harmful to Self or Others, Harmful to Specified Groups, or Harmfully Misleading (4.2–4.4)
- Untrustworthy (inadequate info, deceptive design, obstructed MC, malicious behavior) (4.5)
- Spammy (no MC, copied content, scaled abuse, expired domain, hacked) (4.6)

**Step 2 – Low Quality Check**  
If not Lowest but:
- Lacking E-E-A-T (5.1)
- Low-effort / low-originality MC or filler (5.2)
- Distracting Ads/SC (5.3)
- Mildly negative reputation or unsatisfying creator info (5.4–5.6)  
→ **Low** or **Low+**

**Step 3 – Medium (Default for most pages)**  
Beneficial purpose, adequate MC effort/originality, adequate E-E-A-T and reputation → **Medium** or **Medium+**

**Step 4 – High**  
High-quality MC (strong effort, originality, talent/skill), positive reputation, high E-E-A-T → **High** or **High+**

**Step 5 – Highest**  
Very high-quality MC, very positive reputation, very high E-E-A-T (clearly superior) → **Highest**

---

### 4. Special Cases (Direct from PDF)

- Encyclopedia pages → 9.1
- Error pages / No MC → 9.2 (usually Lowest)
- Forums & Q&A → 9.3
- YMYL pages: always apply higher standards
- Mixed signals: use the dominant characteristic

---

### 5. Required Output Format (Use Exactly)

```markdown
**URL**: [exact url]
**True Purpose**: [one sentence]
**YMYL?**: Yes/No + short reason
**Harm Screen Result**: Passed / Failed + exact guideline subsection
**MC / SC / Ads Summary**:
**E-E-A-T & Reputation Evidence** (include key quotes from browser research):
**Final PQ Rating**: High+  
**Justification** (use exact guideline language):
