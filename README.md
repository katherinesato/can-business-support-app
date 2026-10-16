# 💵 Can Business Support App

> A centralized B2B intelligence platform connecting Canadian SMEs with emergency relief funds, government subsidies, and supply chain resilience resources during economic transitions.

---

## 🎯 About the Project

**Can Business Support App** is an academic software engineering project designed to solve a critical economic challenge: helping Canadian Small and Medium Enterprises (SMEs) navigate market turbulence, supply chain friction, and shifting trade dynamics with the United States.

Conceived as a B2B financial intelligence hub, the platform integrates a structured subsidy directory with a deterministic eligibility engine, delivering transparent, audit-ready program matching for corporate decision-makers. By bridging the gap between complex public policy and business execution, the system eliminates manual navigation overhead and provides actionable clarity when timing is critical.

---

## 🔍 The Pain Point Matrix

Canadian entrepreneurs face a severe information asymmetry across the public and financial sectors:

1. **Information Fragmentation & Cognitive Friction:** Business support programs are heavily dispersed across federal portals (`Canada.ca`), provincial networks (`Ontario.ca`), regional development agencies (`FedNor`, `FedDev`), crown corporations (`BDC`), and domain-specific initiatives, preventing a unified view of available funding.
2. **Regulatory & Financial Complexity:** Complex policy nomenclature, such as matching fund mandates, cumulative eligibility thresholds, and customs compliance rules, creates significant barriers to manual interpretation and compliance verification.
3. **High Discovery Costs & Operational Overhead:** Determining baseline eligibility currently demands specialized external advisory (legal/accounting) or extensive internal manual labor. This multi-week discovery cycle generates opportunity costs and delays critical liquidity.

---

## 🏛️ Platform Architecture & Product Philosophy

The platform adopts a **Dual-Core System Strategy** to maintain institutional credibility while providing modern usability:

### Core A: B2B Centralized Directory & Faceted Search
* **Institutional / Tabular Interface:** A clean, executive view inspired by financial dashboards and business intelligence terminals.
* **Faceted Search Filters:** High-precision filtering by:
  * Industry / Sector (Manufacturing, Agriculture, Logistics, etc.)
  * Enterprise Size / Revenue / Employee Count
  * Geographic Location / Province / Region
  * Financial Instrument Type (Non-repayable Grants, Publicly Guaranteed Loans, Tax Credits / SR&ED)
  * Program Status (Open Applications, Upcoming, Closed)
* **Structured Datasheets:** Every program is normalized into an executive datasheet featuring a 3-point summary, funding ranges, hard eligibility criteria, direct official links, and required documentation.

### Core B: Corporate Triage Assistant (Smart Natural Language / Guided Filter)
* **Executive Guided Filter:** Replaces casual quizzes with a declarative, professional triage form or natural language query input.
* **Deterministic Backend Scoring:** Inputs map directly to deterministic SQL filtering algorithms and dynamic eligibility scoring models in PostgreSQL.

---

## 🕒 Current Stage & Discovery Phase

The project is currently in the **Research and Product Discovery** phase. 

Current activities include:
- **User Research:** Surveying Canadian business owners and financial advisors to refine user friction points and criteria mapping.
- **Market Analysis & Benchmarking:** Auditing public portals (federal/provincial) and financial tools to map subsidy schemas and data fields.
- **Feature & Schema Definition:** Translating validated pain points into technical requirements, relational database schemas, and data ingestion pipelines.

---

## 🛠️ Tech Stack & Architecture

- **Frontend:** HTML, CSS, JavaScript / React (Clean, responsive B2B dashboard UI & dynamic triage state management)
- **Backend:** Python / Java (API routing, deterministic scoring engine, and automated ingestion logic)
- **Database:** PostgreSQL (Relational schema for structured subsidies, faceted filtering, and eligibility scoring)
- **Version Control:** Git & GitHub

---

## 📂 Project Architecture

```text
can-business-support-app/
│
├── docs/            # Research notes, benchmark analysis, and user personas
├── scripts/         # Web scrapers and data normalization scripts for public/private sources
├── frontend/        # Tabular B2B dashboard and Corporate Triage UI
├── backend/         # Eligibility scoring engine, API routing, and deterministic logic
└── database/        # PostgreSQL migrations, table schemas, and indexed subsidy data
```
