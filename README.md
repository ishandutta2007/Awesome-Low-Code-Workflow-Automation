# Awesome Low-Code Workflow Automation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of leading low-code workflow automation platforms, visual business process automation (BPA) suites, open-source integration engines, and AI workflow orchestration tools.

[![GitHub stars](https://img.shields.io/github/stars/ishandutta2007/Awesome-Low-Code-Workflow-Automation?style=social)](https://github.com/ishandutta2007/Awesome-Low-Code-Workflow-Automation/stargazers)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/ishandutta2007/Awesome-Low-Code-Workflow-Automation/blob/main/README.md#how-to-contribute)

**Low-code workflow automation tools** empower citizen developers, business operations teams, and software engineers to automate business logic, orchestrate distributed microservices, integrate APIs, and build intelligent AI agent workflows with minimal hand-coding. Through drag-and-drop workflow builders, visual canvas flowcharts, trigger-action connectors, and declarative configurations, these platforms streamline cross-application integration, human-in-the-loop approvals, robotic process automation (RPA), and enterprise data pipelines.

---

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS & Hosted Platforms](#saas--hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Choose an Automation Stack](#how-to-choose-an-automation-stack)
- [How to Contribute](#how-to-contribute)
- [Disclaimer & License](#disclaimer--license)

---

## Sector Overview & Market Dynamics

The global low-code development and workflow automation sector is valued between **$25 billion and $35 billion in 2025–2026**, with projections surpassing **$65 billion to $85+ billion by the early 2030s** at an estimated CAGR of 15%–25%.

The sector is **moderately fragmented** across specialized enterprise niches rather than a winner-take-all monopoly: while mega-cap tech giants (Microsoft, Salesforce) capture heavy corporate suite bundling, independent iPaaS leaders (Zapier, Celonis/Make, Workato) dominate citizen automation, and hyper-growth open-source AI-first platforms (n8n, Dify, Activepieces, Langflow) rapidly secure self-hosted and data-sovereign enterprise infrastructure.

---

## SaaS & Hosted Platforms

The table below summarizes leading commercial SaaS and hosted platforms, sorted in descending order by enterprise company size (market capitalization or latest private valuation).

| Platform | Company Size (Valuation / Market Cap) | Starting Paid Pricing | Free Tier / Trial Limits | Key Capabilities & Architecture |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Power Automate](https://powerautomate.microsoft.com/)** | ~$3.97 Trillion (Market Cap) | $15 / user / month (Power Automate Premium) | Free tier available via Microsoft 365 (standard connectors only, capped at 6,000 requests/24h; no RPA); 30-day trial for premium | 1,000+ connectors, cloud flows, desktop RPA, AI Builder, and seamless Microsoft 365 / Azure enterprise ecosystem integration. |
| **[Salesforce Flow Builder](https://www.salesforce.com/)** | ~$190 Billion (Market Cap) | $25 / user / month (Salesforce Platform Starter; Flow Builder included natively) | 30-day free trial on Salesforce Platform; permanently free Developer Edition with full Flow Builder access and 2 active user licenses | Native declarative workflow orchestrator for Salesforce; complex multi-screen flows, record-triggered automations, approvals, and MuleSoft connectivity. |
| **[Make](https://www.make.com/)** *(Celonis)* | $13.0 Billion (Parent Valuation) | $9 / month billed annually ($10.59 / month billed monthly for 10,000 operations) | Permanently free plan with 1,000 operations (credits) / month, 2 active scenarios, 15-minute execution intervals, and 3,500+ connectors | Highly visual scenario canvas, branching routers, iterative loops, data transformations, and built-in error handling routines. |
| **[Workato](https://www.workato.com/)** | $5.7 Billion (Valuation) | ~$10,000 / year (Enterprise base workspace + task consumption packages; small-team add-ons from $75/mo) | No permanent free tier; offers a 14-day gated sandbox trial upon request with demo workspaces | Enterprise-grade iPaaS with low-code recipes, enterprise API gateway, custom connector SDKs, and granular role-based governance. |
| **[n8n Cloud](https://n8n.io/)** | $5.2 Billion (Valuation) | €20 / month billed annually (€24 / month billed monthly for 2,500 executions) | 14-day free trial of Pro tier (no credit card required; 1,000 workflow executions, 5 concurrent runs, 100 AI credits) | Managed hosting of the fair-code engine; unlimited workflows/users, 400+ nodes, JavaScript/Python code nodes, and advanced AI Agent orchestration. |
| **[Zapier](https://zapier.com/)** | $5.0 Billion (Valuation) | $19.99 / month billed annually ($29.99 billed monthly for 750 tasks) | Permanently free plan with 100 tasks / month, single-step Zaps (1 trigger + 1 action), 15-minute update polling, Tables (2,500 records), and Forms | Pioneer citizen-integrator platform connecting 7,000+ business applications; AI Zap generator, webhooks, multi-step actions, and canvas visual builder. |
| **[Appian](https://appian.com/)** | ~$2.8 Billion (Market Cap) | ~$100,000 / year enterprise baseline (Seat-based tiers starting ~$75–$150 / user / month via custom quote) | Permanently free Appian Community Edition (personal learning and development sandbox environment) | Enterprise low-code platform uniting business process management (BPM), data fabrics, case management, and robotic process automation. |
| **[Quickbase](https://www.quickbase.com/)** | ~$1.0+ Billion (Valuation) | $35 / user / month (Team tier, 20 user minimum = $700 / month) | 30-day fully functional free trial with access to sample apps, relational table builders, and Quickbase Pipelines | No-code relational database and operational workflow builder with cross-application Pipelines orchestration and governance. |
| **[Tray.io](https://tray.ai/)** | $600 Million (Valuation) | $695 / month (Team plan baseline; scales by workspace and task consumption) | No permanent free tier; offers a 14-day guided proof-of-concept trial upon sales qualification | Composable enterprise integration platform with visual flow builder, Tray Merlin AI agent orchestrator, and elastic serverless processing. |
| **[Kissflow](https://kissflow.com/)** | $400 Million (Valuation) | $1,500 / month (Basic package covering internal digital workplace & process apps) | No permanent free tier; provides a 14-day product trial and sandbox demo upon request | Unified digital workplace combining no-code workflow forms, multi-level sequential approvals, ticket management, and agile process analytics. |

---

## Open-Source GitHub Projects

The following open-source workflow automation systems, low-code internal tool builders, and orchestration engines are sorted in descending order by **GitHub Star Count**. Each badge links directly to the repository's live stargazers.

| Project | GitHub Stars | Primary Language / Stack | License | Description & Architectural Highlights |
| :--- | :--- | :--- | :--- | :--- |
| **[n8n](https://github.com/n8n-io/n8n)** | [![Stars](https://img.shields.io/github/stars/n8n-io/n8n?style=social&color=white)](https://github.com/n8n-io/n8n/stargazers) | TypeScript / Node.js | Fair-code (Sustainable Use License) | Top self-hosted Zapier/Make alternative. Features visual workflow builder, 400+ pre-built integrations, custom JavaScript/Python execution nodes, and native AI Agent nodes with MCP integration. |
| **[Dify](https://github.com/langgenius/dify)** | [![Stars](https://img.shields.io/github/stars/langgenius/dify?style=social&color=white)](https://github.com/langgenius/dify/stargazers) | Python / TypeScript | Apache-2.0 | Production-ready LLM application and AI workflow development platform. Visual prompt engineering, RAG orchestration, multi-agent collaboration, and low-code flow builders. |
| **[Langflow](https://github.com/langflow-ai/langflow)** | [![Stars](https://img.shields.io/github/stars/langflow-ai/langflow?style=social&color=white)](https://github.com/langflow-ai/langflow/stargazers) | Python / React | MIT | Visual flowchart UI for constructing reactive Multi-Agent applications and LangChain/LlamaIndex automated workflows with drag-and-drop components and API exports. |
| **[NocoDB](https://github.com/nocodb/nocodb)** | [![Stars](https://img.shields.io/github/stars/nocodb/nocodb?style=social&color=white)](https://github.com/nocodb/nocodb/stargazers) | TypeScript / Node.js | AGPL-3.0 | Open-source Airtable alternative that turns relational databases (PostgreSQL, MySQL, SQL Server) into smart low-code spreadsheets with automated webhooks and formula triggers. |
| **[Flowise](https://github.com/FlowiseAI/Flowise)** | [![Stars](https://img.shields.io/github/stars/FlowiseAI/Flowise?style=social&color=white)](https://github.com/FlowiseAI/Flowise/stargazers) | TypeScript / Node.js | MIT | Drag-and-drop visual canvas UI for building custom LLM flows, autonomous AI agents, tool-calling chains, and webhook-driven intelligent automation. |
| **[Huginn](https://github.com/huginn/huginn)** | [![Stars](https://img.shields.io/github/stars/huginn/huginn?style=social&color=white)](https://github.com/huginn/huginn/stargazers) | Ruby | MIT | Hackable self-hosted agent platform to monitor online events, run periodic tasks, scrape website data, parse feeds, and fire automated alerts without SaaS limits. |
| **[Apache Airflow](https://github.com/apache/airflow)** | [![Stars](https://img.shields.io/github/stars/apache/airflow?style=social&color=white)](https://github.com/apache/airflow/stargazers) | Python | Apache-2.0 | De facto industry standard platform to programmatically author, schedule, and monitor complex DAG-based workflows, batch processing jobs, and enterprise data pipelines. |
| **[ToolJet](https://github.com/ToolJet/ToolJet)** | [![Stars](https://img.shields.io/github/stars/ToolJet/ToolJet?style=social&color=white)](https://github.com/ToolJet/ToolJet/stargazers) | TypeScript / React | AGPL-3.0 | Low-code internal application and workflow builder. Visual GUI with 50+ database and API connectors, custom JS/Python logic, and MCP integration for AI assistance. |
| **[Appsmith](https://github.com/appsmithorg/appsmith)** | [![Stars](https://img.shields.io/github/stars/appsmithorg/appsmith?style=social&color=white)](https://github.com/appsmithorg/appsmith/stargazers) | JavaScript / Java | Apache-2.0 | Low-code framework to build admin panels, dashboards, and operational approval workflows. Integrates with 25+ databases, REST/GraphQL APIs, and Git version control. |
| **[Novu](https://github.com/novuhq/novu)** | [![Stars](https://img.shields.io/github/stars/novuhq/novu?style=social&color=white)](https://github.com/novuhq/novu/stargazers) | TypeScript | Apache-2.0 | Open-source notification workflow orchestration engine. Visual management for multi-channel messaging (Email, SMS, Push, In-App, Chat) with digests, delays, and routing logic. |
| **[Directus](https://github.com/directus/directus)** | [![Stars](https://img.shields.io/github/stars/directus/directus?style=social&color=white)](https://github.com/directus/directus/stargazers) | TypeScript / Vue.js | BSL-1.1 / Apache-2.0 | Composable data platform and headless backend that layers a real-time API, admin dashboard, and visual event-driven workflow automation engine over any SQL database. |
| **[Kestra](https://github.com/kestra-io/kestra)** | [![Stars](https://img.shields.io/github/stars/kestra-io/kestra?style=social&color=white)](https://github.com/kestra-io/kestra/stargazers) | Java / Vue.js | Apache-2.0 | Infinitely scalable event-driven orchestration and scheduling engine with declarative YAML workflows, visual canvas editor, and 500+ ecosystem plugins. |
| **[Budibase](https://github.com/Budibase/budibase)** | [![Stars](https://img.shields.io/github/stars/Budibase/budibase?style=social&color=white)](https://github.com/Budibase/budibase/stargazers) | TypeScript / Svelte | GPL-3.0 | All-in-one low-code platform for business applications, forms, and automated business workflows. Connects to PostgreSQL, MySQL, REST APIs, and Docker deployments. |
| **[Activepieces](https://github.com/activepieces/activepieces)** | [![Stars](https://img.shields.io/github/stars/activepieces/activepieces?style=social&color=white)](https://github.com/activepieces/activepieces/stargazers) | TypeScript / Node.js | MIT | AI-first open-source workflow automation suite and Zapier alternative. Features 400+ community pieces, visual builder, human-in-the-loop approvals, and MCP server support. |
| **[Prefect](https://github.com/PrefectHQ/prefect)** | [![Stars](https://img.shields.io/github/stars/PrefectHQ/prefect)?style=social&color=white](https://github.com/PrefectHQ/prefect/stargazers) | Python | Apache-2.0 | Modern resilient workflow orchestration and dataflow management framework. Turn ordinary Python scripts into durable distributed pipelines with automatic retries and alerts. |
| **[Node-RED](https://github.com/node-red/node-red)** | [![Stars](https://img.shields.io/github/stars/node-red/node-red?style=social&color=white)](https://github.com/node-red/node-red/stargazers) | JavaScript / Node.js | Apache-2.0 | Browser-based flow editor for wiring together physical devices, web APIs, IoT gateways, and online services via message-driven node execution. |
| **[Temporal](https://github.com/temporalio/temporal)** | [![Stars](https://img.shields.io/github/stars/temporalio/temporal?style=social&color=white)](https://github.com/temporalio/temporal/stargazers) | Go | MIT | Durable execution system for stateful distributed microservices, human-in-the-loop workflows, long-running sagas, and mission-critical orchestrations. |
| **[Windmill](https://github.com/windmill-labs/windmill)** | [![Stars](https://img.shields.io/github/stars/windmill-labs/windmill?style=social&color=white)](https://github.com/windmill-labs/windmill/stargazers) | Rust / TypeScript | AGPL-3.0 | High-performance developer platform converting scripts (Python, TypeScript, Go, Bash, SQL) into auto-generated webhooks, UIs, and complex asynchronous DAG flows. |
| **[Trigger.dev](https://github.com/triggerdotdev/trigger.dev)** | [![Stars](https://img.shields.io/github/stars/triggerdotdev/trigger.dev?style=social&color=white)](https://github.com/triggerdotdev/trigger.dev/stargazers) | TypeScript | Apache-2.0 | TypeScript-first background jobs and durable workflow orchestration engine. Built-in concurrency control, no timeout limits, real-time logging, and AI agent execution. |
| **[Automatisch](https://github.com/automatisch/automatisch)** | [![Stars](https://img.shields.io/github/stars/automatisch/automatisch?style=social&color=white)](https://github.com/automatisch/automatisch/stargazers) | JavaScript / React | AGPL-3.0 | Self-hosted business workflow automation tool engineered as a privacy-respecting, GDPR-compliant alternative to Zapier without cloud data leakage. |
| **[ILLA Builder](https://github.com/illacloud/illa-builder)** | [![Stars](https://img.shields.io/github/stars/illacloud/illa-builder?style=social&color=white)](https://github.com/illacloud/illa-builder/stargazers) | TypeScript / Go | Apache-2.0 | Low-code internal application and workflow platform to build web panels, CRMs, and triggered automation workflows connecting databases, webhooks, and AI models. |
| **[Robot Framework](https://github.com/robotframework/robotframework)** | [![Stars](https://img.shields.io/github/stars/robotframework/robotframework?style=social&color=white)](https://github.com/robotframework/robotframework/stargazers) | Python | Apache-2.0 | Universal open-source keyword-driven automation framework widely used for acceptance test-driven development (ATDD) and Robotic Process Automation (RPA). |
| **[Apache Camel](https://github.com/apache/camel)** | [![Stars](https://img.shields.io/github/stars/apache/camel?style=social&color=white)](https://github.com/apache/camel/stargazers) | Java | Apache-2.0 | Versatile enterprise integration framework implementing Enterprise Integration Patterns (EIP) with 350+ connectors for messages, APIs, and Kafka queues. |
| **[TagUI](https://github.com/aisingapore/TagUI)** | [![Stars](https://img.shields.io/github/stars/aisingapore/TagUI?style=social&color=white)](https://github.com/aisingapore/TagUI/stargazers) | JavaScript / Python | Apache-2.0 | Command-line RPA tool allowing users to automate desktop applications, web browsing clicks, keyboard input, and document workflows using simple human-readable syntax. |
| **[Apache NiFi](https://github.com/apache/nifi)** | [![Stars](https://img.shields.io/github/stars/apache/nifi?style=social&color=white)](https://github.com/apache/nifi/stargazers) | Java | Apache-2.0 | Visual data logistics platform for automating data routing, transformation, system mediation, and real-time streaming ETL across hybrid multicloud environments. |
| **[Inngest](https://github.com/inngest/inngest)** | [![Stars](https://img.shields.io/github/stars/inngest/inngest?style=social&color=white)](https://github.com/inngest/inngest/stargazers) | Go / TypeScript | Apache-2.0 | Event-driven workflow engine allowing developers to write durable multi-step background functions, retries, and AI agent steps without dedicated worker infra. |
| **[Corteza](https://github.com/cortezaproject/corteza)** | [![Stars](https://img.shields.io/github/stars/cortezaproject/corteza?style=social&color=white)](https://github.com/cortezaproject/corteza/stargazers) | Go / Vue.js | Apache-2.0 | Open-source low-code platform mirroring Salesforce architecture. Includes BPMN-compliant workflow engine, custom CRM templates, and record-triggered triggers. |
| **[RPA Framework](https://github.com/robocorp/rpaframework)** | [![Stars](https://img.shields.io/github/stars/robocorp/rpaframework?style=social&color=white)](https://github.com/robocorp/rpaframework/stargazers) | Python | Apache-2.0 | Standard library collection for Python and Robot Framework supporting browser manipulation, PDF data extraction, desktop GUI automation, and MS Office parsing. |
| **[ByteChef](https://github.com/bytechefhq/bytechef)** | [![Stars](https://img.shields.io/github/stars/bytechefhq/bytechef?style=social&color=white)](https://github.com/bytechefhq/bytechef/stargazers) | Java / TypeScript | Apache-2.0 | Open-source API integration and workflow automation engine. Visual drag-and-drop builder with custom code step blocks in Java, JS, Python, and Ruby. |
| **[Joget](https://github.com/jogetworkflow/jw-community)** | [![Stars](https://img.shields.io/github/stars/jogetworkflow/jw-community?style=social&color=white)](https://github.com/jogetworkflow/jw-community/stargazers) | Java | GPL-3.0 | Low-code/no-code enterprise application builder combining business process management, digital form routing, approval automation, and AI plugins. |

---

## How to Choose an Automation Stack

| Requirement | Recommended Options |
| :--- | :--- |
| **Visual Citizen Automation (Zapier Alternatives)** | [n8n](https://github.com/n8n-io/n8n), [Activepieces](https://github.com/activepieces/activepieces), [Automatisch](https://github.com/automatisch/automatisch) |
| **AI Agents & Multi-Agent LLM Orchestration** | [Dify](https://github.com/langgenius/dify), [Langflow](https://github.com/langflow-ai/langflow), [Flowise](https://github.com/FlowiseAI/Flowise), [n8n](https://github.com/n8n-io/n8n) |
| **Internal Tools & Low-Code Dashboarding** | [Appsmith](https://github.com/appsmithorg/appsmith), [ToolJet](https://github.com/ToolJet/ToolJet), [Budibase](https://github.com/Budibase/budibase), [ILLA Builder](https://github.com/illacloud/illa-builder) |
| **Database & Headless Backend Automation** | [NocoDB](https://github.com/nocodb/nocodb), [Directus](https://github.com/directus/directus) |
| **Developer-First Scripts & High-Performance Jobs** | [Windmill](https://github.com/windmill-labs/windmill), [Trigger.dev](https://github.com/triggerdotdev/trigger.dev), [Inngest](https://github.com/inngest/inngest) |
| **Mission-Critical Durable Microservices** | [Temporal](https://github.com/temporalio/temporal) |
| **Large-Scale Data Pipelines & DAG Scheduling** | [Apache Airflow](https://github.com/apache/airflow), [Prefect](https://github.com/PrefectHQ/prefect), [Kestra](https://github.com/kestra-io/kestra), [Apache NiFi](https://github.com/apache/nifi) |
| **Robotic Process Automation (Desktop & Web RPA)** | [Robot Framework](https://github.com/robotframework/robotframework), [TagUI](https://github.com/aisingapore/TagUI), [RPA Framework](https://github.com/robocorp/rpaframework) |
| **IoT & Event-Driven Webhooks** | [Node-RED](https://github.com/node-red/node-red), [Novu](https://github.com/novuhq/novu) |

---

## How to Contribute

Contributions are warmly encouraged! To propose a new SaaS platform, open-source project, or factual correction:

1. **Fork** this repository.
2. Edit `README.md` to insert the project according to the proper section and sorting criteria (Descending by valuation for SaaS; Descending by GitHub star count with social badge for Open-Source).
3. Ensure entries adhere to objective, factual technical descriptions without promotional hyperbole.
4. Open a **Pull Request** detailing your additions.

---

## Disclaimer & License

- This is a community-curated technical index intended for software engineers, automation architects, and operational leadership. Mention does not constitute an explicit endorsement.
- All trademarks and brand assets are the property of their respective owners.
- To the extent possible under law, this work is dedicated under the [Creative Commons CC0 1.0 Universal License](LICENSE).
