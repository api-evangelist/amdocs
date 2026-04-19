# Amdocs (amdocs)

Amdocs is a global technology company providing software and services to communications and media companies worldwide. Its connectX platform is a cloud-native SaaS BSS solution for telecom operators covering customer management, billing, provisioning, and subscription lifecycle. Amdocs also provides MarketONE for digital BSS, NetCracker for OSS network management, and an expanding suite of AI-powered telco solutions built on TM Forum Open APIs.

**URL:** [https://www.amdocs.com/](https://www.amdocs.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Telecom, BSS, OSS, Billing, Customer Management, MVNO, 5G, SaaS

## Timestamps

- **Created:** 2026-03-18
- **Modified:** 2026-04-19

## APIs

### Amdocs connectX BSS API

The Amdocs connectX BSS API provides cloud-native SaaS BSS capabilities for telecom operators, covering billing, provisioning, customer management, and subscription lifecycle. Built on TM Forum Open APIs.

**Human URL:** [https://devportal.amdocs-dbs.com/](https://devportal.amdocs-dbs.com/)

#### Tags

 - Billing, BSS, Provisioning, Telecom, MVNO, SaaS

#### Properties

- [Documentation](https://devportal.amdocs-dbs.com/)
- [GettingStarted](https://developer.amdocs-dbs.com/reference/getting-started-with-your-api)
- [APIReference](https://developer.amdocs-dbs.com/reference/getting-started-with-your-api)
- [OpenAPI](openapi/amdocs-connectx-openapi.yml)
- [AsyncAPI](asyncapi/amdocs-events-asyncapi.yml)

### Amdocs MarketONE API

Digital BSS capabilities for telecoms including catalog management, order management, customer management, and digital service delivery.

**Human URL:** [https://developer.m1amdocs.com/](https://developer.m1amdocs.com/)

#### Tags

 - BSS, Digital Services, Order Management, Telecom

#### Properties

- [Documentation](https://developer.m1amdocs.com/)
- [APIReference](https://developer.m1amdocs.com/api/)
- [Authentication](https://developer.m1amdocs.com/documentation/Content/E-API%20Guides/ULMProcessGuide/ProcessCatalogue/AuthenticateUserProcess.htm)

### Amdocs NetCracker OSS API

Network inventory management, network provisioning, and service assurance capabilities for telecom operators.

**Human URL:** [https://www.amdocs.com/products-services](https://www.amdocs.com/products-services)

#### Tags

 - Network Inventory, Network Management, OSS, Telecom

#### Properties

- [Documentation](https://www.amdocs.com/products-services)

## Common Properties

- [Website](https://www.amdocs.com/)
- [Portal](https://devportal.amdocs-dbs.com/)
- [Documentation](https://knowledge.amdocs-dbs.com/)
- [GettingStarted](https://developer.amdocs-dbs.com/reference/getting-started-with-your-api)
- [GitHubOrganization](https://github.com/open-amdocs)

## Features

| Name | Description |
|------|-------------|
| TM Forum Open API Compliance | All connectX APIs comply with TM Forum Open API standards, enabling fast integration with third-party systems. |
| AI-Native Capabilities | GenAI-powered platform capabilities including AI-driven customer journeys, predictive analytics, and automated decision making. |
| Cloud-Native SaaS Architecture | Serverless microservices architecture deployed on AWS providing elastic scalability and local data residency compliance. |
| eSIM Management | Built-in eSIM lifecycle management enabling telcos and MVNOs to support digital SIM provisioning. |
| Omnichannel Customer Experience | Pre-built customer journeys spanning mobile apps, web self-service, and multi-channel support. |
| MVNO and MVNE Support | End-to-end MVNO and MVNE capabilities including wireless prepaid, postpaid, and B2C solutions. |
| Catalog and Order Management | Flexible product catalog management for bundling connectivity with digital services. |
| Revenue Management | Converged billing, revenue assurance, and monetization capabilities. |

## Use Cases

| Name | Description |
|------|-------------|
| MVNO Launch | Rapidly launch new MVNO brands with pre-integrated telco-in-a-box capabilities. |
| BSS Digital Transformation | Migrate from legacy BSS to cloud-native SaaS BSS with TM Forum Open API compliance. |
| 5G Monetization | Launch and monetize 5G services with flexible catalog management and usage-based billing. |
| Customer Self-Service | Deploy omnichannel self-service portals and mobile apps with pre-built customer journeys. |
| Gen Z Mobile Services | Launch fully customizable mobile plans via AI-powered apps. |
| IoT Service Management | Manage IoT connectivity, device onboarding, and usage-based billing. |

## Integrations

| Name | Description |
|------|-------------|
| AWS | connectX is powered by Amazon Web Services providing cloud infrastructure and global reach. |
| TM Forum Open APIs | Full compliance with TM Forum Open API standards for ecosystem integration. |
| Microsoft | Customer Engagement Platform partnership for AI-driven customer interactions. |
| Network Management Systems | Integration with multi-vendor network management systems via NetCracker APIs. |

## Solutions

| Name | Description |
|------|-------------|
| connectX | All-in-one SaaS BSS platform for telcos and MVNOs with AI-powered capabilities. |
| MarketONE | Digital BSS platform for managing and monetizing subscriptions. |
| Amdocs Networks | Telco cloud transformation solutions for 5G, fiber, and IoT. |
| Digital Financial Services Platform | Mobile wallet and financial services enablement for telco operators. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amdocs connectX BSS API](openapi/amdocs-connectx-openapi.yml)

### AsyncAPI

- [Amdocs Events AsyncAPI](asyncapi/amdocs-events-asyncapi.yml)

### JSON Schema

- [15 JSON Schema files](json-schema/)

### JSON Structure

- [15 JSON Structure files](json-structure/)

### JSON-LD

- [amdocs-connectx-context.jsonld](json-ld/amdocs-connectx-context.jsonld)
- [amdocs-context.jsonld](json-ld/amdocs-context.jsonld)

### Examples

- [15 example JSON files](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amdocs connectX BSS API](capabilities/shared/connectx-api.yaml) — 5 operations for customer, subscription, and billing management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Telco Customer Management](capabilities/telco-customer-management.yaml) | connectX BSS API | 6 | BSS Operator, Customer Care Agent, Billing Team |

## Vocabulary

- [Amdocs Vocabulary](vocabulary/amdocs-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 5 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amdocs Spectral Rules](rules/amdocs-spectral-rules.yml) — 20 rules across 9 categories enforcing Amdocs API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
