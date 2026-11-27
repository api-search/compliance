---
api_specs:
- filename: banksapi-openapi-generated.yml
  format: yaml
  label: fineconomy API
  slug: banksapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/banksapi/openapi/_ae-authored/banksapi-openapi-generated.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: All data hosted in German data centers
    text: This means that all data is subject to the strict German and European data protection guidelines (GDPR) and benefits from the highest security standards.
    type: Regulatory regime (stated applicability, not a certification)
  trust_center:
    url: https://banksapi.de/en/security/
frameworks:
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: fineconomy
provenance_date: '2026-11-09'
provider_name: fineconomy
provider_slug: banksapi
slug: banksapi-compliance
source_date: '2026-11-09'
source_filename: banksapi-compliance.yml
source_heading: Compliance
source_page: https://banksapi.de/en/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: fineconomy\naid: banksapi\nurl: https://banksapi.de/en/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://banksapi.de/en/security/\nattestations:\n- framework: GDPR\n  type: Regulatory regime (stated applicability, not a certification)\n  scope: All data hosted in German data centers\n  period: null\n  issuer: null\n  report_access: unstated\n  text: This means that all data is subject to the strict German and European data protection guidelines (GDPR)\n    and benefits from the highest security standards.\n"
source_yaml_url: https://artifacts.apis.io/banksapi/compliance/banksapi-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from fineconomy's own page on 2026-11-09.
synthetic: false
tags:
- Banking
- Fintech
- Payments
- Data Analytics
---
