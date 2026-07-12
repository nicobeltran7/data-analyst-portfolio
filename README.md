# 👋 Welcome To My Data Analyst Portfolio

I'm the **sole data professional at Mobile Infrastructure (NYSE: BEEP)**, a publicly traded parking REIT — I own the pipeline end to end, from raw operator files to the numbers leadership acts on. I came to the U.S. with broken English and a deadline to learn fast; data became my second language.

The three flagship projects below replicate the patterns I run in production — built clean-room, on synthetic data, from scratch. I write about the systems behind them on **[Analyst Vault](https://substack.com/@nicobeltran7)**.

---

## 📊 Featured Projects

### [⚙️ Hotel Pricing Data Platform](https://github.com/nicobeltran7/hotel-pricing-data-platform)

**Python • dbt • DuckDB • CI/CD — Analytics Engineering**

End-to-end pricing pipeline: four deliberately messy vendor feeds → idempotent upsert-by-natural-key ingestion with quarantine handling → dbt star schema with 25 tests, window-function gap-fill, and incremental models. CI runs the entire pipeline and proves idempotency on every push. `dbt build`: 31/31 green.

### [📐 Hotel Ops Semantic Model](https://github.com/nicobeltran7/hotel-ops-semantic-model)

**Power BI (PBIP/TMDL) • DAX — BI Development**

Enterprise-grade semantic model as reviewable code, not a binary: star schema over the pricing platform's marts, a time-intelligence calculation group (6 variants × 11 measures without measure explosion), tested RLS roles, and documented import-vs-DirectQuery and incremental-refresh trade-offs.

### [💰 Property Portfolio P&L Analysis](https://github.com/nicobeltran7/property-portfolio-pnl-analysis)

**SQL • Financial Analysis • Executive Communication**

18 months of GL-grain actuals vs budget for a 12-property portfolio. Variance decomposition SQL separates revenue effects from cost effects and types each miss — step change vs compounding drift — then a 2-page executive memo turns the findings into ranked recommendations. The memo is the deliverable.

### [👟 Consumer Brand P&L Dashboard](https://github.com/nicobeltran7/Power-Bi-Nike-Case)

**Power BI • DAX • Financial Modeling**

Full P&L statement in Power BI: hierarchical profit/loss structure, segment and regional breakdowns, 5-year trends with conditional formatting and drill-down.

### [🏡 Ames Housing Price Prediction](https://github.com/nicobeltran7/Python-Machine-Learning-Business-Case)

**Python • Machine Learning • Feature Engineering**

An interpretable ML baseline built through systematic EDA, correlation analysis, and feature engineering — focused on *why* predictions work, not just accuracy targets.

---

## 🛠️ Tech Stack

**Languages:** SQL, Python, DAX
**Platforms:** Microsoft Fabric, Dataverse, Azure, DuckDB
**Tools:** dbt, Power BI, GitHub Actions, Pandas, Git
**Skills:** ETL/ELT Pipelines, Dimensional Modeling, Financial Analysis, Stakeholder Communication

---

## 🤝 Let's Connect

📫 **LinkedIn:** https://www.linkedin.com/in/nicolasbeltran7/
💻 **GitHub:** https://github.com/nicobeltran7/
📝 **Analyst Vault:** https://substack.com/@nicobeltran7

*Each repository includes an architecture diagram, a design-decisions section, and the thinking behind the work. Dive in.*
