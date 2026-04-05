<!-- copilot-context-manager:begin -->
<!-- Active context: No Prompt — updated 2026-04-05T12:01:48.265Z -->



<!-- copilot-context-manager:end -->
<!-- github-copilot-toolbox:mcp-skills-awareness-begin -->

### MCP & Skills awareness (GitHub Copilot Toolbox)

_Last synced: 2026-04-05T12:01:53.949Z._

- **Full report:** `.github/copilot-toolbox-mcp-skills-awareness.md` in this workspace (auto-overwritten on each scan). Use it as ground truth for configured servers and skill folders.
- **MCP:** For **live tools**, use **Copilot Chat → Agent** and **trust/start** the right servers in the MCP UI.
- **When the user’s task matches a server** (e.g. “open this Confluence page” and a **Confluence** / **Atlassian** MCP is listed), **prefer that server id** and plan on Agent + MCP for actions—not only file search.
- **Skills:** Folders below contain `SKILL.md`; attach or cite paths in chat when relevant.

#### Workspace MCP

- `c:\Users\jacob\Documents\GitHub\Smart-AI-Resume-Analyzer\.vscode\mcp.json` _(workspace: Smart-AI-Resume-Analyzer)_ — _file missing_

_No active workspace servers in mcp.json._

#### User MCP

- `C:\Users\jacob\AppData\Roaming\Code\User\mcp.json` — _servers defined_

| Server id | Kind | Detail |
|-----------|------|--------|
| io.github.github/github-mcp-server | http | https://api.githubcopilot.com/mcp/ |
| microsoft/markitdown | stdio | uvx markitdown-mcp@0.0.1a4 |
| io.github.wonderwhy-er/desktop-commander | stdio | npx --registry https://registry.npmjs.org @wonderwhy-er/desktop-commander@0.2.38 |
| com.microsoft/azure | stdio | dnx Azure.Mcp@2.0.0-beta.31 --yes -- server start |
| io.github.f/prompts.chat-mcp | stdio | npx @fkadev/prompts.chat-mcp@1.0.9 |
| io.github.microsoft/awesome-copilot | stdio | docker run -i --rm ghcr.io/microsoft/mcp-dotnet-samples/awesome-copilot:1.0.2026032705 |
| microsoft/playwright-mcp | stdio | npx @playwright/mcp@latest |
| com.microsoft/nuget | stdio | dnx NuGet.Mcp.Server@1.2.3 --yes --source https://api.nuget.org/v3/index.json |
| microsoftdocs/mcp | http | https://learn.microsoft.com/api/mcp |
| microsoft-learn | http | https://learn.microsoft.com/api/mcp |
| azure-ai-foundry/mcp-foundry | stdio | uvx --prerelease=allow --from git+https://github.com/azure-ai-foundry/mcp-foundry.git run-azure-ai-foundry-mcp --envFile ${input:env_file_path} |

#### Project skills

_None found (or no workspace open)._

#### User skills

- **appinsights-instrumentation** — `C:\Users\jacob\.agents\skills\appinsights-instrumentation` — Guidance for instrumenting webapps with Azure Application Insights. Provides telemetry patterns, SDK setup, and configuration references. WHEN: how to instrument app, App Insights SDK, telemetry patterns, what is App Ins

- **azure-ai** — `C:\Users\jacob\.agents\skills\azure-ai` — Use for Azure AI: Search, Speech, OpenAI, Document Intelligence. Helps with search, vector/hybrid search, speech-to-text, text-to-speech, transcription, OCR. WHEN: AI Search, query search, vector search, hybrid search, s

- **azure-aigateway** — `C:\Users\jacob\.agents\skills\azure-aigateway` — Configure Azure API Management as an AI Gateway for AI models, MCP tools, and agents. WHEN: semantic caching, token limit, content safety, load balancing, AI model governance, MCP rate limiting, jailbreak detection, add 

- **azure-cloud-migrate** — `C:\Users\jacob\.agents\skills\azure-cloud-migrate` — Assess and migrate cross-cloud workloads to Azure with migration reports and code conversion guidance. Supports AWS, GCP, and other providers. WHEN: migrate Lambda to Azure Functions, migrate AWS to Azure, Lambda migrati

- **azure-compliance** — `C:\Users\jacob\.agents\skills\azure-compliance` — Run Azure compliance and security audits with azqr plus Key Vault expiration checks. Covers best-practice assessment, resource review, policy/compliance validation, and security posture checks. WHEN: compliance scan, sec

- **azure-compute** — `C:\Users\jacob\.agents\skills\azure-compute` — Azure VM and VMSS router for recommendations, pricing, autoscale, orchestration, and connectivity troubleshooting. WHEN: Azure VM, VMSS, scale set, recommend, compare, server, website, burstable, lightweight, VM family, 

- **azure-cost** — `C:\Users\jacob\.agents\skills\azure-cost` — Unified Azure cost management: query historical costs, forecast future spending, and optimize to reduce waste. WHEN: \"Azure costs\", \"Azure spending\", \"Azure bill\", \"cost breakdown\", \"cost by service\", \"cost by

