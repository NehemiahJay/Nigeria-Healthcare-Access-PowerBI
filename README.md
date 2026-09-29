# Nigeria Healthcare Access

**Tool:** Power BI · **Type:** Data Visualization, DAX, Interactive Dashboard Design
**Author:** Nehemiah — [LinkedIn](https://www.linkedin.com/in/nehemiahjibrin) · [Notion Portfolio](https://app.notion.com/p/Data-Analytics-Portfolio-Nehemiah-Jibrin-3b92ffc8dac380c2a2c0c71619a6402b?source=copy_link)

---

## Overview

A three-page interactive Power BI dashboard analyzing healthcare facility access across Nigeria — covering national totals, the public/private split, ownership structure, facility-level (referral tier) distribution, and per-capita density by state.

> **Business question:** Where is Nigeria's healthcare facility capacity — across public and private providers, ownership types, and referral tiers — concentrated or thin by state, and what does that reveal for a health system planner or policy analyst?

---


**A note on comparing this to the Excel project:** this dataset totals 51,022 facilities — a different figure from the Nigeria Health Facilities Registry used in the [Excel project](https://github.com/NehemiahJay/Nigeria-Health-Facility-analysis) (45,748). The two are not the same dataset and likely differ in scope, source, or collection date. State-by-state rankings should not be directly compared between the two projects as if measuring the same thing — though where a pattern holds across both (see Key Findings below), that's worth noting explicitly.

---

## What's in This Repo

| File | Description |
|---|---|
| `Nigeria_Healthcare_Access.pbix` | The Power BI report — 3 pages |
| `nigeria_healthcare_access_companion.docx` | Companion document — business question, insights, recommendations, limitations |

---

## Key Findings

- **A meaningful share of facilities have no documented ownership tier.** 38.3% (19,523 facilities) are logged as "Unknown" ownership type, far more than the 9.1% with unclear public/private status — meaning facilities are reasonably well classified as broadly public or private, but poorly documented at the specific ownership level.
- **Lagos ranks lowest in public facility density per capita — and this replicates across two independent datasets.** This project's lowest public-facilities-per-100k state is Lagos (4.98), mirroring the earlier Excel project where Lagos also ranked near the bottom per capita despite having the most facilities in raw count. This cross-dataset agreement is the strongest single finding across both projects.
- **The "top state" answer changes depending on which dataset you ask.** This dataset ranks Cross River highest in facilities per 100k; the Excel project ranked Nasarawa, Taraba, and Osun highest. Neither is wrong — it's a reminder not to treat one dataset's ranking as ground truth.
- **Nigeria's referral-tier imbalance shows up again, independently.** 88.0% of facilities here are Primary-tier, close to the Excel project's 95% finding — two separately sourced datasets agreeing makes this one of the most defensible claims in the portfolio.
- **Three separate "Unknown" categories exist in this dataset** (ownership type, public/private status, facility level) and should not be conflated — each reflects a different data gap.

Full write-up, including a flagged dashboard design limitation (the Private Facilities per 100K map's color scale), is in the companion document.

---

## Skills Demonstrated

DAX measures · Per-capita normalization · Multi-page report design · KPI card design · Choropleth and treemap visualization · Cross-project data validation · Honest handling of dataset-specific vs. replicated findings
