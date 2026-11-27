---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type 2 Report Request
    type: SOC 2 Type 2 Report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: ISO 27001:2022 Audit Report Request
    type: ISO 27001:2022 Audit Report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Protect the personal data and privacy of EU citizens for transactions that occur within EU member states
    type: GDPR
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA California Consumer Privacy Act, is legislation designed to improve the data privacy of California residents
    type: CCPA
  trust_center:
    url: https://trust.chattermill.com/
frameworks:
- CCPA
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Chattermill
provenance_date: '2026-11-09'
provider_name: Chattermill
provider_slug: chattermill
slug: chattermill-compliance
source_date: '2026-11-09'
source_filename: chattermill-compliance.yml
source_heading: Compliance
source_page: https://trust.chattermill.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Chattermill\naid: chattermill\nurl: https://trust.chattermill.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.chattermill.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 Report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 2 Report Request\n- framework: ISO27001\n  type: ISO 27001:2022 Audit Report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO 27001:2022 Audit Report Request\n- framework: GDPR\n  type: GDPR\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ Protect the personal data and privacy of EU citizens for transactions that occur within EU member states\n- framework: CCPA\n  type: CCPA\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA California Consumer Privacy Act, is legislation designed to improve the data privacy of California\n    residents\n"
source_yaml_url: https://artifacts.apis.io/chattermill/compliance/chattermill-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Chattermill's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Voice of Customer
- Feedback Analysis
- Enterprise
---
