---
api_specs:
- filename: cashflo-ingest-api-openapi.yml
  format: yaml
  label: CashFlo Ingest API
  slug: cashflo-ingest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cashflo/openapi/cashflo-ingest-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance SOC 2 1 document
    type: null
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance ISO 27001:2022 1 document
    type: ISO 27001:2022
  trust_center:
    url: https://trust.cashflo.io/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: CashFlo
provenance_date: '2026-11-09'
provider_name: CashFlo
provider_slug: cashflo
slug: cashflo-compliance
source_date: '2026-11-09'
source_filename: cashflo-compliance.yml
source_heading: Compliance
source_page: https://trust.cashflo.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: CashFlo\naid: cashflo\nurl: https://trust.cashflo.io/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.cashflo.io/\nattestations:\n- framework: SOC2\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance SOC 2 1 document\n- framework: ISO27001\n  type: ISO 27001:2022\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance ISO 27001:2022 1 document\n"
source_yaml_url: https://artifacts.apis.io/cashflo/compliance/cashflo-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from CashFlo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Accounts Payable
- Payments
- Working Capital
- Supply Chain Finance
- ERP Integration
- Compliance
- India
---
