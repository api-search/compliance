---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Qventus-2025-Type 2 SOC 2-Final Report.pdf
    type: Type 2 report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Qventus-2025-Type 1 HIPAA-Final Report.pdf
    type: Type 1 report
  trust_center:
    url: https://trust.qventus.com/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Qventus
provenance_date: '2026-11-10'
provider_name: Qventus
provider_slug: qventus
slug: qventus-compliance
source_date: '2026-11-10'
source_filename: qventus-compliance.yml
source_heading: Compliance
source_page: https://trust.qventus.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Qventus\naid: qventus\nurl: https://trust.qventus.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.qventus.com/\nattestations:\n- framework: SOC2\n  type: Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Qventus-2025-Type 2 SOC 2-Final Report.pdf\n- framework: HIPAA\n  type: Type 1 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Qventus-2025-Type 1 HIPAA-Final Report.pdf\n"
source_yaml_url: https://artifacts.apis.io/qventus/compliance/qventus-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Qventus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health IT
- Hospital Operations
- Artificial Intelligence
- Automation
- Care Coordination
---
