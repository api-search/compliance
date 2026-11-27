---
api_specs:
- filename: brand-api-brands-api-openapi.yml
  format: yaml
  label: Brand API (Brandfetch) Brands API
  slug: brand-api-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brand-api/openapi/brand-api-brands-api-openapi.yml
- filename: brand-api-context-api-openapi.yml
  format: yaml
  label: Brand API (Brandfetch) Context API
  slug: brand-api-context-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brand-api/openapi/brand-api-context-api-openapi.yml
- filename: brand-api-search-api-openapi.yml
  format: yaml
  label: Brand API (Brandfetch) Search API
  slug: brand-api-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brand-api/openapi/brand-api-search-api-openapi.yml
- filename: brand-api-viewer-api-openapi.yml
  format: yaml
  label: Brand API (Brandfetch) Viewer API
  slug: brand-api-viewer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brand-api/openapi/brand-api-viewer-api-openapi.yml
- filename: brand-api-agents-api-openapi.yml
  format: yaml
  label: Brand API (Brandfetch) Agents API
  slug: brand-api-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brand-api/openapi/brand-api-agents-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: View all SOC2 Type2 Report
    type: SOC 2 Type 2 report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Security trust service category
    source: https://docs.brandfetch.com/support/security-soc2
    text: Brandfetch is SOC 2 Type 2 certified.
    type: Type 2
  trust_center:
    url: https://trust.brandfetch.com/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Brand API (Brandfetch)
provenance_date: '2026-11-09'
provider_name: Brand API (Brandfetch)
provider_slug: brand-api
slug: brand-api-compliance
source_date: '2026-11-09'
source_filename: brand-api-compliance.yml
source_heading: Compliance
source_page: https://trust.brandfetch.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Brand API (Brandfetch)\naid: brand-api\nurl: https://trust.brandfetch.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/brand-api-trust-center.yml\n  sources:\n  - https://docs.brandfetch.com/support/security-soc2\n  - https://trust.brandfetch.com/\ntrust_center:\n  url: https://trust.brandfetch.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: View all SOC2 Type2 Report\n- framework: SOC2\n  type: Type 2\n  scope: Security trust service category\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Brandfetch is SOC 2 Type 2 certified.\n  source: https://docs.brandfetch.com/support/security-soc2\n"
source_yaml_url: https://artifacts.apis.io/brand-api/compliance/brand-api-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Brand API (Brandfetch)'s own page on 2026-11-09.
synthetic: false
tags:
- Brands
- Logo
- Brand Assets
- Company Data
- Firmographics
- Brand Context
- Merchant Enrichment
- Agent Tools
- A2A
---
