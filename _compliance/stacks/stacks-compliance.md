---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: ISO 27001:2022
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type 2
    type: report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: regulatory compliance
  trust_center:
    url: https://trust.stacks.ai/
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Stacks
provenance_date: '2026-11-10'
provider_name: Stacks
provider_slug: stacks
slug: stacks-compliance
source_date: '2026-11-10'
source_filename: stacks-compliance.yml
source_heading: Compliance
source_page: https://trust.stacks.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Stacks\naid: stacks\nurl: https://trust.stacks.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.stacks.ai/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO 27001:2022\n- framework: SOC2\n  type: report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 2\n- framework: GDPR\n  type: regulatory compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/stacks/compliance/stacks-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Stacks's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Accounting
- Financial Close
- Reconciliation
- ERP
- Artificial Intelligence
- AI Agents
---
