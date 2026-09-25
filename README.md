# Awesome-Financial-Crime-Intelligence

## Top Financial Crime Intelligence Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on AML, Transaction Monitoring, Entity Resolution, Network Analytics, Fraud & Financial Crime Investigation*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Financial Crime Intelligence**. These systems help banks, fintechs, and regulated institutions detect money laundering, fraud rings, sanctions evasion, and other financial crime through transaction monitoring, entity resolution, network analytics, and investigation workflows.



**Examples** include Quantexa, Feedzai, Featurespace, NICE Actimize, Oracle FCCM, DataWalk, ThetaRay, ComplyAdvantage, AMLYZE, and SAS AML (the category leaders).



**Open-source emphasis**: Enterprise financial-crime platforms are heavily commercial and regulated. Practical open options include transaction-monitoring engines (**Jube**, **Osprey**), graph analytics, and research/AML prototypes. This section lists the strongest available open resources and is realistic about the large commercial and compliance gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Quantexa](https://www.quantexa.com/)**  

  Decision-intelligence platform specializing in entity resolution and network analytics for financial crime, risk, and large-scale data environments.



- **[Feedzai](https://www.feedzai.com/)**  

  AI-native RiskOps platform unifying fraud detection, AML, and risk operations with real-time scoring and behavioral intelligence for banks and payment processors.



- **[Featurespace](https://www.featurespace.com/)**  

  Adaptive behavioral analytics platform (ARIC) focused on real-time fraud and financial-crime detection with strong false-positive reduction.



- **[NICE Actimize](https://www.niceactimize.com/)**  

  Comprehensive enterprise financial-crime suite covering fraud, AML, sanctions, surveillance, and investigation workflows for global banks.



- **[Oracle Financial Crime and Compliance Management (FCCM)](https://www.oracle.com/)**  

  Oracle’s financial-crime and compliance platform for transaction monitoring, case management, and regulatory reporting inside the Oracle ecosystem.



- **[DataWalk](https://datawalk.com/)**  

  Knowledge-graph and investigative analytics platform used for complex financial-crime and intelligence investigations.



- **[ThetaRay](https://www.thetaray.com/)**  

  AI-powered transaction monitoring and financial-crime detection platform focused on anomaly detection and network insights.



- **[ComplyAdvantage](https://complyadvantage.com/)**  

  Financial-crime risk data and screening platform providing adverse media, sanctions, and risk intelligence for compliance teams.



- **[AMLYZE](https://amlyze.com/)**  

  AML and transaction-monitoring platform aimed at mid-market and specialized financial institutions.



- **[SAS AML and related financial-crime solutions](https://www.sas.com/)**  

  Enterprise analytics-driven AML and financial-crime detection offerings from SAS.



## Open-Source GitHub Projects

- **[Jube (AML & Fraud Transaction Monitoring)](https://github.com/jube-home/aml-fraud-transaction-monitoring)**  

  Fully open-source (AGPLv3) platform for real-time transaction monitoring, hybrid rule + ML detection, case management, and audit trails designed for AML and fraud prevention.



- **[Osprey](https://github.com/opensource-finance/osprey)**  

  Lightweight open-source transaction-monitoring service using CEL rules and FATF-style typologies—single Go binary, fast to deploy for rule-based detection.



- **[AML transaction-monitoring research and ML prototypes](https://github.com/)**  

  Community projects demonstrating large-scale transaction scoring, XGBoost/SHAP explainability, and GenAI-assisted SAR generation.



- **[Graph and network analytics open tools](https://github.com/)**  

  Neo4j, NetworkX, and related libraries used to model account relationships, mule networks, and collusive rings.



- **[Rule engines and typology open libraries](https://github.com/)**  

  Open business-rule engines and FATF-typology implementations usable for basic transaction monitoring.



- **[Entity-resolution open components](https://github.com/)**  

  Community tools for matching and linking customer and counterparty records across data sources.



- **[Case management open workflows](https://github.com/)**  

  Lightweight open systems for queuing, investigating, and documenting financial-crime alerts.



- **[Sanctions and watchlist open screening helpers](https://github.com/)**  

  Utilities for working with public sanctions lists and basic screening pipelines (not a substitute for commercial data feeds).



- **[Explainability and model-governance open tooling](https://github.com/)**  

  SHAP, MLflow, and related projects that support transparent and auditable ML models for AML.



- **[Documentation and typology open playbooks](https://github.com/)**  

  Guides and example rule sets aligned with common AML scenarios and regulatory expectations.



### Additional Strong Open-Source Options

- Prototyping real-time monitoring with **Jube** or **Osprey** for rule + ML detection and basic case handling.

- Using open graph databases to explore network structures around high-risk entities.

- Accepting that production-grade entity resolution at bank scale, regulatory-grade case management, global data feeds, model risk management, and examiner-ready audit trails still require commercial platforms (Quantexa, Feedzai, NICE Actimize, Featurespace, Oracle FCCM, SAS, etc.).

- Focusing open-source efforts on transparency of detection logic, data ownership, and education for compliance engineering teams.



**Frameworks for building custom systems**: Ingest transactions and customer data → apply open rules and ML scoring (Jube/Osprey or custom) → enrich with graph analytics → route alerts to case management → generate investigation narratives. Suitable for research, fintech sandboxes, and internal prototypes. Regulated financial institutions almost always rely on commercial financial-crime platforms for production compliance.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Financial-crime systems support regulatory obligations (AML, sanctions, fraud). Incorrect detection or incomplete investigations can create legal, financial, and reputational risk. Open-source tools are **not** a substitute for regulated commercial systems or professional compliance programs. This list is not legal, regulatory, or compliance advice.



---

**Made for financial-crime, AML, and compliance technology teams.**

Let's keep detection smarter, investigations clearer, and core logic as open as practical.
