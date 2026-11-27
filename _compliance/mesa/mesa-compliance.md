---
api_specs:
- filename: mesa-authentication-api-openapi.yml
  format: yaml
  label: Mesa Authentication API
  slug: mesa-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesa/openapi/mesa-authentication-api-openapi.yml
- filename: mesa-invoices-api-openapi.yml
  format: yaml
  label: Mesa Invoices API
  slug: mesa-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mesa/openapi/mesa-invoices-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type I
    type: Type I
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II (Ongoing Observation)
    type: Type II (Ongoing Observation)
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://www.joinmesa.com
    text: SOC2 Compliant
    type: badge claim
  trust_center:
    url: https://trust.joinmesa.com/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mesa
provenance_date: '2026-11-10'
provider_name: Mesa
provider_slug: mesa
slug: mesa-compliance
source_date: '2026-11-10'
source_filename: mesa-compliance.yml
source_heading: Compliance
source_page: https://trust.joinmesa.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mesa\naid: mesa\nurl: https://trust.joinmesa.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/mesa-trust-center.yml\n  sources:\n  - https://trust.joinmesa.com/\n  - https://www.joinmesa.com\ntrust_center:\n  url: https://trust.joinmesa.com/\nattestations:\n- framework: SOC2\n  type: Type I\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type I\n- framework: SOC2\n  type: Type II (Ongoing Observation)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II (Ongoing Observation)\n- framework: SOC2\n  type: badge claim\n\
  \  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 Compliant\n  source: https://www.joinmesa.com\n"
source_yaml_url: https://artifacts.apis.io/mesa/compliance/mesa-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Mesa's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Invoice Financing
- Embedded Finance
- Early Payment
- ACH
- Supplier Payments
- B2B
---
