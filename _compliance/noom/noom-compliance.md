---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    text: 2025 Noom SOC2 Type 2
    type: Type 2
  - framework: HITRUST
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    text: 2025 Noom HITRUST i1 Certification Letter
    type: i1 certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: null
  trust_center:
    url: https://trust.noom.com/
frameworks:
- HIPAA
- HITRUST
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Noom
provenance_date: '2026-11-10'
provider_name: Noom
provider_slug: noom
slug: noom-compliance
source_date: '2026-11-10'
source_filename: noom-compliance.yml
source_heading: Compliance
source_page: https://trust.noom.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Noom\naid: noom\nurl: https://trust.noom.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.noom.com/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: 2025 Noom SOC2 Type 2\n- framework: HITRUST\n  type: i1 certification\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: 2025 Noom HITRUST i1 Certification Letter\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n"
source_yaml_url: https://artifacts.apis.io/noom/compliance/noom-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Noom's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Digital Health
- Weight Management
- Wellness
- Behavioral Health
- Telehealth
- Nutrition
- Consumer Health
- Mobile App
---
