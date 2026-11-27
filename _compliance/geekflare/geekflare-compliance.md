---
api_specs:
- filename: geekflare-api-tool-api-openapi.yml
  format: yaml
  label: Geekflare API Tool API
  slug: geekflare-api-tool-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/geekflare/openapi/geekflare-api-tool-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 Started
    type: SOC 2 Type 2
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: GDPR compliance
  trust_center:
    url: https://trust.geekflare.com/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Geekflare
provenance_date: '2026-11-09'
provider_name: Geekflare
provider_slug: geekflare
slug: geekflare-compliance
source_date: '2026-11-09'
source_filename: geekflare-compliance.yml
source_heading: Compliance
source_page: https://trust.geekflare.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Geekflare\naid: geekflare\nurl: https://trust.geekflare.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/geekflare-trust-center.yml\ntrust_center:\n  url: https://trust.geekflare.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Started\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n"
source_yaml_url: https://artifacts.apis.io/geekflare/compliance/geekflare-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Geekflare's own page on 2026-11-09.
synthetic: false
tags:
- Development
- Public APIs
- Web Scraping
- Search
- Screenshots
- DNS
- Website Monitoring
- Security Testing
- AI Agents
- MCP
---
