---
api_specs:
- filename: browserless-browser-rest-apis-api-openapi.yml
  format: yaml
  label: Browserless Browser REST APIs API
  slug: browserless-browser-rest-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browserless/openapi/browserless-browser-rest-apis-api-openapi.yml
- filename: browserless-management-rest-apis-api-openapi.yml
  format: yaml
  label: Browserless Management REST APIs API
  slug: browserless-management-rest-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browserless/openapi/browserless-management-rest-apis-api-openapi.yml
- filename: browserless-agent-api-openapi.yml
  format: yaml
  label: Browserless Agent API
  slug: browserless-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browserless/openapi/browserless-agent-api-openapi.yml
- filename: browserless-bql-execution-api-openapi.yml
  format: yaml
  label: Browserless BQL Execution API
  slug: browserless-bql-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browserless/openapi/browserless-bql-execution-api-openapi.yml
- filename: browserless-browser-management-api-openapi.yml
  format: yaml
  label: Browserless Browser Management API
  slug: browserless-browser-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browserless/openapi/browserless-browser-management-api-openapi.yml
- filename: browserless-cdp-devtools-connections-api-openapi.yml
  format: yaml
  label: Browserless CDP & DevTools Connections API
  slug: browserless-cdp-devtools-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browserless/openapi/browserless-cdp-devtools-connections-api-openapi.yml
- filename: browserless-chrome-licensed-build-api-openapi.yml
  format: yaml
  label: Browserless Chrome (licensed build) API
  slug: browserless-chrome-licensed-build-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browserless/openapi/browserless-chrome-licensed-build-api-openapi.yml
- filename: browserless-crawling-api-openapi.yml
  format: yaml
  label: Browserless Crawling API
  slug: browserless-crawling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browserless/openapi/browserless-crawling-api-openapi.yml
- filename: browserless-functions-downloads-api-openapi.yml
  format: yaml
  label: Browserless Functions & Downloads API
  slug: browserless-functions-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browserless/openapi/browserless-functions-downloads-api-openapi.yml
- filename: browserless-integrations-api-openapi.yml
  format: yaml
  label: Browserless Integrations API
  slug: browserless-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browserless/openapi/browserless-integrations-api-openapi.yml
- filename: browserless-platform-skills-api-openapi.yml
  format: yaml
  label: Browserless Platform / Skills API
  slug: browserless-platform-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browserless/openapi/browserless-platform-skills-api-openapi.yml
- filename: browserless-profiles-api-openapi.yml
  format: yaml
  label: Browserless Profiles API
  slug: browserless-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browserless/openapi/browserless-profiles-api-openapi.yml
- filename: browserless-proxy-api-openapi.yml
  format: yaml
  label: Browserless Proxy API
  slug: browserless-proxy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browserless/openapi/browserless-proxy-api-openapi.yml
- filename: browserless-scraping-content-api-openapi.yml
  format: yaml
  label: Browserless Scraping & Content API
  slug: browserless-scraping-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browserless/openapi/browserless-scraping-content-api-openapi.yml
- filename: browserless-screenshots-pdfs-api-openapi.yml
  format: yaml
  label: Browserless Screenshots & PDFs API
  slug: browserless-screenshots-pdfs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browserless/openapi/browserless-screenshots-pdfs-api-openapi.yml
- filename: browserless-sessions-connections-api-openapi.yml
  format: yaml
  label: Browserless Sessions & Connections API
  slug: browserless-sessions-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browserless/openapi/browserless-sessions-connections-api-openapi.yml
- filename: browserless-unblock-stealth-api-openapi.yml
  format: yaml
  label: Browserless Unblock & Stealth API
  slug: browserless-unblock-stealth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browserless/openapi/browserless-unblock-stealth-api-openapi.yml
- filename: browserless-websocket-apis-api-openapi.yml
  format: yaml
  label: Browserless WebSocket APIs API
  slug: browserless-websocket-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browserless/openapi/browserless-websocket-apis-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: organization-wide; infrastructure-hosting controls scoped to the cloud Browserless operates
    text: Security documentation is available for vendor review on request.
    type: SOC 2 Type II report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Browserless complies with the General Data Protection Regulation (GDPR) and maintains policies to support customer privacy obligations.
    type: GDPR compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Enterprise plans, private deployments we operate and self-hosted
    text: Browserless supports HIPAA-compatible deployments on Enterprise plans, both private deployments we operate and self-hosted.
    type: HIPAA-compatible deployments with Business Associate Agreement
  trust_center:
    url: https://www.browserless.io/trust
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Browserless
provenance_date: '2026-11-09'
provider_name: Browserless
provider_slug: browserless
slug: browserless-compliance
source_date: '2026-11-09'
source_filename: browserless-compliance.yml
source_heading: Compliance
source_page: https://www.browserless.io/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Browserless\naid: browserless\nurl: https://www.browserless.io/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/browserless-trust-center.yml\ntrust_center:\n  url: https://www.browserless.io/trust\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: organization-wide; infrastructure-hosting controls scoped to the cloud Browserless operates\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Security documentation is available for vendor review on request.\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Browserless complies with the General Data Protection Regulation (GDPR) and maintains policies to support\n    customer privacy obligations.\n- framework: HIPAA\n  type: HIPAA-compatible deployments with Business Associate Agreement\n  scope: Enterprise plans, private deployments we operate and self-hosted\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Browserless supports HIPAA-compatible deployments on Enterprise plans, both private deployments we operate\n    and self-hosted.\n"
source_yaml_url: https://artifacts.apis.io/browserless/compliance/browserless-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Browserless's own page on 2026-11-09.
synthetic: false
tags:
- Browser Automation
- Browser Infrastructure
- AI Agents
- Web Scraping
- BrowserQL
- Puppeteer
- Playwright
- Selenium
- Stealth
- CAPTCHA Solving
- Residential Proxy
- PDF Generation
- Screenshots
- Smart Scrape
- Crawl
- Search
- MCP
- Session Recording
- Hybrid Automation
- Chrome DevTools Protocol
---
