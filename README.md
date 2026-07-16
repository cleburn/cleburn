# Howdy, I'm Cleburn

**I build data pipelines that inform financial decisions.**

## Background

Bringing 10+ years of business leadership and real-world problem-solving to AI engineering.
Former U.S. Marine · Professional Athlete (MMA) · VP of Sales · Real Estate Investor · Author

---

## Contact

[LinkedIn](https://linkedin.com/in/cleburnwalker) · [Email](mailto:cleburn.walker@gmail.com)

---

## Market Intelligence

**Project Information Advantage** · *private while in active development*

An entity-agnostic discovery pipeline that captures market-relevant public signals at their source — SEC EDGAR filings (Form 4, 8-K), federal contract awards (SAM.gov, USAspending), healthcare catalysts (openFDA, ClinicalTrials.gov), and regulatory events (FTC HSR, lobbying disclosures) — then resolves noisy entity names to public tickers and surfaces cross-source events with strict alert idempotency.

- Always-on ingestion via systemd daemons and timers on a headless Linux host
- JSONL spools drained into DuckDB micro-batches for crash-safe, append-only storage
- Raw evidence preserved at capture, so every alert traces back to its source document

**[Kalshi Longshot Maker](https://github.com/cleburn/market-maker-bot)** · *retired*

A maker-side prediction-market bot and autonomous research lab grounded in the favorite-longshot bias literature. Three nodes with strict role separation — a research lab discovers, a control plane governs, an execution node trades — and research can never authorize capital; only the approval gate can. Retired after out-of-sample validation showed the targeted edge wasn't capturable after costs.

---

## Decision Tools with Real Money on the Line

**[Real Estate Investment Analyzer](https://github.com/cleburn/property-analyst-pro)** · [Live App](https://property-analyst-pro.streamlit.app/)

Ranks neighborhoods in Texas and Florida by cash flow potential and appreciation, using forward-validated ML predictions trained on 25 years of housing data across 11 metro areas and 3,000+ neighborhoods.

**[Amazon Ads Analytics](https://github.com/cleburn/amazon-ads-analytics)**

CLI analyzer for the Amazon Sponsored Products campaigns behind my published book series. Ingests Amazon Ads exports and KDP sales data, reconciles attribution gaps, tracks trends in SQLite, and turns it all into weekly reports with max-profitable-bid recommendations — every bid change is backed by the pipeline.

---

## Aegis — Governance for AI Agents

<a href="https://github.com/cleburn/aegis-cli">                                                        
<img src="https://raw.githubusercontent.com/cleburn/aegis-cli/main/aegis-banner.svg" alt="Aegis — Structured governance for AI agents" width="800" />                                                    
</a> 

Much of the work above is built with AI agents, which raised its own problem worth solving: agents need enforceable rules. So I built **Aegis**, an open-source, end-to-end governance framework — a [spec](https://github.com/cleburn/aegis-spec) defining scoped roles, permissions, and autonomy levels; a [CLI](https://github.com/cleburn/aegis-cli) that generates a complete policy from a conversation; and an [MCP server](https://github.com/cleburn/aegis-mcp) that validates and permits/denies every agent action at runtime. Stress-tested by generating compliant platforms in [defense](https://github.com/cleburn/cleardefense) (CMMC/ITAR), [fintech](https://github.com/cleburn/clearfintech) (PCI-DSS/SOX), and [healthcare](https://github.com/cleburn/clearhealth) (HIPAA).

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)

**Data:** Python · SQL · DuckDB · SQLite · Pandas · scikit-learn · statsmodels · Streamlit

**Systems:** TypeScript · Node.js · systemd · Git · MCP SDK

![cleburn's GitHub stats](https://my-github-stats-one-lemon.vercel.app/api?username=cleburn&show_icons=true&count_private=true&theme=nightowl)


