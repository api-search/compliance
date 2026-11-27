---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Airtime is SOC 2, type 2 compliant.
    type: SOC 2 Type 2
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We have implemented a GDPR compliance program.
    type: compliance program
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We have implemented a CCPA compliance program.
    type: compliance program
  trust_center:
    url: https://www.airtime.com/legal/trust-center
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Airtime
provenance_date: '2026-11-09'
provider_name: Airtime
provider_slug: airtime
slug: airtime-compliance
source_date: '2026-11-09'
source_filename: airtime-compliance.yml
source_heading: Compliance
source_page: https://www.airtime.com/legal/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Airtime\naid: airtime\nurl: https://www.airtime.com/legal/trust-center\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.airtime.com/legal/trust-center\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Airtime is SOC 2, type 2 compliant.\n- framework: GDPR\n  type: compliance program\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We have implemented a GDPR compliance program.\n- framework: CCPA\n  type: compliance program\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: We have implemented a CCPA compliance program.\n"
source_yaml_url: https://artifacts.apis.io/airtime/compliance/airtime-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Airtime's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Video
- Productivity
- Collaboration
- Screen Recording
- Presentations
- Remote Work
---
