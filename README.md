# Awesome-Enterprise-Private-Data-Exchange

# Awesome Enterprise Private Data Exchange

> A curated list of top Enterprise Private Data Exchange platforms — both SaaS/Hosted commercial solutions and open-source alternatives for secure, governed data sharing and monetization.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Snowflake Data Exchange](#snowflake-data-exchange)
  - [Harbr Data Commerce Platform](#harbr-data-commerce-platform)
  - [Dawex Data Exchange](#dawex-data-exchange)
  - [Revelate](#revelate)
  - [Databricks Marketplace](#databricks-marketplace)
  - [AWS Data Exchange](#aws-data-exchange)
  - [ThinkData Works](#thinkdata-works)
  - [Datarade](#datarade)
  - [Narrative I/O](#narrative-io)
  - [Opendatasoft](#opendatasoft)
- [Open-Source Software](#-open-source-software)
  - [X-Road](#x-road)
  - [Unified Data Marketplace (UDAM)](#unified-data-marketplace-udam)
  - [Gen3 Data Commons](#gen3-data-commons)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Enterprise Private Data Exchange platforms. These are not open-source but are included as reference points for feature comparison.

### Snowflake Data Exchange
**Type:** Private data marketplace within Snowflake  
A Data Exchange is a private, invitation-only marketplace where providers publish data products as listings for a selected group of consumer accounts. Unlike direct sharing (which requires specifying each account individually), a Data Exchange acts as a searchable catalog where invited members can browse and subscribe to listings. Access is controlled per listing, so different teams or partners can receive different levels of access to the same dataset. Data Exchange supports cross-region and cross-cloud sharing via replication. Requires provisioning by Snowflake [citation:1][citation:14].  
**Best for:** Organizations already on Snowflake that need scalable, governed data distribution across business units, subsidiaries, or partners without building a separate marketplace.

### Harbr Data Commerce Platform
**Type:** Private data marketplace with advanced access control  
A private, fully governed data marketplace that combines self-service data commerce with enterprise-grade identity controls. Key differentiators include a policy-based IAM system with fine-grained access control at the user, organization, product, and asset levels, plus proprietary Organization-Based Access Controls (OBAC) that let operators define how organizations interact within the marketplace. Supports one-sided, multi-sided, and enterprise data-sharing models on a single platform. Integrates with Databricks, AWS, Azure, and Google. Deploys on the customer's cloud of choice, preserving commits and discounts [citation:2][citation:15].  
**Best for:** Enterprises wanting a branded, invite-only data storefront with sophisticated multi-tenant governance and deployment flexibility across cloud providers.

### Dawex Data Exchange
**Type:** Data exchange and data space platform  
A French platform (founded 2015) focused on sovereign, compliant data transactions. Supports corporate data hubs, industry data exchanges, and data marketplaces. Emphasizes data sovereignty (precise control over licensing and usage terms), neutral governance (no vendor lock-in via Data Space architecture), and robust automated audit trails for compliance. Used across Europe, Asia, North America, and the Middle East [citation:3].  
**Best for:** Organizations prioritizing regulatory compliance, data sovereignty, and neutral governance, particularly in European and regulated markets.

### Revelate
**Type:** Data marketplace and distribution platform  
A secure, agnostic data marketplace platform with integrated data stores for provisioning. The Query API product now integrates with Databricks Delta Shares, tables, and views, enabling administrators to create data products directly from Databricks assets. Consumers can query only the data they need, with tailored access across internal and external stakeholders. Streamlines cataloging, entitlements, and distribution [citation:4].  
**Best for:** Teams wanting a Databricks-integrated marketplace with granular, query-level data product delivery.

### Databricks Marketplace
**Type:** Open data and AI asset exchange  
An open exchange where providers publish datasets, AI models, notebooks, apps, and MCP servers for Databricks customers. Uses OpenSharing for secure data exchange. Supports both public listings and **private exchanges** where listings are discoverable only by member consumers. Providers need a Databricks account and a Unity Catalog-enabled premium workspace. The Universal Commit Drawdown program allows up to 10% of commits to be used for eligible third-party purchases [citation:5].  
**Best for:** Databricks-centric organizations wanting to share or acquire data, models, and AI assets within a governed lakehouse ecosystem.

### AWS Data Exchange
**Type:** Third-party data marketplace on AWS  
Allows providers to offer data products (files, APIs, Amazon S3, AWS Lake Formation) to AWS customers. Supports private offers with custom terms and payment schedules. Consumers subscribe through the AWS Console, with automatic billing according to the schedule. Auto-renewal can be toggled, and access is revoked upon subscription end. Providers can set refund policies for paid products [citation:6].  
**Best for:** AWS-native organizations wanting to procure or distribute third-party datasets with AWS billing integration.

### ThinkData Works
**Type:** Data catalog and distribution platform  
Combines data cataloging with virtualization, governance, and secure self-serve access. Enables organizations to connect to diverse sources, enrich data, and distribute it internally or externally. Features controlled access with revocability, usage tracking, quality monitoring, and support for monetization through a data marketplace [citation:7].  
**Best for:** Organizations needing a unified catalog-and-distribution layer that bridges internal data management with external data commerce.

### Datarade
**Type:** B2B data marketplace and commerce cloud  
Operates a marketplace connecting data buyers with providers (500+ providers, 100K monthly buyers, 4K data products), plus a Data Commerce Cloud (DCC) SaaS product for providers to grow omni-channel data businesses. Founded in Berlin in 2018, with $1M+ ARR and 500 DCC customers by 2023 [citation:8].  
**Best for:** Data providers wanting both marketplace exposure and a dedicated commerce platform, and buyers seeking to discover commercial datasets.

### Narrative I/O
**Type:** Data collaboration and delivery platform  
Provides a data collaboration platform with an MCP server for AI agent integration, NQL query execution, job management, and connector-based dataset delivery. Supports asynchronous workflows and dataset routing to destination applications [citation:9].  
**Best for:** Teams wanting programmatic, API-driven data delivery and collaboration with AI agent accessibility.

### Opendatasoft
**Type:** Data portal platform  
A data portal solution for democratizing data access, serving 350 customers across 25 countries with 3,000+ data portals. Available on SAP Store, integrates with SAP Datasphere and SAP HANA Cloud. Provides multi-tenant isolation, encryption, and >99.5% service levels [citation:10].  
**Best for:** Public sector and enterprise organizations wanting to build branded data portals for internal or external data sharing, particularly within SAP ecosystems.

---

## 🟩 Open-Source Software

Self-hosted, community-driven data exchange and collaboration platforms. All listed projects offer source code you can deploy on your own infrastructure.

### X-Road
**Stack:** Java / Linux / Docker | **License:** MIT  
A unified, secure open-source data exchange layer used at national scale by Finland, Estonia, and Iceland. Provides a standardized framework for organizations to exchange data securely via interfaces, with built-in address management, message routing, access rights management, machine-level authentication, transport-level encryption, time-stamping, digital signatures, and logging. Each service provider owns its data and controls access rights. Supports cross-border federation between ecosystems. The identities of participating organizations are verified via certificates issued by a trusted CA. Logs provide non-repudiation and can be used as evidence in court proceedings [citation:11].  
**Best for:** Government agencies, public sector consortiums, and regulated industries needing a proven, nationally-scaled secure data exchange layer with strong legal non-repudiation.

### Unified Data Marketplace (UDAM)
**Stack:** Node.js / Express / Next.js / PostgreSQL | **License:** Open Source (per GitHub)  
An API-first data marketplace backend for monetizing data services, APIs, or datasets. Includes Stripe integration for payments, AES-256 token encryption for secure access credentials, concurrency-safe order processing with PostgreSQL row locks, session-based auth with OAuth provider support, and Docker-ready deployment. Small orders (below a configurable limit) issue access tokens instantly; larger orders go through Stripe Checkout. Designed to provide the essential backend infrastructure so operators can focus on their data services [citation:12].  
**Best for:** Developers and small teams wanting to launch a data marketplace quickly with built-in payments and token management, without building commerce infrastructure from scratch.

### Gen3 Data Commons
**Stack:** Python / Cloud-native | **License:** Open Source (per arXiv)  
An open-source platform for managing, analyzing, and sharing research data through data commons. Provides structured data submission, querying, and sharing capabilities following operator-defined data models. Used in research and genomics contexts for controlled data access and collaboration [citation:13].  
**Best for:** Research institutions and academic consortia needing a governed data commons for sensitive or regulated research data.

---

## 📊 Comparison at a Glance

| Software | License | Type | Deployment | Best For |
|----------|---------|------|------------|----------|
| **Snowflake Data Exchange** | Proprietary | Private marketplace | Snowflake SaaS | Snowflake-native internal/partner sharing |
| **Harbr** | Proprietary | Private marketplace | Customer cloud | Multi-tenant governance + branded storefront |
| **Dawex** | Proprietary | Data exchange + data spaces | SaaS | Data sovereignty + regulatory compliance |
| **Revelate** | Proprietary | Data marketplace | SaaS | Databricks-integrated query-level delivery |
| **Databricks Marketplace** | Proprietary | Data + AI exchange | Databricks SaaS | Lakehouse data/model sharing |
| **AWS Data Exchange** | Proprietary | Third-party marketplace | AWS SaaS | AWS-billed third-party data procurement |
| **ThinkData Works** | Proprietary | Catalog + distribution | SaaS | Catalog-to-commerce bridge |
| **Datarade** | Proprietary | B2B marketplace + DCC | SaaS | Data provider commerce platform |
| **Narrative I/O** | Proprietary | Data collaboration | SaaS | API-driven data delivery + AI agents |
| **Opendatasoft** | Proprietary | Data portal | SaaS | Branded portals (SAP ecosystem) |
| **X-Road** | MIT | Secure data exchange layer | Self-hosted | Government/national-scale exchange |
| **UDAM** | Open Source | Marketplace backend | Self-hosted | Quick marketplace launch + Stripe |
| **Gen3** | Open Source | Research data commons | Self-hosted | Academic/research data sharing |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Enterprise Private Data Exchange platform that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
