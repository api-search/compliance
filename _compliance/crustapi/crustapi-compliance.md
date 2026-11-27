---
api_specs:
- filename: crustapi-demo-api-openapi.yml
  format: yaml
  label: CrustAPI Demo API
  slug: crustapi-demo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crustapi/openapi/crustapi-demo-api-openapi.yml
- filename: crustapi-search-api-openapi.yml
  format: yaml
  label: CrustAPI Search API
  slug: crustapi-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crustapi/openapi/crustapi-search-api-openapi.yml
- filename: crustapi-account-api-openapi.yml
  format: yaml
  label: CrustAPI Account API
  slug: crustapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crustapi/openapi/crustapi-account-api-openapi.yml
- filename: crustapi-linked-in-api-openapi.yml
  format: yaml
  label: CrustAPI Linked In API
  slug: crustapi-linked-in-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crustapi/openapi/crustapi-linked-in-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR COMPLIANT
    type: compliance badge
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA COMPLIANT
    type: compliance badge
  trust_center:
    url: https://crustapi.com/
frameworks:
- CCPA
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CrustAPI
provenance_date: '2026-11-09'
provider_name: CrustAPI
provider_slug: crustapi
slug: crustapi-compliance
source_date: '2026-11-09'
source_filename: crustapi-compliance.yml
source_heading: Compliance
source_page: https://crustapi.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CrustAPI\naid: crustapi\nurl: https://crustapi.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/crustapi-trust-center.yml\ntrust_center:\n  url: https://crustapi.com/\nattestations:\n- framework: GDPR\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR COMPLIANT\n- framework: CCPA\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA COMPLIANT\n"
source_yaml_url: https://artifacts.apis.io/crustapi/compliance/crustapi-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from CrustAPI's own page on 2026-11-09.
synthetic: false
tags:
- Search
- Google Maps
- LinkedIn
- SERP / Web Scraping
- Business & Lead Data
- People / Recruiting Data
- Data Enrichment
- AI Agents / MCP
- RAG
- Data
---
