---
api_specs:
- filename: searchapi-search-api-openapi.yml
  format: yaml
  label: SearchApi SERP API
  slug: searchapi-serp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searchapi/openapi/searchapi-search-api-openapi.yml
- filename: searchapi-account-api-openapi.yml
  format: yaml
  label: SearchApi Account & Analytics API
  slug: searchapi-account-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searchapi/openapi/searchapi-account-api-openapi.yml
- filename: searchapi-analytics-api-openapi.yml
  format: yaml
  label: SearchApi Analytics API
  slug: searchapi-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searchapi/openapi/searchapi-analytics-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: SearchApi security certifications and audit reports
    text: SearchApi maintains independent security certifications and audit reports, including SOC 2 Type II and ISO 27001 assessments.
    type: SOC 2 Type II report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: SearchApi security certifications and audit reports
    text: These reports, along with on-site audit rights and detailed security assessments, are available to customers on an Enterprise plan.
    type: ISO 27001 assessment
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: security controls
    source: https://www.searchapi.io/announcements
    text: SearchApi is now SOC 2 Type II compliant.
    type: SOC 2 Type II report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.searchapi.io/announcements
    text: SearchApi is GDPR compliant.
    type: GDPR documentation
  trust_center:
    url: https://www.searchapi.io/legal/dpa
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: SearchApi
provenance_date: '2026-11-10'
provider_name: SearchApi
provider_slug: searchapi
slug: searchapi-compliance
source_date: '2026-11-10'
source_filename: searchapi-compliance.yml
source_heading: Compliance
source_page: https://www.searchapi.io/legal/dpa
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: SearchApi\naid: searchapi\nurl: https://www.searchapi.io/legal/dpa\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/searchapi-trust-center.yml\n  sources:\n  - https://www.searchapi.io/announcements\n  - https://www.searchapi.io/legal/dpa\ntrust_center:\n  url: https://www.searchapi.io/legal/dpa\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: SearchApi security certifications and audit reports\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SearchApi maintains independent security certifications and audit reports, including SOC 2 Type II and ISO\n    27001\
  \ assessments.\n- framework: ISO27001\n  type: ISO 27001 assessment\n  scope: SearchApi security certifications and audit reports\n  period: null\n  issuer: null\n  report_access: on_request\n  text: These reports, along with on-site audit rights and detailed security assessments, are available to customers\n    on an Enterprise plan.\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: security controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SearchApi is now SOC 2 Type II compliant.\n  source: https://www.searchapi.io/announcements\n- framework: GDPR\n  type: GDPR documentation\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SearchApi is GDPR compliant.\n  source: https://www.searchapi.io/announcements\n"
source_yaml_url: https://artifacts.apis.io/searchapi/compliance/searchapi-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from SearchApi's own page on 2026-11-10.
synthetic: false
tags:
- Search
- SERP
- Google Search
- Web Scraping
- Search data
- Market Intelligence
- SEO
- MCP
- Agent-Native
---
