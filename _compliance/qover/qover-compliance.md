---
api_specs:
- filename: postman.yaml
  format: yaml
  label: Qover Embedded Insurance API
  slug: qover-embedded-insurance-api
  spec_type: Postman
  url: https://docs.qover.com/
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Qover is ISO 27001 & ISO 27701 compliant
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27701:2019
    type: certification
  trust_center:
    url: https://trust.qover.com/
frameworks:
- ISO27001
- ISO27701
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Qover
provenance_date: '2026-11-10'
provider_name: Qover
provider_slug: qover
slug: qover-compliance
source_date: '2026-11-10'
source_filename: qover-compliance.yml
source_heading: Compliance
source_page: https://trust.qover.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Qover\naid: qover\nurl: https://trust.qover.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.qover.com/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Qover is ISO 27001 & ISO 27701 compliant\n- framework: ISO27701\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27701:2019\n"
source_yaml_url: https://artifacts.apis.io/qover/compliance/qover-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Qover's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Insurtech
- Insurance
- Embedded Insurance
- Claims
- Policy
- Fintech
- Belgium
---
