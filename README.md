# MySQL-CapStone-Project
# ZikFlix Consumer Usage & Preference Analysis (2021–2025)
### Isaac Okolie | Data Analyst | MySQL & Tableau

---

## 📌 What This Project Is About

ZikFlix is a pan-African streaming platform focused on Nollywood and regional storytelling.

This project is a **descriptive analytics engagement** that transforms five years of
event-level streaming data into actionable insights for content, product, and growth teams.

The analysis surfaces viewer preferences, regional patterns, device behavior,
audience segmentation, and monetization signals — all presented through an
interactive performance dashboard.

---

## 🎯 Project Objectives

- Measure **Total Watch Hours** to assess overall platform engagement
- Determine **Average Watch Time per User** to understand content depth
- Calculate **Completion Rate** to evaluate content retention
- Identify **Top Genres by Watch Hours** to guide content investment
- Examine **Regional Usage Patterns** to prioritize market expansion
- Analyze **Content Consumption by Age Group** to define audience segments
- Evaluate **Device Usage by Age Range** to support mobile-first decisions
- Assess **Gender Distribution** for inclusive content strategy
- Analyze **Subscription Tier Distribution** to evaluate monetization performance

---

## 📊 Dataset Overview

| Property | Detail |
|----------|--------|
| Dataset | ZikFlix Viewing Events (Cleaned) |
| Total Records | 50,000 Events |
| Total Columns | 19 |
| Analysis Period | 2021 – 2025 |
| Visualization Tool | Tableau |

### Key Fields:
Event_ID, Event_Timestamp, User_Id, Content_ID, Device_Type, Country,
City, Watch_Duration_Minutes, Watch_Hours, Language_Used, Weekday,
Year_Month, Age, Age_Group, Gender, Subscription_Tier, Primary_Genre,
Content_Dur_Minutes, Is_Completed

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Tableau | Dashboard & visualizations |
| MySQL | Data cleaning, preparation and exploration |

---

## 📋 Key Metrics (Dashboard KPIs)

| KPI | Value |
|-----|-------|
| **Total Watch Hours** | 6,352 Hrs |
| **Average Watch Time** | 88.9 Mins |
| **Completion Rate** | 17.28% |
| **Total Events** | 50,000 |

---

## 🔍 Key Findings

### 📺 Content & Engagement
| Finding | Detail |
|---------|--------|
| Top Genre | Drama — 1.25K watch hours |
| #2 Genre | Comedy — 0.94K watch hours |
| #3 Genre | Romance — 0.77K watch hours |
| Completion Rate | 17.28% — users start but rarely finish |
| Avg Watch Time | 88.9 mins — strong session depth |

### 🌍 Regional Performance
| Country | Users |
|---------|-------|
| Nigeria | 31,188 — dominant market |
| Ghana | 3,690 |
| Kenya | 2,924 |
| South Africa | 2,539 |
| Cameroon | 2,043 |

### 👥 Audience Demographics
| Segment | Finding |
|---------|---------|
| Top Age Group | Adults dominate consumption |
| #2 Age Group | Mid-Age users |
| Gender Split | Male 49.05% / Female 47.16% / Non-binary 1.94% / Prefer Not Say 1.85% |
| Primary Device | Mobile Phone — 26,972 events (54%) |

### 💳 Subscription Tiers
| Tier | Users | % |
|------|-------|---|
| Free (Ad-Supported) | 28,084 | 52.75% |
| Basic | 12,191 | 25.57% |
| Premium | 9,725 | 21.68% |

---

## 💡 Key Business Insights

1. **Drama, Comedy, and Romance** dominate watch hours — emotionally engaging, story-driven content resonates most with the ZikFlix audience
2. **Nigeria is the primary market** — accounting for 62% of all viewing events
3. **Mobile phone is the #1 device** — the platform is being consumed as a mobile-first experience
4. **17.28% completion rate** — users engage but don't finish content, indicating a content-length or recommendation issue
5. **52.75% of users are on the free tier** — significant monetization opportunity through paid conversion
6. **Adults and Mid-Age groups** drive the majority of content consumption — a digitally active, engaged core audience
7. **Gender distribution is nearly balanced** — platform appeals broadly across genders

---

## ✅ Strategic Recommendations

1. **Optimize for Mobile-First** — improve streaming on low bandwidth, enhance UI, introduce offline downloads
2. **Invest in Drama, Comedy & Romance** — allocate content budget toward the highest-performing genres
3. **Improve Completion Rate** — shorter content formats, better recommendations, stronger "Continue Watching" feature
4. **Target Adults & Young Adults** — tailor content and campaigns to the core audience segments
5. **Boost Paid Conversions** — premium-exclusive content, limited-time discounts, managed ad frequency
6. **Expand into Ghana, Kenya & Ethiopia** — localized content and regional partnerships for emerging markets
7. **Adopt a Data-Driven Culture** — continuously monitor MAU, watch hours, and completion rate

---

## 📈 Expected Outcomes

| Recommendation | Expected Outcome |
|----------------|-----------------|
| Mobile optimization | Higher engagement and satisfaction across the largest user segment |
| Genre investment (Drama, Comedy, Romance) | Increased watch hours and stronger audience retention |
| Completion rate improvements | More users finishing content, boosting engagement quality |
| Audience targeting (Adults, Young Adults) | Deeper engagement within core segments |
| Paid conversion strategy | Revenue growth from the 52.75% free-tier user base |
| Regional expansion | Platform growth beyond Nigeria into high-potential markets |
| Continuous KPI monitoring | Faster adaptation to user behavior changes |

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `CLEAN_ZIKFLIX.csv` | Cleaned dataset — 50,000 viewing events, 19 columns |
| `ZIKFLIX_Business_Brief.docx` | Original client business brief |
| `ZIKFLIX_PROJECT_REPORT.docx` | Full written analytics report |
| `Zik-Flix-Analytics-Report.pptx` | Presentation deck |
| `screenshots/dashboard.png` | ZikFlix Performance Dashboard screenshot |
| `README.md` | This documentation file |

---

## 🖥️ Dashboard Preview

The ZikFlix Performance Dashboard (2021–2025) includes:
- Total Watch Hours, Avg Watch Time, Completion Rate KPI cards
- Device Dominance by Age Group (stacked bar)
- Age Group by Watch Hours (horizontal bar)
- Region Dominance (Africa map visual)
- Top Genre by Watch Hours (ranked bar)
- Gender Distribution (donut chart)
- Subscription Tier Distribution (pie chart)

---

## 👤 Author

**Isaac Okolie**
Data Analyst & Data Analytics Tutor | Nigeria

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://linkedin.com/in/isaac-okolie)

---

*Descriptive Analytics | ZikFlix, Inc. | 2021–2025*
