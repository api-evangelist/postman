# Postman (postman)

Postman is the world's leading API platform, used by 35+ million developers to design, build, test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections, Workspaces, the API Client, Spec Hub, Mock Servers, Monitors, the Postman CLI, Newman, Flows, AI Agent Builder, the Postman MCP Server and MCP Generator, API Governance, the Private API Network, Live Collections, Insights, and a public Postman API Network with millions of public workspaces.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/postman/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party
- **Network Tier:** 1 (Top-tier API platform provider)

## Tags

AI Agent Builder, AI Agents, API Catalog, API Client, API Design, API Development, API Documentation, API Governance, API Lifecycle, API Monitoring, API Network, API Platform, API Testing, Audit Logs, Automation, CI/CD, Collaboration, Collections, Compliance, Discovery, Environments, Flows, GraphQL, gRPC, HTTP, Insights, MCP, MCP Generator, Mock Servers, Mocking, Monitors, Newman, OpenAPI, Platform, Private API Network, Public API Network, Secret Scanning, Spec Hub, Specifications, SSO, Testing, Vault, WebSocket, Workflows, Workspaces

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-15

## APIs

### Postman

The single platform for collaborative API development used by 35+ million developers. Covers the entire API lifecycle - design, build, test, document, mock, monitor, and govern - and now includes first-class AI Agent Builder, MCP Generator, and Flows for orchestrating multi-step API workflows for AI agents.

**Human URL:** https://www.postman.com/
**Base URL:** https://api.getpostman.com

#### Properties

