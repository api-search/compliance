---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Avaneer maintains SOC2 Type 1 compliance and our report is available upon request.
    type: Type 1
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: All network activity is HIPAA-compliant, logged, and auditable.
    type: null
  trust_center:
    url: https://avaneerhealth.com/security/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Avaneer Health
provenance_date: '2026-11-09'
provider_name: Avaneer Health
provider_slug: avaneer-health
slug: avaneer-health-compliance
source_date: '2026-11-09'
source_filename: avaneer-health-compliance.yml
source_heading: Compliance
source_page: https://avaneerhealth.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Avaneer Health\naid: avaneer-health\nurl: https://avaneerhealth.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://avaneerhealth.com/security/\nattestations:\n- framework: SOC2\n  type: Type 1\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Avaneer maintains SOC2 Type 1 compliance and our report is available upon request.\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: All network activity is HIPAA-compliant, logged, and auditable.\n"
source_yaml_url: https://artifacts.apis.io/avaneer-health/compliance/avaneer-health-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Avaneer Health's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Revenue Cycle
- Interoperability
- Real-Time Data
- API Platform
---
