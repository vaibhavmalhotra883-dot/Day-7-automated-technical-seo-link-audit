# Automated Technical SEO & Internal Link Equity Pipeline

An end-to-end Technical SEO data pipeline built with **Python**, **Google Sheets**, and **Looker Studio** to audit crawl health, on-page parity, and internal PageRank distribution across an enterprise multi-niche website (100+ core URLs).

> **Confidentiality Note:** All proprietary brand identifiers have been anonymized in public-facing reports to protect client privacy.

## 🎯 Project Objectives
- Automate the extraction and analysis of HTTP status codes, Title/H1 alignment, and link graphs.
- Identify internal link equity bottlenecks between high-intent commercial pages and top-of-funnel informational content.
- Deliver a self-service BI dashboard in Looker Studio for executive decision-making.

## 📊 Key Analytical Insights
- **Internal Inlink Skew:** Top-of-funnel informational pages accumulated up to **789 internal inlinks**, while core revenue-generating service pages averaged **~78 inlinks**.
- **Outlink Dilution:** Niche industry guides averaged **190–245 total internal outlinks**, creating opportunities to consolidate link equity toward primary commercial hubs.
- **Template & Content Parity:** Audited Title Tag vs. H1 Tag consistency and flagged duplicate URL structures for canonical/consolidation review.

## 🛠️ Tech Stack & Live Assets
- **Python (Google Colab):** Data cleaning, metric aggregation, and automated SEO auditing. -> [Open Colab Notebook](https://colab.research.google.com/drive/16bmky8fLhLrMZqTiFJvrm57elYT6f87W?usp=sharing)
- **Looker Studio:** Interactive data visualization and crawl distribution dashboard. -> [View Live Dashboard](https://datastudio.google.com/reporting/4c40cd43-2a3e-4472-8746-0691288a4ad2)
- **Google Sheets:** Structured relational dataset powering the BI layer. -> [View Audit Dataset](https://docs.google.com/spreadsheets/d/1qnNLaC9CMuf9M74waG3r0JK5IyxLPIXHYT2vTH_NL9Y/edit?usp=sharing)
