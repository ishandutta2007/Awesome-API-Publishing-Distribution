# Awesome-API-Publishing-Distribution

A curated list of awesome tools, frameworks, and platforms for publishing, distributing, documenting, and monetizing APIs.

---

## Sector Overview & Market Dynamics

The global API management and developer portal market is estimated at **$7.5B – $9.5B** (projected to exceed **$25B–$35B by the early 2030s** with a ~17–20% CAGR). The sector is **moderately fragmented**: high-volume API gateways, enterprise catalogs, and general lifecycle tooling lean toward consolidation among massive incumbents (such as Postman and SmartBear), whereas the API documentation, developer portal UI, and SDK publishing layer remains vibrantly fragmented with specialized modern challengers (such as Mintlify, Redocly, and Fern) driving rapid innovation.

---

## SaaS Products

| Product | Valuation / Revenue Scale | Pricing (Starting Tier) | Free Tier Limits |
| :--- | :--- | :--- | :--- |
| **Postman** | Valuation: $5.6B (Primary Series D) / Revenue: ~$313M ARR | **Solo Plan:** $9/month (billed annually) or **Team Plan:** $19/user/month (billed annually) | **Free forever:** Strictly 1 user (shared team workspaces require paid upgrade), includes basic collection runs & API client features |
| **SmartBear (SwaggerHub & Stoplight)** | Valuation: ~$1.8B–$2.0B (Vista Equity Partners & Francisco Partners) / Revenue: ~$150M+ ARR | **SwaggerHub Individual:** $19/user/month (billed annually) / **Team:** $29/user/month | **Free forever:** 1 user, up to 3 public APIs, 5 component domains (Stoplight free tier: 1 user, 1 project) |
| **Mintlify** | Valuation: $500M (Series B) / Revenue: ~$23M ARR | **Pro Plan:** $450/month (billed annually, or $540/month billed monthly) | **Starter Plan (Free forever):** Up to 5 editor seats, custom domain, API playground, MCP server, full platform hosting |
| **ReadMe** | Valuation: ~$36M (Series A post-money) / Revenue: ~$8M–$12M ARR | **Pro Plan:** $250/month (billed annually) | **Starter Plan (Free forever):** 1 project, 1 API version, custom domain, bi-directional git sync, interactive API explorer |
| **Speakeasy** | Total Funding: $25.9M (Series A) / Early-stage (<$5M ARR) | **AI Control Plane / Enterprise:** Usage-based / Tailored custom enterprise pricing | **Free Tier:** 1 generated SDK up to 50 API methods; includes a 14-day business trial with full platform access |
| **Fern** | Total Funding: $13M (Series A; Acquired by Postman) / Revenue: ~$3.3M ARR | **Team Plan:** $150/month (billed annually with 25% discount) | **Hobby Plan (Free forever):** Up to 2 team members, 250 AI credits, unlimited documentation viewers |
| **GitBook** | Bootstrapped / Modest funding / Revenue: ~$3.7M–$4M ARR | **Essential Plan:** $65/site/month + $12/user/month (billed annually, or $79/site + $15/user monthly) | **Free forever:** Strictly 1 user, public sites only on `*.gitbook.io` subdomain (no custom domains, basic branding) |
| **Redocly** | Private / Backed by Marbruck Investments (Confidential scale) | **Pro Plan:** $249/month (billed annually, $2,988/year for up to 3 projects) | **Free Trial:** 14-day full-feature trial of Redocly Workspaces; open-source CLI & core renderer are free forever |

---

## Open-Source Tools & Frameworks

Open-source tools and frameworks for generating interactive documentation, developer portals, and client libraries, sorted by GitHub stargazers count:

