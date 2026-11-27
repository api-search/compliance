---
api_specs:
- filename: shipsy-website-ai-api-openapi.yml
  format: yaml
  label: Shipsy Website AI API
  slug: shipsy-website-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipsy/openapi/shipsy-website-ai-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Independent third party
    period: null
    report_access: nda
    scope: All 5 Trust Services Criteria
    text: SOC 2 Type II — Certified (report available under NDA)
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: BSI (British Standards Institution)
    period: null
    report_access: on_request
    scope: Information Security Management Systems
    text: ISO 27001:2022 — Certified via BSI (British Standards Institution)
    type: ISO 27001:2022 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: Shipsy as data processor
    text: GDPR — Compliant; DPA + SCCs available
    type: GDPR compliance (self-stated processor compliance)
  trust_center:
    url: https://trust.shipsy.io/
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Shipsy
provenance_date: '2026-11-10'
provider_name: Shipsy
provider_slug: shipsy
slug: shipsy-compliance
source_date: '2026-11-10'
source_filename: shipsy-compliance.yml
source_heading: Compliance
source_page: https://trust.shipsy.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Shipsy\naid: shipsy\nurl: https://trust.shipsy.io/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.shipsy.io/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: All 5 Trust Services Criteria\n  period: null\n  issuer: Independent third party\n  report_access: nda\n  text: SOC 2 Type II — Certified (report available under NDA)\n- framework: ISO27001\n  type: ISO 27001:2022 certification\n  scope: Information Security Management Systems\n  period: null\n  issuer: BSI (British Standards Institution)\n  report_access: on_request\n  text: ISO 27001:2022 — Certified via BSI (British Standards\
  \ Institution)\n- framework: GDPR\n  type: GDPR compliance (self-stated processor compliance)\n  scope: Shipsy as data processor\n  period: null\n  issuer: null\n  report_access: on_request\n  text: GDPR — Compliant; DPA + SCCs available\n"
source_yaml_url: https://artifacts.apis.io/shipsy/compliance/shipsy-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Shipsy's own page on 2026-11-10.
synthetic: false
tags:
- Logistics
- Artificial Intelligence
- Transportation
- Warehouse
- Software-as-a-Service
- Company
---
