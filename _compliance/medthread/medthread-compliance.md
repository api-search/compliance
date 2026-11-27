---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: compliance statement
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Certified
    type: certification
  trust_center:
    url: https://www.medthread.health/providers
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: MedThread
provenance_date: '2026-11-10'
provider_name: MedThread
provider_slug: medthread
slug: medthread-compliance
source_date: '2026-11-10'
source_filename: medthread-compliance.yml
source_heading: Compliance
source_page: https://www.medthread.health/providers
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: MedThread\naid: medthread\nurl: https://www.medthread.health/providers\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.medthread.health/providers\nattestations:\n- framework: HIPAA\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n- framework: SOC2\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Certified\n"
source_yaml_url: https://artifacts.apis.io/medthread/compliance/medthread-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from MedThread's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health Information Management
- Long-Term Care
- Post-Acute Care
- Skilled Nursing
- FHIR
- EHR Integration
- Compliance
- Patient Records
- Artificial Intelligence
---
