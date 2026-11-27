---
api_specs:
- filename: serpapi-account-api-openapi.yml
  format: yaml
  label: SerpApi Account API
  slug: serpapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpapi/openapi/serpapi-account-api-openapi.yml
- filename: serpapi-search-api-openapi.yml
  format: yaml
  label: SerpApi Search API
  slug: serpapi-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpapi/openapi/serpapi-search-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Trust Services Principles
    text: SOC 2 Service Organization Controls (Soc2) (Type II) Trust Services Principles. Acquired
    type: Type II
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: Service Organization Controls
    text: SOC 3 Service Organization Controls (Soc3). Acquired
    type: null
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: International Standard for Information Security
    text: ISO 27001 International Standard for Information Security. Acquired
    type: null
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: International Standard for Privacy Information Management
    text: ISO 27701 International Standard for Privacy Information Management. Acquired
    type: null
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Ethical Web Data Collection Initiative
    text: EWDCI Ethical Web Data Collection Initiative Trust Seal. Acquired
    type: Trust Seal
  trust_center:
    url: https://serpapi.com/security
frameworks:
- ISO27001
- ISO27701
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: SerpApi
provenance_date: '2026-11-10'
provider_name: SerpApi
provider_slug: serpapi
slug: serpapi-compliance
source_date: '2026-11-10'
source_filename: serpapi-compliance.yml
source_heading: Compliance
source_page: https://serpapi.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: SerpApi\naid: serpapi\nurl: https://serpapi.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://serpapi.com/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: Trust Services Principles\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Service Organization Controls (Soc2) (Type II) Trust Services Principles. Acquired\n- framework: SOC3\n  type: null\n  scope: Service Organization Controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 3 Service Organization Controls (Soc3). Acquired\n- framework: ISO27001\n  type: null\n  scope:\
  \ International Standard for Information Security\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 International Standard for Information Security. Acquired\n- framework: ISO27701\n  type: null\n  scope: International Standard for Privacy Information Management\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27701 International Standard for Privacy Information Management. Acquired\n- framework: other\n  type: Trust Seal\n  scope: Ethical Web Data Collection Initiative\n  period: null\n  issuer: null\n  report_access: unstated\n  text: EWDCI Ethical Web Data Collection Initiative Trust Seal. Acquired\n"
source_yaml_url: https://artifacts.apis.io/serpapi/compliance/serpapi-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from SerpApi's own page on 2026-11-10.
synthetic: false
tags:
- Bing
- Google
- Search
- Search Engines
- SERP
- Web Scraping
- AI Agents
- MCP
- Markdown
- Baidu
- DuckDuckGo
- YouTube
- Amazon
---
