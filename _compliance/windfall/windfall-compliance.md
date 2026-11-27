---
api_specs:
- filename: windfall-windfall-api-api-openapi.yml
  format: yaml
  label: Windfall API
  slug: windfall-windfall-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/windfall/openapi/windfall-windfall-api-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: security, availability, processing integrity, confidentiality principles
    text: Windfall’s continued SOC 2 Type 2 compliance demonstrates our commitment to security, availability, processing integrity, and confidentiality principles.
    type: Type 2 report
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Windfall is a registered data broker in the state of California, and fully compliant with CCPA.
    type: compliance statement
  trust_center:
    url: https://www.windfall.com/platform/privacy-security
frameworks:
- CCPA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Windfall
provenance_date: '2026-11-10'
provider_name: Windfall
provider_slug: windfall
slug: windfall-compliance
source_date: '2026-11-10'
source_filename: windfall-compliance.yml
source_heading: Compliance
source_page: https://www.windfall.com/platform/privacy-security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Windfall\naid: windfall\nurl: https://www.windfall.com/platform/privacy-security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/windfall-trust-center.yml\ntrust_center:\n  url: https://www.windfall.com/platform/privacy-security\nattestations:\n- framework: SOC2\n  type: Type 2 report\n  scope: security, availability, processing integrity, confidentiality principles\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Windfall’s continued SOC 2 Type 2 compliance demonstrates our commitment to security, availability, processing\n    integrity, and confidentiality principles.\n- framework:\
  \ CCPA\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Windfall is a registered data broker in the state of California, and fully compliant with CCPA.\n"
source_yaml_url: https://artifacts.apis.io/windfall/compliance/windfall-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Windfall's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Data Enrichment
- Wealth Data
- People Intelligence
- Career Data
- Identity Resolution
- Sales Intelligence
- Marketing
- Data
- Net Worth
- Sales
---
