# 👋 Welcome To My Data Analyst Portfolio

I'm the sole data professional at Mobile Infrastructure (NYSE: BEEP), a publicly traded parking REIT. I own our data pipeline end to end, from the raw files our parking operators send to the numbers leadership acts on. I came to the U.S. with broken English and a deadline to learn fast; data became my second language.

The three featured projects below rebuild patterns from my day job on synthetic data, from scratch. I write about the systems behind them on [Analyst Vault](https://substack.com/@nicobeltran7).

---

## 📊 Featured Projects

### [⚙️ Hotel Pricing Data Platform](https://github.com/nicobeltran7/hotel-pricing-data-platform)

A pricing pipeline in Python, dbt and DuckDB. Four deliberately messy vendor feeds get validated, upserted by natural key (bad rows go to quarantine with reason codes), then modeled into a tested star schema with a gap-filled daily rate series. CI runs the whole pipeline on every push, tests included.

### [📐 Hotel Ops Semantic Model](https://github.com/nicobeltran7/hotel-ops-semantic-model)

A Power BI semantic model saved as PBIP/TMDL, so the DAX, calculation group, and RLS roles live in the repo as readable code instead of a .pbix binary. Sits on top of the pricing platform's marts. Time intelligence is handled with one calculation group instead of dozens of duplicate measures.

### [💰 Property Portfolio P&L Analysis](https://github.com/nicobeltran7/property-portfolio-pnl-analysis)

Eighteen months of GL-level actuals and budget for a synthetic 12-property portfolio. The SQL splits each property's NOI miss into revenue and cost effects to figure out what kind of problem it is, and a two-page memo turns the findings into recommendations.

### [👟 Consumer Brand P&L Dashboard](https://github.com/nicobeltran7/Power-Bi-Nike-Case)

A full P&L statement built in Power BI with public Nike data: hierarchical profit/loss structure, segment and regional views, and five-year trends with drill-down.

### [🏡 Ames Housing Price Prediction](https://github.com/nicobeltran7/Python-Machine-Learning-Business-Case)

Machine learning on the Ames housing dataset with the focus on interpretability rather than leaderboard accuracy: systematic EDA, correlation analysis, feature engineering, and a baseline model that can explain its predictions.

---

## 🛠️ Tech Stack

SQL, Python, and DAX day to day. Microsoft Fabric, Dataverse, and Azure at work; dbt, DuckDB, Power BI, and GitHub Actions in these projects.

---

## 🤝 Let's Connect

📫 **LinkedIn:** https://www.linkedin.com/in/nicolasbeltran7/
💻 **GitHub:** https://github.com/nicobeltran7/
📝 **Analyst Vault:** https://substack.com/@nicobeltran7
