---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: Amwell platform
    text: Our platform is HITRUST certified and HIPAA compliant
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Amwell platform
    text: HIPAA compliant with actionable security guidelines to protect sensitive patient information
    type: regulatory compliance
  trust_center:
    url: https://business.amwell.com/who-we-serve/government
frameworks:
- HITRUST
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Amwell
provenance_date: '2026-11-09'
provider_name: Amwell
provider_slug: amwell
slug: amwell-compliance
source_date: '2026-11-09'
source_filename: amwell-compliance.yml
source_heading: Compliance
source_page: https://business.amwell.com/who-we-serve/government
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Amwell\naid: amwell\nurl: https://business.amwell.com/who-we-serve/government\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://business.amwell.com/who-we-serve/government\nattestations:\n- framework: HITRUST\n  type: certification\n  scope: Amwell platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our platform is HITRUST certified and HIPAA compliant\n- framework: other\n  type: regulatory compliance\n  scope: Amwell platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA compliant with actionable security guidelines to protect sensitive patient information\n"
source_yaml_url: https://artifacts.apis.io/amwell/compliance/amwell-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Amwell's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- United States
- Telehealth
- Virtual Care
- FHIR
- HL7
- Interoperability
- Electronic Health Records
- SDK
---