| Project | Stars | Description | License |
| :--- | :--- | :--- | :--- |
| **[Slate](https://github.com/slatedocs/slate)** | [![GitHub stars](https://img.shields.io/github/stars/slatedocs/slate?style=social&color=white)](https://github.com/slatedocs/slate/stargazers) | Beautiful, responsive three-column static documentation generator for APIs inspired by Stripe and PayPal. | Apache-2.0 |
| **[Backstage](https://github.com/backstage/backstage)** | [![GitHub stars](https://img.shields.io/github/stars/backstage/backstage?style=social&color=white)](https://github.com/backstage/backstage/stargazers) | Spotify's CNCF-stewarded developer portal platform with software catalog, TechDocs, templates, and plugin ecosystem. | Apache-2.0 |
| **[Swagger UI](https://github.com/swagger-api/swagger-ui)** | [![GitHub stars](https://img.shields.io/github/stars/swagger-api/swagger-ui?style=social&color=white)](https://github.com/swagger-api/swagger-ui/stargazers) | Dependency-free collection of HTML, JavaScript, and CSS assets that dynamically generate documentation from an OpenAPI-compliant API. | Apache-2.0 |
| **[Redoc](https://github.com/Redocly/redoc)** | [![GitHub stars](https://img.shields.io/github/stars/Redocly/redoc?style=social&color=white)](https://github.com/Redocly/redoc/stargazers) | OpenAPI/Swagger-generated API reference documentation with responsive three-panel responsive design and clean theme customization. | MIT |
| **[Scalar](https://github.com/scalar/scalar)** | [![GitHub stars](https://img.shields.io/github/stars/scalar/scalar?style=social&color=white)](https://github.com/scalar/scalar/stargazers) | Modern, interactive open-source API documentation, playground, and testing suite for OpenAPI and Swagger specs. | MIT |
| **[Stoplight Elements](https://github.com/stoplightio/elements)** | [![GitHub stars](https://img.shields.io/github/stars/stoplightio/elements?style=social&color=white)](https://github.com/stoplightio/elements/stargazers) | Customizable, embeddable API documentation Web Components and React components powered by OpenAPI specifications. | Apache-2.0 |
| **[Fusio](https://github.com/apioo/fusio)** | [![GitHub stars](https://img.shields.io/github/stars/apioo/fusio?style=social&color=white)](https://github.com/apioo/fusio/stargazers) | Open-source API management platform that offers an integrated developer portal, auto-generated SDKs, and monetization flows. | AGPL-3.0 |
| **[RapiDoc](https://github.com/rapi-doc/RapiDoc)** | [![GitHub stars](https://img.shields.io/github/stars/rapi-doc/RapiDoc?style=social&color=white)](https://github.com/rapi-doc/RapiDoc/stargazers) | Custom-element Web Component for generating interactive OpenAPI documentation with fast rendering and multiple themes. | MIT |
| **[APIPark](https://github.com/APIParkLab/APIPark)** | [![GitHub stars](https://img.shields.io/github/stars/APIParkLab/APIPark?style=social&color=white)](https://github.com/APIParkLab/APIPark/stargazers) | Open-source AI gateway and developer portal for unified API and LLM management, sharing, and distribution. | Apache-2.0 |
| **[WSO2 API Manager](https://github.com/wso2/product-apim)** | [![GitHub stars](https://img.shields.io/github/stars/wso2/product-apim?style=social&color=white)](https://github.com/wso2/product-apim/stargazers) | Enterprise-grade complete lifecycle API management platform featuring a full-fledged developer portal and monetization support. | Apache-2.0 |
| **[Zudoku](https://github.com/zuplo/zudoku)** | [![GitHub stars](https://img.shields.io/github/stars/zuplo/zudoku?style=social&color=white)](https://github.com/zuplo/zudoku/stargazers) | Modern, customizable, open-source API documentation framework built by Zuplo for developers. | Apache-2.0 |
| **[Speakeasy OpenAPI Generator](https://github.com/speakeasy-api/openapi-generation)** | [![GitHub stars](https://img.shields.io/github/stars/speakeasy-api/openapi-generation?style=social&color=white)](https://github.com/speakeasy-api/openapi-generation/stargazers) | Open-source CLI and engine for generating strongly-typed SDKs and client libraries across multiple programming languages. | AGPL-3.0 |

---

## Contributing

Contributions are welcome! Please submit a PR or open an issue to suggest additions or improvements to this list.