- [Documentation](https://www.postman.com/)
- [GettingStarted](https://learning.postman.com/docs/developer/postman-api/intro-api/)
- [Authentication](https://learning.postman.com/docs/developer/postman-api/authentication/)
- [RateLimits](https://learning.postman.com/docs/developer/postman-api/postman-api-rate-limits/)
- [PostmanCollection](https://www.postman.com/postman/postman-public-workspace/documentation/i2uqzpp/postman-api)
- [SchemaCatalog](https://schema.postman.com/)
- [AsyncAPI](asyncapi/postman-webhooks-asyncapi.yml)
- [JSONSchema - Collection](json-schema/postman-collection-schema.json)
- [JSONSchema - Environment](json-schema/postman-environment-schema.json)
- [JSONSchema - Workspace](json-schema/postman-workspace-schema.json)
- [JSON-LD Context](json-ld/postman-context.yml)
- [JSONStructure - Collection](json-structure/postman-collection-structure.json)
- [JSONStructure - Workspace](json-structure/postman-workspace-structure.json)
- [JSONStructure - Monitor](json-structure/postman-monitor-structure.json)
- [Naftiko Capability - Postman APIs](capabilities/shared/postman-apis.yaml)
- [Naftiko Workflow - API Development Lifecycle](capabilities/api-development-lifecycle.yaml)
- [Naftiko Workflow - Governance](capabilities/governance.yaml)
- [Naftiko Workflow - MCP Publishing](capabilities/mcp-publishing.yaml)
- [Spectral Ruleset](rules/postman-rules.yml)
- [Vocabulary](vocabulary/postman-vocabulary.yml)
- [Plans and Pricing](plans/postman-plans-pricing.yml)
- [Rate Limits Policy](rate-limits/postman-rate-limits.yml)
- [FinOps (FOCUS 1.3 Aligned)](finops/postman-finops.yml)

### Postman Collections API

Programmatically create, read, update, and delete Postman Collections including requests, folders, scripts, and environments. Powers CI/CD integration, sync, and collection generation pipelines.

**Base URL:** https://api.getpostman.com

- [OpenAPI](openapi/postman-collections-api-openapi.yml)
- [Example - Get All Collections](examples/postman-get-all-collections-example.json)

### Postman Workspaces API

Manage personal, team, partner, public, and private workspaces. Control visibility, membership, roles, and the elements (collections, environments, mocks, monitors, APIs) attached to each workspace.

**Base URL:** https://api.getpostman.com

- [OpenAPI](openapi/postman-workspaces-api-openapi.yml)

### Postman Environments API

Programmatic management of Postman environments and global variables, including secret variables stored in the Postman Vault, so you can scope work to dev/staging/prod environments.

**Base URL:** https://api.getpostman.com

- [OpenAPI](openapi/postman-environments-api-openapi.yml)

### Postman Mock Servers API

CRUD operations on mock servers, mock responses, visibility, and mock call logs - used to simulate API behavior during API-first development and to share reference implementations with partners.

**Base URL:** https://api.getpostman.com

- [OpenAPI](openapi/postman-mock-servers-api-openapi.yml)
- [Example - Create Mock Server](examples/postman-create-mock-server-example.json)

### Postman Monitors API

Runs Postman Collections on a recurring schedule to validate API health, performance, and contract conformance. Surfaces metrics, test results, and notification webhooks for incident response.

**Base URL:** https://api.getpostman.com

- [OpenAPI](openapi/postman-monitors-api-openapi.yml)
- [Example - Run Monitor](examples/postman-run-monitor-example.json)

### Postman APIs / Spec Hub API

Manages API definitions, versions, specifications, and linked elements. Supports OpenAPI 3, AsyncAPI, GraphQL, gRPC/Protobuf, RAML, WSDL, and SOAP definitions for design-first API workflows.

**Base URL:** https://api.getpostman.com

- [OpenAPI](openapi/postman-apis-api-openapi.yml)
- [Example - Create API](examples/postman-create-api-spec-example.json)

### Postman Private API Network API

Manages your internal API catalog - organizing folders, approving submissions, controlling visibility, and integrating CI/CD pipelines that publish APIs into your developer portal.

**Base URL:** https://api.getpostman.com

- [OpenAPI](openapi/postman-private-api-network-api-openapi.yml)

### Postman Webhooks API

Creates webhooks that trigger collection runs with custom payloads, integrating Postman with external systems (GitHub, Slack, custom triggers) for event-driven automation.

**Base URL:** https://api.getpostman.com

- [OpenAPI](openapi/postman-webhooks-api-openapi.yml)
- [AsyncAPI](asyncapi/postman-webhooks-asyncapi.yml)

### Postman Collection Runs API

Programmatically launches collection runs, retrieves run results, and powers integration with Newman, the Postman CLI, and CI/CD pipelines for automated test execution.

**Base URL:** https://api.getpostman.com

- [OpenAPI](openapi/postman-collection-runs-api-openapi.yml)

### Postman Tags API

Manages tags applied to APIs, collections, and workspaces for organization, governance reporting, and discoverability across the Private and Public API Networks.

**Base URL:** https://api.getpostman.com

- [OpenAPI](openapi/postman-tags-api-openapi.yml)

### Postman Audit Logs API

Enterprise-only API exposing team audit events (user actions, configuration changes, security events) for SIEM ingestion and compliance reporting (SOC 2, GDPR, ISO).

**Base URL:** https://api.getpostman.com

- [OpenAPI](openapi/postman-audit-logs-api-openapi.yml)
- [Example - Audit Logs](examples/postman-audit-logs-example.json)

### Postman Secret Scanner API

Manages detected secrets and resolves leaked credentials found in collections, environments, and other elements - part of Postman's API governance and security posture suite.

**Base URL:** https://api.getpostman.com

- [OpenAPI](openapi/postman-secret-scanner-api-openapi.yml)

### Postman Billing API

Account billing information, seat allocation, and resource usage so finance and FinOps teams can integrate Postman consumption into chargeback / showback reporting.

**Base URL:** https://api.getpostman.com

### Postman SCIM API

SCIM 2.0 user / group provisioning from your identity provider (Okta, OneLogin, Azure AD, Ping) into Postman team accounts.

**Base URL:** https://api.getpostman.com/scim/v2

### Postman MCP Server

Exposes Postman Collections, environments, and workspaces over Anthropic's Model Context Protocol so AI agents (Claude, Cursor, custom LLM clients) can reason over and execute APIs directly from your Postman library.

**Source:** https://github.com/postmanlabs/postman-mcp-server

### Postman Flows

Visual workflow builder that chains API calls, transformations, and conditional logic. Flows are executable, debuggable, and cloneable documentation that powers AI agent orchestration and partner integrations.

**Source:** https://www.postman.com/product/flows/

## Pricing Plans (reconciled)

| Plan | Price | Seat | AI Credits / mo | Monitoring req / mo | API calls / mo |
|------|-------|------|------------------|---------------------|----------------|
| Free | $0 | 1 user | 50 | 1,000 | 10,000 |
| Solo | $9 / month, billed annually | 1 user | 400 | 10,000 | 100,000 |
| Team | $19 / user / month, billed annually | unlimited | 400 / user | 10,000 | 1,000,000 |
| Enterprise | $49 / user / month, billed annually | unlimited | 800 / user (pooled) | 10,000 | 10,000,000 |

Source: [postman.com/pricing](https://www.postman.com/pricing/).

## Rate Limits (reconciled)

- **Per-key burst:** 300 requests / minute (`RateLimit-Policy: 300;w=60`).
- **Monthly Postman API calls:** 10k Free / 100k Solo / 1M Team / 10M Enterprise.
- **Monitoring requests:** 1k Free / 10k Solo, Team, Enterprise.
- **Headers:** `RateLimit-Limit`, `RateLimit-Remaining`, `RateLimit-Reset`, `RateLimit-Policy`, `RetryAfter`, plus `X-RateLimit-*-Month` for monthly quota state.

Source: [Postman API rate limits](https://learning.postman.com/docs/developer/postman-api/postman-api-rate-limits/).

## Compliance

SOC 2 Type II, SOC 3, PCI DSS, GDPR, CCPA, Cloud Security Alliance STAR, EU-U.S. Data Privacy Framework (and UK/Swiss extensions). See the [Postman Customer Trust Portal](https://security.postman.com/) for downloadable evidence.

## Tooling and GitHub

Top repositories at [github.com/postmanlabs](https://github.com/postmanlabs):

- [newman](https://github.com/postmanlabs/newman) - command-line collection runner (7.2k stars).
- [postman-app-support](https://github.com/postmanlabs/postman-app-support) - desktop app issue tracker and support.
- [openapi-to-postman](https://github.com/postmanlabs/openapi-to-postman) - convert OpenAPI 3.0 to Postman v2.
- [postman-code-generators](https://github.com/postmanlabs/postman-code-generators) - generate code in 20+ languages.
- [postman-collection](https://github.com/postmanlabs/postman-collection) - JS SDK for Postman Collections.
- [postman-runtime](https://github.com/postmanlabs/postman-runtime) - request and script execution engine.
- [postman-mcp-server](https://github.com/postmanlabs/postman-mcp-server) - first-party MCP server.
- [postman-insights-agent](https://github.com/postmanlabs/postman-insights-agent) - production API observability agent.
- [schemas](https://github.com/postmanlabs/schemas) - canonical JSON Schemas (also at [schema.postman.com](https://schema.postman.com/)).
- [postman-sandbox](https://github.com/postmanlabs/postman-sandbox) - script sandbox.
- [postman-flows](https://github.com/postmanlabs/postman-flows) - Flows public progress repo.
- [postman-collection-transformer](https://github.com/postmanlabs/postman-collection-transformer) - v1 to v2 conversion.
- [httpbin](https://github.com/postmanlabs/httpbin) - reference HTTP testing service (13.5k stars).

## Common Properties

- [Website](https://www.postman.com/)
- [Pricing](https://www.postman.com/pricing/)
- [Knowledgebase](https://www.postman.com/learn/)
- [Documentation](https://learning.postman.com/)
- [Getting Started](https://learning.postman.com/docs/developer/postman-api/intro-api/)
- [Authentication](https://learning.postman.com/docs/developer/postman-api/authentication/)
- [Rate Limits](https://learning.postman.com/docs/developer/postman-api/postman-api-rate-limits/)
- [Blog](https://blog.postman.com/)
- [Templates](https://www.postman.com/templates/)
- [Support](https://support.postman.com/hc/en-us)
- [Release Notes](https://www.postman.com/release-notes/)
- [Status](https://status.postman.com/)
- [Events](https://www.postman.com/events/)
- [Postman CLI](https://learning.postman.com/docs/postman-cli/postman-cli-installation/)
- [Newman CLI](https://github.com/postmanlabs/newman)
- [Postman Partner Program](https://www.postman.com/partner-program/)
- [Case Studies](https://www.postman.com/case-studies/)
- [Terms of Service](https://www.postman.com/legal/terms/)
- [Privacy Policy](https://www.postman.com/legal/privacy-policy/)
- [Trust Center](https://www.postman.com/trust/)
- [Customer Trust Portal](https://security.postman.com/)
- [Compliance Certifications](https://www.postman.com/trust/compliance/)
- [VS Code Extension](https://marketplace.visualstudio.com/items?itemName=Postman.postman-for-vscode)
- [Public API Network](https://www.postman.com/explore)
- [Postman MCP Network](https://www.postman.com/explore/mcp)
- [Postman Academy](https://academy.postman.com/)
- [Schema Catalog](https://schema.postman.com/)
- [AI Agent Builder](https://www.postman.com/product/ai-agent-builder/)
- [MCP Server](https://github.com/postmanlabs/postman-mcp-server)
- [Flows](https://www.postman.com/product/flows/)
- [API Governance](https://www.postman.com/product/api-governance/)
- [API Catalog](https://www.postman.com/product/api-catalog/)
- [Workspaces](https://www.postman.com/product/workspaces/)
- [Sign Up](https://identity.getpostman.com/signup)
- [Login](https://identity.getpostman.com/login)
- [Console](https://go.postman.co/)
- [GitHub Organization](https://github.com/postmanlabs)
- [LinkedIn](https://www.linkedin.com/company/postman-platform)
- [Twitter / X](https://twitter.com/getpostman)
- [Discord](https://discord.com/invite/bKjz3CXbB6)
- [YouTube](https://www.youtube.com/c/Postman)
- [Community Forum](https://community.postman.com/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/postman)

## Maintainers

- Kin Lane &lt;kin@apievangelist.com&gt;
- Postman &lt;help@postman.com&gt; ([postman.com](https://www.postman.com))
