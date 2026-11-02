# Awesome Enterprise Private Data Exchange

> A curated list of top Enterprise Private Data Exchange platforms — both SaaS/Hosted commercial solutions and open-source alternatives for secure, governed data sharing and monetization.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
- [Open-Source Software](#-open-source-software)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🌐 Sector Overview & Market Dynamics

The global Data Exchange Platform and Enterprise Data Sharing market is estimated at approximately **$5.6B to $6.5B**, expanding at a robust CAGR of ~15% to 16% (and anchoring an adjacent Enterprise Data Management market exceeding $100B+). The sector exhibits a **moderately concentrated oligopoly at the top**—where hyperscalers and data cloud heavyweights (AWS, Snowflake, Databricks) capture ~40% combined market share through embedded ecosystems—balanced by a **heavily fragmented long-tail** of specialized, jurisdiction-specific, and sovereign data space vendors driven by localized data residency regulations (e.g., GDPR, EU Data Act) and domain-specific compliance constraints.

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Enterprise Private Data Exchange platforms sorted descending by company size (valuation / revenue).

| Product | Company Size (Valuation / Revenue) | Starting Pricing (Specific Tier) | Free Tier Limit / Free Trial Limit | Deployment & Key Capabilities |
|---|---|---|---|---|
| **[AWS Data Exchange](https://aws.amazon.com/data-exchange/)** | **~$2.3T – $2.5T Mkt Cap** (Amazon) / **~$108B ARR** (AWS) | **$0 platform fee for buyers**; for publishers: **3% fulfillment fee** per paid transaction + **$0.04167/hour** per active data grant + S3 storage ($0.023/GB/mo) | **Free forever tier for open data**: Unlimited access to Open Data on AWS catalog (zero subscription fee); for AWS accounts: standard **12-month AWS Free Tier** & credits apply to underlying queries/storage. | AWS SaaS; native AWS billing integration, automated entitlements, support for S3 direct sharing, Redshift, and API assets with private offer support. |
| **[Databricks Marketplace](https://www.databricks.com/product/marketplace)** | **~$100B – $134B Valuation** (Dec 2024 / 2025) / **~$4B+ ARR** | **$0.07 – $0.15/DBU** (Standard compute jobs) / **$0.55/DBU** (SQL Pro); provider requires Unity Catalog Premium workspace (starts at **$0.22/DBU**) | **14-day free trial** with full compute/Unity Catalog access (includes free DBU usage credits; underlying cloud provider VM/storage costs billed separately or via cloud credits). | Databricks Lakehouse SaaS; Delta Sharing protocol, private exchanges, AI models, notebooks, and MCP servers sharing. |
| **[Snowflake Data Exchange](https://www.snowflake.com/en/data-cloud/workloads/collaboration/)** | **~$60B – $75B Mkt Cap** (NYSE: SNOW) / **~$3.6B ARR** (FY2025) | **$2.00 per Snowflake Credit** (Standard Edition On-Demand rate) + **$23/TB/month** capacity storage | **30-day free trial with $400 in free usage credits** (no credit card required upfront; expires after 30 days or when $400 credits are consumed). | Snowflake SaaS; private invitation-only exchanges, cross-cloud & cross-region replication, granular directory listings, zero data-copy sharing. |
| **[Revelate](https://www.revelate.co/)** | **~$80M Valuation** ($22M total funding) | **$2,500/month** (Core Data Fulfillment base subscription tier) | **14-day guided proof-of-concept / sandbox trial** with up to 5 test data product listings and 10 consumer invitations. | Multi-cloud SaaS; Databricks Delta Sharing and Snowflake integration, query-level delivery, automated entitlements and data marketplace monetization. |
| **[Harbr Data Commerce Platform](https://www.harbrdata.com/)** | **$50M+ Total Funding** (Series A led by Tiger Global & Dawn Capital) / **~$10M-$15M ARR est.** | **$3,500/month** (Enterprise starter license for private exchange deployment) | **30-day enterprise evaluation / POC trial** (custom-provisioned private tenant with pre-loaded sample datasets, up to 10 user licenses). | Customer Cloud (AWS/Azure/GCP); Organization-Based Access Controls (OBAC), branded enterprise storefront, multi-party data collaboration. |
| **[Opendatasoft](https://www.opendatasoft.com/)** | **~$36.3M Total Funding** (Salesforce Ventures) / **~$18M ARR** | **€1,250/month (~$1,350/mo)** billed annually (Essential / Professional portal license) | **30-day sandbox trial** (includes 5 published datasets, up to 100,000 API calls/month, and 3 workspace admin seats). | Multi-tenant SaaS (EU/US); SAP Datasphere & HANA integration, citizen-facing and private internal data portals, built-in visualization and API generator. |
| **[Narrative I/O](https://www.narrative.io/)** | **~$50M – $100M Valuation est.** ($13.8M funding) / **~$3.6M ARR** | **$1,000/month** (Data Collaboration Starter plan) + pay-per-net-new identity match | **14-day free trial** of Buyer Studio & Data Collaboration workspace (includes $250 credit toward query executions and connector setups). | SaaS; API-driven data delivery, Rosetta Stone data attribute mapper, AI agent MCP integration, precision buyer/seller commerce rules. |
| **[Datarade](https://datarade.ai/)** | **~$5M – $10M Valuation est.** ($1.23M funding) / **~$2.1M ARR** | **$0/month for Data Buyers**; for Data Providers: **€499/month (~$540/mo)** (DCC - Data Commerce Cloud Starter plan for listing & lead management) | **Free forever plan for buyers** (unlimited searches, RFQs, and vendor comparisons); providers receive a **14-day free trial** of Data Commerce Cloud. | SaaS; global data commerce network, 500+ DaaS vendors, multi-channel distribution orchestration, e-commerce storefront builder for data vendors. |
| **[Dawex Data Exchange](https://www.dawex.com/)** | **~$25M – $50M Valuation est.** (~$13M funding incl. Nemetschek) | **€1,500/month (~$1,620/mo)** (Corporate Data Hub entry subscription) | **30-day proof-of-concept / evaluation access** (up to 5 participating partner organizations, 20 data transactions). | SaaS & sovereign cloud; Gaia-X and European Data Spaces compliant, neutral governance, licensing terms enforcement, non-repudiation audit trails. |
| **[ThinkData Works](https://www.thinkdataworks.com/)** | **~$15M – $25M Valuation est.** (~$8M funding) / **~$3M-$5M ARR est.** | **$1,500/month** (Namara platform Starter data virtualization & catalog tier) | **14-day proof-of-concept trial** (up to 3 connected data sources, 50GB virtualized data processing, and 5 team user accounts). | Managed SaaS & hybrid-cloud; data catalog to commerce bridge, data virtualization, automated metadata governance, granular client-level licensing. |

---

## 🟩 Open-Source Software

Self-hosted, community-driven data exchange layers, federated data spaces, and collaboration platforms. Ranked in descending order by GitHub star count.

| Project | GitHub Stars | Stack & License | Key Highlights | Best For |
|---|---|---|---|---|
| **[CKAN](https://github.com/ckan/ckan)** | [![Stars](https://img.shields.io/github/stars/ckan/ckan?style=social&color=white)](https://github.com/ckan/ckan/stargazers) | Python / Flask / PostgreSQL / Solr<br>*(AGPL-3.0)* | World's leading open-source data portal platform used by national governments (data.gov) and enterprises. Granular access rights, comprehensive metadata harvesting, rich API extensions, and dataset publication workflows. | Enterprise and public-sector data portals, internal catalogs, and governed open data distribution. |
| **[Delta Sharing](https://github.com/delta-io/delta-sharing)** | [![Stars](https://img.shields.io/github/stars/delta-io/delta-sharing?style=social&color=white)](https://github.com/delta-io/delta-sharing/stargazers) | Python / Scala / Rust / Go<br>*(Apache-2.0)* | The industry's first open standard for secure, zero-copy data and AI asset sharing across organizations and clouds. Supports Apache Spark, Pandas, Databricks, Power BI, and Tableau without vendor lock-in. | Multi-cloud and cross-platform large-scale lakehouse data exchange without copying data. |
| **[X-Road](https://github.com/nordic-institute/X-Road)** | [![Stars](https://img.shields.io/github/stars/nordic-institute/X-Road)](https://github.com/nordic-institute/X-Road/stargazers) | Java / Linux / Docker<br>*(MIT)* | Nationally-scaled, secure distributed data exchange layer (driving Estonia and Finland's digital state). Features built-in address management, PKI machine-level authentication, cryptographic timestamps, digital signatures, and legally binding non-repudiation logs. | Governments, sovereign consortia, and highly regulated industries requiring legally defensible data interchange. |
| **[Magda](https://github.com/magda-io/magda)** | [![Stars](https://img.shields.io/github/stars/magda-io/magda)](https://github.com/magda-io/magda/stargazers) | TypeScript / Scala / Kubernetes<br>*(Apache-2.0)* | Cloud-native data catalog and federated data marketplace framework developed by CSIRO's Data61. Provides automated metadata harvesting across disparate platforms, policy-based authorization (OPA), and dataset previewing. | Cloud-native enterprise data hubs requiring automated federated indexing and Open Policy Agent access controls. |
| **[Eclipse Dataspace Components (EDC)](https://github.com/eclipse-edc/Connector)** | [![Stars](https://img.shields.io/github/stars/eclipse-edc/Connector)](https://github.com/eclipse-edc/Connector/stargazers) | Java / Gradle / Docker<br>*(Apache-2.0)* | The core reference implementation of the Dataspace Protocol under the Eclipse Foundation and Gaia-X framework. Separates control plane (contract negotiations, catalog protocol) from data plane (streaming, multi-cloud transfers) with sovereign policy enforcement. | European Data Spaces, cross-enterprise industrial ecosystems (Catena-X), and sovereign B2B data sharing. |
| **[dataall](https://github.com/data-dot-all/dataall)** | [![Stars](https://img.shields.io/github/stars/data-dot-all/dataall)](https://github.com/data-dot-all/dataall/stargazers) | Python / React / AWS CDK<br>*(Apache-2.0)* | Open-source enterprise data marketplace and data mesh orchestration framework on AWS. Enables data producers to publish datasets, manage share requests with approval workflows, and automatically provision AWS Lake Formation & S3 permissions. | AWS-centric enterprises adopting decentralized Data Mesh architectures with self-serve data exchange. |
| **[Ocean Market](https://github.com/oceanprotocol/market)** | [![Stars](https://img.shields.io/github/stars/oceanprotocol/market)](https://github.com/oceanprotocol/market/stargazers) | TypeScript / Next.js / Web3<br>*(Apache-2.0)* | Decentralized, privacy-preserving data marketplace frontend for publishing, buying, and consuming data services. Integrates compute-to-data technology to preserve private algorithmic queries without exposing underlying raw datasets. | Decentralized data monetization, AI compute-to-data exchanges, and tokenized private dataset trading. |
| **[FIWARE Data Space Connector](https://github.com/FIWARE/data-space-connector)** | [![Stars](https://img.shields.io/github/stars/FIWARE/data-space-connector)](https://github.com/FIWARE/data-space-connector/stargazers) | Java / Docker / Microservices<br>*(Apache-2.0)* | Out-of-the-box data space connector combining Eclipse Dataspace Components (EDC) with FIWARE identity and context broker capabilities. Supports OID4VC (verifiable credentials), trusted contract negotiation, and smart-city data interchange. | Smart cities, utilities, and regional industrial consortia adopting FIWARE and Gaia-X data space architectures. |
| **[Gen3 Cloud Automation](https://github.com/uc-cdis/cloud-automation)** | [![Stars](https://img.shields.io/github/stars/uc-cdis/cloud-automation)](https://github.com/uc-cdis/cloud-automation/stargazers) | Python / Bash / Kubernetes<br>*(Apache-2.0)* | Core infrastructure automation for Gen3 Data Commons, developed by the Center for Translational Data Science at the University of Chicago. Manages secure microservice deployments (Fence auth, Indexd indexing, Arborist authz) for regulated research data sharing. | Academic, biomedical, and genomic consortia building sovereign, HIPAA/NIH-compliant research data commons. |
| **[Unified Data Marketplace (UDAM)](https://github.com/CyberSolo/UDAM)** | [![Stars](https://img.shields.io/github/stars/CyberSolo/UDAM)](https://github.com/CyberSolo/UDAM/stargazers) | TypeScript / Node.js / Next.js<br>*(MIT)* | Lightweight API-first data marketplace backend for monetizing data services and datasets. Features native Stripe billing integration, AES-256 token encryption for API credentials, concurrency-safe PostgreSQL row locks, and instant token checkout. | Indie developers and agile teams looking to quickly deploy a self-hosted, monetizeable data storefront with integrated credit-card billing. |

---

## 📊 Comparison at a Glance

| Software | License / Model | Deployment | Core Focus | Company Size / Community Scale |
|---|---|---|---|---|
| **AWS Data Exchange** | Proprietary SaaS | AWS Cloud | Cloud-native dataset & API procurement | ~$2.4T Amazon / ~$108B AWS ARR |
| **Databricks Marketplace** | Proprietary SaaS | Multi-Cloud Lakehouse | Lakehouse data, AI models & apps sharing | ~$100B+ Valuation / ~$4B+ ARR |
| **Snowflake Data Exchange** | Proprietary SaaS | Multi-Cloud Snowflake | Private & partner governed zero-copy sharing | ~$60B-$75B Mkt Cap / ~$3.6B ARR |
| **Revelate** | Proprietary SaaS | Customer Cloud / SaaS | Granular query-level data product distribution | ~$80M Valuation |
| **Harbr** | Proprietary SaaS | Customer Cloud (VPC) | Branded data marketplace & OBAC access | $50M+ Total Funding |
| **Opendatasoft** | Proprietary SaaS | Managed Cloud | Branded enterprise & citizen data portals | ~$18M ARR |
| **Narrative I/O** | Proprietary SaaS | Managed Cloud | API-driven data delivery & AI agent integration | ~$50M-$100M Valuation |
| **Datarade** | Proprietary SaaS | Managed Cloud | B2B data monetization & vendor discovery | ~$2.1M ARR |
| **Dawex** | Proprietary SaaS | Sovereign Cloud / SaaS | Cross-border data spaces & compliance governance | ~$25M-$50M Valuation |
| **ThinkData Works** | Proprietary SaaS | Managed Cloud / Hybrid | Data virtualization & catalog-to-commerce | ~$15M-$25M Valuation |
| **CKAN** | Open Source (AGPL-3.0) | Self-Hosted / K8s | Enterprise catalog & public data portal | 5,100+ GitHub Stars |
| **Delta Sharing** | Open Source (Apache-2.0) | Cross-Cloud / Self-Hosted | Universal open protocol for zero-copy sharing | 960+ GitHub Stars |
| **X-Road** | Open Source (MIT) | Self-Hosted / Distributed | Secure distributed data interchange layer | 870+ GitHub Stars |
| **Magda** | Open Source (Apache-2.0) | Cloud-Native / K8s | Federated metadata catalog & access policies | 600+ GitHub Stars |
| **Eclipse EDC** | Open Source (Apache-2.0) | Self-Hosted / Multi-Cloud | Gaia-X / IDS sovereign dataspace connector | 420+ GitHub Stars |
| **dataall** | Open Source (Apache-2.0) | AWS Cloud | AWS Data Mesh marketplace & governance | 250+ GitHub Stars |
| **Ocean Market** | Open Source (Apache-2.0) | Decentralized / Web3 | Privacy-preserving compute-to-data exchange | 220+ GitHub Stars |
| **FIWARE DSC** | Open Source (Apache-2.0) | Docker / Microservices | Smart-city & industrial data spaces | 60+ GitHub Stars |
| **Gen3** | Open Source (Apache-2.0) | Kubernetes / Cloud | Biomedical & genomic research data commons | 40+ GitHub Stars |
| **UDAM** | Open Source (MIT) | Self-Hosted / Docker | Turnkey Stripe-powered data API marketplace | Active Open-Source Repo |

---

## 🤝 Contributing

Contributions are welcome! If you know of an enterprise data exchange platform or open-source dataspace connector that should be listed here, please open a pull request with:

- Project name and URL
- Brief description and primary use case
- Stack, deployment model, and license
- Why it stands out in enterprise data exchange

Please ensure the project is actively maintained and relevant to private data exchange.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
