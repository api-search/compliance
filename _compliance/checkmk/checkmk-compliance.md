---
claim_count: 6
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022 certificate pdf
    type: certificate
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Checkmk SOC 2 Type 1 Report 2025
    type: Type 1
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: badge
  - framework: DORA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: DORA
    type: badge
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: EU AI Act
    type: AI regulation badge (EU AI Act)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SIG-Lite 2023
    type: SIG-Lite questionnaire
  trust_center:
    url: https://trust.checkmk.com/
frameworks:
- DORA
- GDPR
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Checkmk
provenance_date: '2026-11-09'
provider_name: Checkmk
provider_slug: checkmk
slug: checkmk-compliance
source_date: '2026-11-09'
source_filename: checkmk-compliance.yml
source_heading: Compliance
source_page: https://trust.checkmk.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Checkmk\naid: checkmk\nurl: https://trust.checkmk.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.checkmk.com/\nattestations:\n- framework: ISO27001\n  type: certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 certificate pdf\n- framework: SOC2\n  type: Type 1\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Checkmk SOC 2 Type 1 Report 2025\n- framework: GDPR\n  type: badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: DORA\n  type: badge\n  scope:\
  \ null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: DORA\n- framework: other\n  type: AI regulation badge (EU AI Act)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: EU AI Act\n- framework: other\n  type: SIG-Lite questionnaire\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SIG-Lite 2023\n"
source_yaml_url: https://artifacts.apis.io/checkmk/compliance/checkmk-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Checkmk's own page on 2026-11-09.
synthetic: false
tags:
- Monitoring
- Observability
- IT Infrastructure
- Open Source
- Software-as-a-Service
---
