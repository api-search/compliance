---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: certification
  - framework: ISO9001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 9001
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: regulatory compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA
    type: regulatory compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 80079:34
    type: standard
  trust_center:
    url: https://trust.augury.com/
frameworks:
- CCPA
- GDPR
- ISO27001
- ISO9001
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Augury
provenance_date: '2026-11-09'
provider_name: Augury
provider_slug: augury
slug: augury-compliance
source_date: '2026-11-09'
source_filename: augury-compliance.yml
source_heading: Compliance
source_page: https://trust.augury.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Augury\naid: augury\nurl: https://trust.augury.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.augury.com/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: ISO9001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 9001\n- framework: GDPR\n  type: regulatory compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: regulatory compliance\n  scope:\
  \ null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA\n- framework: other\n  type: standard\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 80079:34\n"
source_yaml_url: https://artifacts.apis.io/augury/compliance/augury-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Augury's own page on 2026-11-09.
synthetic: false
tags:
- Industrial AI
- Machine Health
- Process Health
- Predictive Maintenance
- Vibration Analysis
- Condition Monitoring
- IoT Sensors
- Halo
- Manufacturing
- Reliability
- Asset Performance
- OT
- CMMS
- EAM
---
