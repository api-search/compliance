---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2024'
    report_access: unstated
    scope: null
    text: 2024 - SOC 2 Type 2 Report
    type: Type 2
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    text: 2025 - SOC 2 Type 2 Report
    type: Type 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 HIPAA
    type: null
  trust_center:
    url: https://trust.brook.ai/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Brook
provenance_date: '2026-11-09'
provider_name: Brook
provider_slug: brook
slug: brook-compliance
source_date: '2026-11-09'
source_filename: brook-compliance.yml
source_heading: Compliance
source_page: https://trust.brook.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Brook\naid: brook\nurl: https://trust.brook.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.brook.ai/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: '2024'\n  issuer: null\n  report_access: unstated\n  text: 2024 - SOC 2 Type 2 Report\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: 2025 - SOC 2 Type 2 Report\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 HIPAA\n"
source_yaml_url: https://artifacts.apis.io/brook/compliance/brook-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Brook's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Remote Care
- Artificial Intelligence
---
