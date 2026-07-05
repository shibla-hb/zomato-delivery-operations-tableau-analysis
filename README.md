# zomato-delivery-operations-tableau-analysis
# 🍽️ Zomato Delivery Operations Analysis

**Tableau dashboard analyzing 45,584 food delivery orders to identify what causes delivery delays and how to fix them.**

🔗 **Live Dashboard:** [https://public.tableau.com/views/deliveryoperations/dashbord3?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]
📁 **Dataset:** [Kaggle – Zomato Delivery Operations](https://www.kaggle.com/datasets/saurabhbadole/zomato-delivery-operations-analytics-dataset)
👩‍💻 **Analyst:** Shibla Nasreen | Tool: Tableau Public

---

## Overview

A 6-page interactive Tableau Story analyzing delivery performance across weather, traffic, vehicle condition, delivery partner demographics, geography, and scheduling patterns — built to find the biggest driver of delivery delay and recommend a fix.

**Key metrics:** 44,174 orders | 26.48 min avg delivery time | 4.63/5 rating | 1,320 delivery partners

---

## Key Findings

- 🚨 **Multiple deliveries is the biggest risk** — delivery time nearly doubles (22.9 → 47.8 min, +109%) when a partner handles 3 orders at once
- 🎉 **Festivals cause severe delays** — 45.5 min avg vs 25.98 min normally (+75%)
- 🌦️ **Weather & traffic add secondary delay** — fog adds ~7 min, jam traffic adds ~10 min
- 🔧 **Vehicle condition matters more than type** — only 34% of the fleet is good/excellent condition; poor-condition motorcycles alone account for 14,656 deliveries
- 👤 **Partner age has minimal effect** on ratings (4.5–4.6 across all ages)

---

## Recommendation

**Cap simultaneous deliveries at 1 additional order per trip** — this single change addresses the largest controllable delay in the dataset. Supporting actions: a festival staffing protocol, prioritized vehicle maintenance, and weather-adjusted delivery estimates.

---

## Tools

Tableau Public — calculated fields, dashboard actions, navigation objects, Story points, geospatial mapping

---

**Contact:** Shibla Nasreen | Doha, Qatar | [www.linkedin.com/in/shibla-nasreen]

 ***This project was built as part of a Data Analytics training portfolio, demonstrating end-to-end skills in data cleaning, exploratory analysis, dashboard design, and business storytelling using Tableau.****
