# Awesome-API-Publishing-Distribution

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **the open-source side is much thinner than your list implies**, and one SaaS entry has no verifiable pricing.



## What the search results actually contain



**SaaS pricing (usable):**

- **Mintlify**: Starter **$0/month** (5 editor seats, full platform, custom domain, MCP server, API playground); Pro **$450/month annual** or $540 monthly (unlimited editors, Agent, Assistant, Automations, preview deployments); Enterprise contact .

- **Redocly**: Pro **$249/month annual** ($2,988/year, 3 projects); Scale **$729/month annual** ($8,748/year, 10 projects); Enterprise custom. Unlimited seats and readers on every plan. AI Assistant and MCP server included in beta on all plans .

- **Fern**: Hobby **$0/month** (2 team members, 250 AI credits); Team **$150/month** (25% annual discount); Enterprise custom with SSO, RBAC, self-hosting .

- **Speakeasy**: **Free tier** (one SDK up to 50 API methods, 14-day business trial); hosted platform is **Enterprise-only with "Tailored" pricing**. The SDK generator was open-sourced under **AGPL-3.0** on September 17, 2026 as `speakeasy-api/openapi-generation` . Pay-as-you-go pricing exists for the AI control plane (tokens under management, MCP gateway egress) .



**No pricing surfaced for:**

- **ReadMe** (not in results)

- **SwaggerHub** (not in results)

- **Stoplight** (not in results)

- **GitBook** (not in results)

- **Postman API Distribution** (not in results as a distribution product)



**Open-source tools (usable):**

- **Backstage**: Apache 2.0, CNCF-stewarded, software catalog + scaffolder + TechDocs + plugin system . **Not in your list**, but it is the dominant open-source developer portal.

- **Markline**: Open-source, self-hostable docs framework with first-class OpenAPI, full-text search, interactive API playground; positioned as an "open alternative to Scalar and Mintlify" .

- **Scribe**: Open-source Mintlify alternative built on Next.js App Router, with ApiEndpoint component, CodeTabs, Steps, Cards, full-text search, version switcher, single config file .

- **Tome**: Open-source docs platform generating sites from Markdown/MDX with full-text search, API reference, AI chat; self-hosted or Tome Cloud; **early-stage, limited adoption signals** .

- **RapiDoc Portal**: Open-source portal for publishing API docs with auth, protected content, OAuth try-it, Markdown/MDX/Markdoc support .

- **WSO2 API Manager**: Apache 2.0, full lifecycle API management server including developer portal with try-it console, auto-generated SDKs, self-service key management .

- **Fusio**: Open-source API management platform with developer portal, SDK automation, API monetization, MCP integration .

- **OpenDevX**: Open-source framework for building API developer exchanges and marketplaces; integrates with API gateways and meshes; monetization with billing connectors . **Older project (v1.0.1, 2021)**—treat as reference architecture, not active production tool.



**What is missing:**

- **No star counts** for any open-source project.

- **No revenue or valuation data** for any vendor.

- **No pricing for ReadMe, SwaggerHub, Stoplight, GitBook, or Postman.**



## What I recommend



**Remove or reframe the SaaS entries without pricing.** If you list ReadMe, SwaggerHub, Stoplight, GitBook, and Postman, mark them **"quote-only"**—do not fabricate figures. Only Mintlify, Redocly, and Fern have verified public pricing from the results.



**The open-source section should be honest about what exists:**



| Project | License | What it actually does | Status |

|---|---|---|---|

| **Backstage** | Apache 2.0 | Developer portal: catalog, scaffolder, TechDocs, plugins  | Mature, CNCF-stewarded |

| **Markline** | Open source | Self-hostable docs with OpenAPI playground, search  | Active |

| **Scribe** | Open source | Mintlify alternative, Next.js, API components  | Active |

| **RapiDoc Portal** | Open source | API docs portal with auth and OAuth try-it  | Active |

| **WSO2 API Manager** | Apache 2.0 | Full APIM server with developer portal  | Mature |

| **Fusio** | Open source | API management with portal, SDK gen, monetization  | Active |

| **Tome** | Open source | Docs publishing with AI chat  | **Early-stage** |

| **OpenDevX** | Open source | Developer exchange framework  | **Stale (2021)** |



**Drop "Postman API Distribution" as a category.** Postman is an API client and platform; its distribution story is publishing collections, not a developer portal or docs site. If you want a Postman-adjacent entry, list it in the SaaS section with **"pricing not surfaced"**—not as an open-source alternative.



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate star counts, pricing for ReadMe/SwaggerHub/Stoplight/GitBook, or present OpenDevX as actively maintained.
