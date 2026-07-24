# Native GA4 Traffic & E-Commerce Analytics

![Looker Studio](https://img.shields.io/badge/Looker_Studio-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Google Analytics 4](https://img.shields.io/badge/GA4-E37400?style=for-the-badge&logo=googleanalytics&logoColor=white)

## 📌 Executive Summary
This project demonstrates native platform proficiency in **Google Analytics 4 (GA4)** by connecting Looker Studio directly to the live **Google Merchandise Store GA4 property**. 

The interactive dashboard evaluates marketing channel acquisition efficiency, user engagement quality, and e-commerce conversion performance across web traffic.

* **Live Interactive Dashboard:** (https://datastudio.google.com/reporting/ea466e3d-bebd-4af1-8139-e747052ca74f)
* **Data Source:** Live GA4 Demo Account (`GA4 - Google Merchandise Store`)

---

## 📊 Core KPIs & Native GA4 Schema

The dashboard tracks end-to-end web performance using standard GA4 native dimensions and metrics:

| Category | GA4 Metric / Dimension | Description |
| :--- | :--- | :--- |
| **Traffic Volume** | `Sessions`, `Active users` | Total site visits and unique active visitor counts |
| **Traffic Quality** | `Engaged sessions`, `Engagement rate` | Sessions lasting >10s, with 2+ pageviews or a conversion |
| **Acquisition** | `Session default channel group` | Standardized channel buckets (Organic, Direct, Paid Search) |
| **Conversion** | `Key events`, `Session key event rate` | High-value actions and session conversion efficiency |
| **E-Commerce** | `Purchase revenue` | Total transactions generated on site |
| **Segmentation** | `Device category` | Desktop vs. Mobile vs. Tablet traffic breakdown |

---

## 📈 Key Analytics Insights

1. **Acquisition Efficiency:** Baseline organic search and direct traffic drive the bulk of engaged session volume and overall store revenue.
2. **Engagement Dynamics:** Desktop users exhibit significantly higher `Engagement rate` and `Session key event rate` compared to mobile visitors, indicating potential checkout mobile UX friction.
3. **Channel Performance:** `Session default channel group` segmentation reveals where high traffic volume fails to translate into key event conversions.

---

## 🛠 Tech Stack
* **Analytics Engine:** Google Analytics 4 (GA4 Native API)
* **Visualization:** Google Looker Studio
