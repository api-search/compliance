---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2
    type: Type 2
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 1
    type: Type 1
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA - Attestation Letter
    type: attestation letter
  trust_center:
    url: https://trust.chambercardio.com/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Chamber Cardio
provenance_date: '2026-11-09'
provider_name: Chamber Cardio
provider_slug: chamber-cardio
slug: chamber-cardio-compliance
source_date: '2026-11-09'
source_filename: chamber-cardio-compliance.yml
source_heading: Compliance
source_page: https://trust.chambercardio.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Chamber Cardio\naid: chamber-cardio\nurl: https://trust.chambercardio.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.chambercardio.com/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2\n- framework: SOC2\n  type: Type 1\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 1\n- framework: HIPAA\n  type: attestation letter\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA - Attestation Letter\n"
source_yaml_url: https://artifacts.apis.io/chamber-cardio/compliance/chamber-cardio-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Chamber Cardio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Cardiology
- Value-Based Care
- Health Tech
- FHIR
- Care Coordination
- Payers
---
