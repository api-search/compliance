---
api_specs:
- filename: tavily-crawl-api-openapi.yml
  format: yaml
  label: Tavily Crawl API
  slug: tavily-crawl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-crawl-api-openapi.yml
- filename: tavily-extract-api-openapi.yml
  format: yaml
  label: Tavily Extract API
  slug: tavily-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-extract-api-openapi.yml
- filename: tavily-map-api-openapi.yml
  format: yaml
  label: Tavily Map API
  slug: tavily-map-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-map-api-openapi.yml
- filename: tavily-research-api-openapi.yml
  format: yaml
  label: Tavily Research API
  slug: tavily-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-research-api-openapi.yml
- filename: tavily-search-api-openapi.yml
  format: yaml
  label: Tavily Search API
  slug: tavily-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-search-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Customers and prospects can request access can to review the updated report directly in the Trust Center.
    type: SOC 2 Type II report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Tavily is now ISO/IEC 27001:2022 certified
    type: ISO/IEC 27001:2022 certification
  trust_center:
    url: https://trust.tavily.com/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Tavily
provenance_date: '2026-11-10'
provider_name: Tavily
provider_slug: tavily
slug: tavily-compliance
source_date: '2026-11-10'
source_filename: tavily-compliance.yml
source_heading: Compliance
source_page: https://trust.tavily.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Tavily\naid: tavily\nurl: https://trust.tavily.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/tavily-trust-center.yml\ntrust_center:\n  url: https://trust.tavily.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Customers and prospects can request access can to review the updated report directly in the Trust Center.\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Tavily is now ISO/IEC 27001:2022\
  \ certified\n"
source_yaml_url: https://artifacts.apis.io/tavily/compliance/tavily-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Tavily's own page on 2026-11-10.
synthetic: false
tags:
- Search
- Web Search
- AI Agents
- LLM
- Extract
- Crawl
- Sitemap
- Research
- REST
- LangChain
- LlamaIndex
- Real-Time
- A2A
---