- **azure-deploy** — `C:\Users\jacob\.agents\skills\azure-deploy` — Execute Azure deployments for ALREADY-PREPARED applications that have existing .azure/deployment-plan.md and infrastructure files. DO NOT use this skill when the user asks to CREATE a new application — use azure-prepare 

- **azure-diagnostics** — `C:\Users\jacob\.agents\skills\azure-diagnostics` — Debug Azure production issues on Azure using AppLens, Azure Monitor, resource health, and safe triage. WHEN: debug production issues, troubleshoot container apps, troubleshoot functions, troubleshoot AKS, kubectl cannot 

- **azure-enterprise-infra-planner** — `C:\Users\jacob\.agents\skills\azure-enterprise-infra-planner` — Architect and provision enterprise Azure infrastructure from workload descriptions. For cloud architects and platform engineers planning networking, identity, security, compliance, and multi-resource topologies with WAF 

- **azure-hosted-copilot-sdk** — `C:\Users\jacob\.agents\skills\azure-hosted-copilot-sdk` — Build, deploy, modify GitHub Copilot SDK apps on Azure. PREFER OVER azure-prepare when codebase contains copilot-sdk markers. WHEN: copilot SDK, @github/copilot-sdk, copilot-powered app, deploy copilot app, add feature, 

- **azure-kubernetes** — `C:\Users\jacob\.agents\skills\azure-kubernetes` — Plan, create, and configure production-ready Azure Kubernetes Service (AKS) clusters. Covers Day-0 checklist, SKU selection (Automatic vs Standard), networking options (private API server, Azure CNI Overlay, egress confi

- **azure-kusto** — `C:\Users\jacob\.agents\skills\azure-kusto` — Query and analyze data in Azure Data Explorer (Kusto/ADX) using KQL for log analytics, telemetry, and time series analysis. WHEN: KQL queries, Kusto database queries, Azure Data Explorer, ADX clusters, log analytics, tim

- **azure-messaging** — `C:\Users\jacob\.agents\skills\azure-messaging` — Troubleshoot and resolve issues with Azure Messaging SDKs for Event Hubs and Service Bus. Covers connection failures, authentication errors, message processing issues, and SDK configuration problems. WHEN: event hub SDK 

- **azure-prepare** — `C:\Users\jacob\.agents\skills\azure-prepare` — Prepare Azure apps for deployment (infra Bicep/Terraform, azure.yaml, Dockerfiles). Use for create/modernize or create+deploy; not cross-cloud migration (use azure-cloud-migrate). WHEN: \"create app\", \"build web app\",

- **azure-quotas** — `C:\Users\jacob\.agents\skills\azure-quotas` — Check/manage Azure quotas and usage across providers. For deployment planning, capacity validation, region selection. WHEN: \"check quotas\", \"service limits\", \"current usage\", \"request quota increase\", \"quota exc

- **azure-rbac** — `C:\Users\jacob\.agents\skills\azure-rbac` — Helps users find the right Azure RBAC role for an identity with least privilege access, then generate CLI commands and Bicep code to assign it. Also provides guidance on permissions required to grant roles. WHEN: bicep f

- **azure-resource-lookup** — `C:\Users\jacob\.agents\skills\azure-resource-lookup` — List, find, and show Azure resources across subscriptions or resource groups. Handles prompts like \"list websites\", \"list virtual machines\", \"list my VMs\", \"show storage accounts\", \"find container apps\", and \"

- **azure-resource-visualizer** — `C:\Users\jacob\.agents\skills\azure-resource-visualizer` — Analyze Azure resource groups and generate detailed Mermaid architecture diagrams showing the relationships between individual resources. WHEN: create architecture diagram, visualize Azure resources, show resource relati

- **azure-storage** — `C:\Users\jacob\.agents\skills\azure-storage` — Azure Storage Services including Blob Storage, File Shares, Queue Storage, Table Storage, and Data Lake. Provides object storage, SMB file shares, async messaging, NoSQL key-value, and big data analytics capabilities. In

- **azure-upgrade** — `C:\Users\jacob\.agents\skills\azure-upgrade` — Assess and upgrade Azure workloads between plans, tiers, or SKUs within Azure. Generates assessment reports and automates upgrade steps. WHEN: upgrade Consumption to Flex Consumption, upgrade Azure Functions plan, migrat

- **azure-validate** — `C:\Users\jacob\.agents\skills\azure-validate` — Pre-deployment validation for Azure readiness. Run deep checks on configuration, infrastructure (Bicep or Terraform), RBAC role assignments, managed identity permissions, and prerequisites before deploying. WHEN: validat

- **entra-app-registration** — `C:\Users\jacob\.agents\skills\entra-app-registration` — Guides Microsoft Entra ID app registration, OAuth 2.0 authentication, and MSAL integration. USE FOR: create app registration, register Azure AD app, configure OAuth, set up authentication, add API permissions, generate s

- **microsoft-foundry** — `C:\Users\jacob\.agents\skills\microsoft-foundry` — Deploy, evaluate, and manage Foundry agents end-to-end: Docker build, ACR push, hosted/prompt agent create, container start, batch eval, prompt optimization, prompt optimizer workflows, agent.yaml, dataset curation from

<!-- github-copilot-toolbox:mcp-skills-awareness-end -->
