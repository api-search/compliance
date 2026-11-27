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
    text: SOC 2 Type II
    type: Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: null
  trust_center:
    url: https://trust.sprinterhealth.com/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sprinter Health
provenance_date: '2026-11-10'
provider_name: Sprinter Health
provider_slug: sprinter-health
slug: sprinter-health-compliance
source_date: '2026-11-10'
source_filename: sprinter-health-compliance.yml
source_heading: Compliance
source_page: https://trust.sprinterhealth.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sprinter Health\naid: sprinter-health\nurl: https://trust.sprinterhealth.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.sprinterhealth.com/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n"
source_yaml_url: https://artifacts.apis.io/sprinter-health/compliance/sprinter-health-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Sprinter Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- In-Home Care
- Preventive Care
- Diagnostics
- Telehealth
- Care Navigation
---
