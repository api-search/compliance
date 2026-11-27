---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Wheel platform
    text: SOC 2 certified and HIPAA-compliant platform
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Wheel Horizon platform
    text: With built-in HIPAA compliance, SOC 2 certification, and experience powering compliant virtual care in all 50 states
    type: compliance
  trust_center:
    url: https://www.wheel.com/security-compliance
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Wheel
provenance_date: '2026-11-10'
provider_name: Wheel
provider_slug: wheel
slug: wheel-compliance
source_date: '2026-11-10'
source_filename: wheel-compliance.yml
source_heading: Compliance
source_page: https://www.wheel.com/security-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Wheel\naid: wheel\nurl: https://www.wheel.com/security-compliance\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.wheel.com/security-compliance\nattestations:\n- framework: SOC2\n  type: certification\n  scope: Wheel platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 certified and HIPAA-compliant platform\n- framework: HIPAA\n  type: compliance\n  scope: Wheel Horizon platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: With built-in HIPAA compliance, SOC 2 certification, and experience powering compliant virtual care in all\n    50 states\n"
source_yaml_url: https://artifacts.apis.io/wheel/compliance/wheel-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Wheel's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Virtual Care
- Digital Health
- Clinician Network
- Care Enablement
- HIPAA
---
