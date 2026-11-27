---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: 2024-2025
    report_access: unstated
    scope: null
    text: SOC 2 Type II Report 2024-2025
    type: SOC 2 Type II report
  - framework: SOC2
    issuer: null
    period: 2023-2024
    report_access: unstated
    scope: null
    text: SOC 2 Type II Report 2023-2024
    type: SOC 2 Type II report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: compliance listing
  trust_center:
    url: https://trust.ravio.com/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ravio
provenance_date: '2026-11-10'
provider_name: Ravio
provider_slug: ravio
slug: ravio-compliance
source_date: '2026-11-10'
source_filename: ravio-compliance.yml
source_heading: Compliance
source_page: https://trust.ravio.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ravio\naid: ravio\nurl: https://trust.ravio.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/ravio-trust-center.yml\ntrust_center:\n  url: https://trust.ravio.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: 2024-2025\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Report 2024-2025\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: 2023-2024\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Report 2023-2024\n- framework: GDPR\n  type: compliance listing\n  scope: null\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/ravio/compliance/ravio-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Ravio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Compensation
- Benchmarking
- Total Rewards
- Human Resources
- Software-as-a-Service
---
