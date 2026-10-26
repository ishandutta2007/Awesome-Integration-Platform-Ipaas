# Awesome-Integration-Platform-Ipaas

# Top Integration Platform (iPaaS) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Workflow Automation, Enterprise Integration & Self-Hosted Connectivity*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Integration Platform as a Service (iPaaS)**. These tools enable organizations to connect applications, automate data flows, and orchestrate business processes across cloud and on-premises systems—reducing manual work and eliminating point-to-point integration sprawl.

**Examples** include ServiceNow IntegrationHub, Zapier, Make, Workato, Tray.io, MuleSoft Anypoint Platform, Boomi, Celigo, Microsoft Power Automate, and SnapLogic (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosted workflow automation, API integration, and data pipeline orchestration—ideal for organizations building sovereign integration infrastructure without per-task or per-connection licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow IntegrationHub](https://www.servicenow.com/)**  
  Enterprise integration platform on the Now Platform with prebuilt spokes for common enterprise systems, Flow Designer for visual automation, and central management of integrations across ITSM, HR, and security workflows.

- **[Zapier](https://zapier.com/)**  
  Market-leading no-code automation platform with thousands of app integrations; triggers and actions-based workflows for connecting SaaS tools without engineering effort.

- **[Make](https://www.make.com/)**  
  Visual automation platform (formerly Integromat) with advanced flow logic, error handling, and granular control over data transformation between apps.

- **[Workato](https://www.workato.com/)**  
  Enterprise automation platform with AI-powered recipe building, low-code connectors, and governance features for cross-functional business workflows.

- **[Tray.io](https://tray.io/)**  
  Low-code automation platform with powerful data transformation capabilities and enterprise-grade security for complex integration workflows.

- **[MuleSoft Anypoint Platform](https://www.mulesoft.com/)**  
  Enterprise iPaaS and API management platform with API-led connectivity approach, extensive connector library, and runtime for on-premises or cloud deployment.

- **[Boomi](https://boomi.com/)**  
  Cloud-native integration platform with visual process design, extensive connector ecosystem, and master data management capabilities.

- **[Celigo](https://www.celigo.com/)**  
  Integration platform focused on mid-market businesses with prebuilt integration apps for NetSuite, Salesforce, Shopify, and other common SaaS systems.

- **[Microsoft Power Automate](https://powerautomate.microsoft.com/)**  
  Microsoft's automation platform with RPA capabilities, extensive connectors across Microsoft and third-party services, and deep integration with the Power Platform ecosystem.

- **[SnapLogic](https://www.snaplogic.com/)**  
  Enterprise integration platform with AI-powered pipeline building and support for real-time and batch data flows across cloud and on-premises systems.

## Open-Source GitHub Projects

- **[n8n](https://github.com/n8n-io/n8n)**  
  Leading open-source workflow automation platform (Sustainable Use License, ~25k+ GitHub stars); visual node-based editor with 200+ pre-built integrations covering SaaS apps, databases, and APIs; supports self-hosting with Docker, custom node development, and AI agent capabilities; positioned as the most feature-complete open-source alternative to Zapier and Make for technical teams .

- **[Activepieces](https://github.com/activepieces/activepieces)**  
  Open-source, MIT-licensed workflow automation platform with 500+ pre-built "pieces" (integrations) covering Google Sheets, Slack, OpenAI, HTTP, and webhooks; features a beginner-friendly visual flow builder, AI Agents and Copilot built into the editor, human-in-the-loop approval steps, sandboxed JavaScript/TypeScript code steps, and MCP server support for AI tool integration; Docker-deployable with PostgreSQL and Redis, or one-click Railway deployment; positioned as a privacy-first Zapier/Make alternative with unlimited self-hosted tasks .

- **[Cenit IO](https://github.com/cenit-io/cenit)**  
  100% open-source integration Platform as a Service (iPaaS) written in Ruby (MIT, ~505 GitHub stars); provides a backend platform with a React-based frontend UI for managing integrations; includes Odoo ERP integration addons; actively maintained with recent commits as of July 2026 .

- **[Apache NiFi](https://github.com/apache/nifi)**  
  Open-source data flow automation and processing platform (Apache 2.0); visual interface for designing data pipelines with 100+ processors; excels at complex data routing, transformation, and high-throughput ingestion; higher learning curve than workflow automation tools but stronger for data engineering use cases .

- **[Node-RED](https://github.com/node-red/node-red)**  
  Open-source flow-based programming tool (Apache 2.0) with extensive IoT and integration nodes; browser-based editor for wiring together devices, APIs, and services; commonly used for IoT data pipelines, event-driven automation, and rapid integration prototyping .

- **[Airbyte](https://github.com/airbytehq/airbyte)**  
  Open-source ELT data pipeline platform (MIT for core, with some enterprise features under separate license); 150+ pre-built connectors for syncing data from SaaS apps, databases, and APIs into data warehouses; focused on data integration rather than workflow automation .

- **[ByteChef](https://github.com/bytechefhq/bytechef)**  
  Open-source, low-code, extendable API integration and workflow automation platform (Java-based); designed for integrating organizations or SaaS products with any third-party API; ~200 GitHub stars with active development .

- **[Sequor](https://pypi.org/project/sequor/)**  
  SQL-centric workflow platform for building API integrations (code-first, YAML/Jinja/SQL); fuses API execution with database operations for bidirectional data flow; applies software engineering practices (version control, CI/CD) to integration pipelines; an alternative to black-box SaaS connectors for data teams .

### Additional Strong Open-Source Options

- **Prismatic Components** — Prismatic open-sourced its entire connector library under Apache-2.0 in June 2026; the code synchronizes with production releases and serves as a reference framework for building enterprise connectors (Salesforce, NetSuite, HubSpot) .
- **NocoBase** — AI no-code/low-code platform with data source integration capabilities (MySQL, PostgreSQL, REST API) and workflow engine; Apache 2.0 licensed; better suited for database-intensive integration combined with internal app building .
- **Windmill** — Developer platform that turns scripts into workflows and UIs; open-source alternative to Retool and Temporal with a fast workflow engine and self-hosted PostgreSQL backend.

**Frameworks for building custom systems**: Combine **n8n** for comprehensive workflow automation with 200+ integrations, **Activepieces** for AI-augmented flows with MCP support and beginner-friendly building, **Apache NiFi** for high-throughput data pipeline processing, and **Cenit IO** for a purpose-built open-source iPaaS with ERP integration in a fully self-hosted integration stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- iPaaS platforms handling business data and credentials must comply with applicable privacy regulations and organizational security policies; API keys and OAuth tokens require secure storage and rotation.
- Self-hosted open-source solutions vary significantly in scope—n8n and Activepieces provide broad workflow automation, while Apache NiFi and Airbyte focus on data pipeline integration; choose based on whether the primary need is app-to-app automation or data movement.
- Verify license terms for commercial use; n8n uses the Sustainable Use License (not OSI-approved, with restrictions on resale), Activepieces uses MIT, Cenit IO uses MIT, and Apache NiFi uses Apache 2.0 .

---

**Made for integration engineers, IT operations teams, automation developers, and enterprise architects.**  
Let's make integration platforms more open, controllable, and workflow-ready.
