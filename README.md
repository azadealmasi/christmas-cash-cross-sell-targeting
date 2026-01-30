# Christmas Cash Cross-Sell Targeting 🎄💷

Data-driven targeting for a Christmas cash cross-sell campaign, including eligibility rules, rank-based prioritisation, a **Top 3,000 target list**, and a **Power BI dashboard** for campaign insights and, support insight-driven marketing decisions.

**Goal:** target supporters who are contactable and engaged but **have not previously made cash donations**, in order to maximise **new cash donor acquisition**.

---

## Project overview

The work combines:
- Clear **eligibility rules** aligned to campaign objectives  
- A **transparent, rank-based prioritisation method**  
- A practical **target list output** for campaign activation  
- An interactive **Power BI dashboard** for stakeholder insight  

The approach is designed to be **simple, explainable, and reusable** for future campaigns.

---

## Key components

### 1. Eligibility & filtering
Supporters must:
- Be **contactable** (marketing permissions in place)
- Have **no prior cash donation activity**

This ensures the campaign focuses on **new cash conversion**, rather than existing cash donors.

---

### 2. Prioritisation method

Eligible supporters are ranked using a **rank-based scoring approach** across engagement channels such as:
- Mail
- Membership
- Raffle
- Telephone

Ranks are combined into a single priority score:
- Higher engagement → better rank
- Lower final score → higher campaign priority

This method:
- Avoids scale issues between metrics
- Is easy to explain to non-technical stakeholders
- Produces a clear, defensible target list

---

### 3. Power BI dashboard

The dashboard provides insight into:
- Total supporters, donations, income, and communications
- Engagement by channel
- Comparison of **selected vs non-selected** supporters
- Supporter profile analysis (age bands, regions, engagement segments)

It is designed for use by **marketing, fundraising, and analytics teams**.

---

## Repository structure

## Repository structure

```
.
├── data/                     # Clean datasets used for analysis and modelling
│   └── data.xlsx

├── notebooks/                # Data preparation and targeting logic
│   ├── christmas_cash_cross_sell_targeting.ipynb
│   └── powerbi_dataset_preparation.ipynb
├── powerbi/                  # Interactive Power BI dashboard
│   └── Christmas Cash Cross-Sell Dashboard.pbix
├── outputs/                  # Final outputs ready for stakeholders
│   ├── dashboard_export.pdf 
    ├── powerbi_ready_dataset.csv
│   └── Top3000_ChristmasCash_TargetList.xlsx
├── slides/                   # Summary presentation
│   └── Christmas Cash Cross-Sell Targeting.pptx
└── README.md
```


---

## Outputs

- **Top 3,000 Target List (Excel)** – ready for campaign activation  
- **Power BI Dashboard (PBIX)** – interactive reporting and insight  
- **PDF Dashboard Export** – shareable with stakeholders  
- **Presentation Deck** – summary of approach and findings  

---

## Suggested campaign KPIs

- First-time cash donor conversion rate  
- Total cash income generated  
- Cost per acquisition (CPA)  
- Performance by engagement segment  

---

## Reusability

This framework can be reused for:
- Other seasonal campaigns
- Different donation types
- Alternative ranking or predictive models
- A/B testing targeting strategies

---


