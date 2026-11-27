---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: all cloud environments
    text: For all our cloud environments, Redox maintains Health Information Trust Alliance (HITRUST®) certification .
    type: certification
  - framework: HITRUST
    issuer: third-party auditor
    period: null
    report_access: unstated
    scope: Redox transactions on AWS and Google Cloud Platform
    text: For Redox transactions on AWS and Google Cloud Platform, we have earned the HITRUST r2 certification, the highest standard achievable, validated by a third-party auditor.
    type: r2 certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Redox maintains a SOC 2® Type 2 report .
    type: Type 2 report
  trust_center:
    url: https://redoxengine.com/platform-security/
frameworks:
- HITRUST
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Redox
provenance_date: '2026-11-10'
provider_name: Redox
provider_slug: redox
slug: redox-compliance
source_date: '2026-11-10'
source_filename: redox-compliance.yml
source_heading: Compliance
source_page: https://redoxengine.com/platform-security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Redox\naid: redox\nurl: https://redoxengine.com/platform-security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://redoxengine.com/platform-security/\nattestations:\n- framework: HITRUST\n  type: certification\n  scope: all cloud environments\n  period: null\n  issuer: null\n  report_access: unstated\n  text: For all our cloud environments, Redox maintains Health Information Trust Alliance (HITRUST®) certification\n    .\n- framework: HITRUST\n  type: r2 certification\n  scope: Redox transactions on AWS and Google Cloud Platform\n  period: null\n  issuer: third-party auditor\n  report_access: unstated\n\
  \  text: For Redox transactions on AWS and Google Cloud Platform, we have earned the HITRUST r2 certification, the\n    highest standard achievable, validated by a third-party auditor.\n- framework: SOC2\n  type: Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Redox maintains a SOC 2® Type 2 report .\n"
source_yaml_url: https://artifacts.apis.io/redox/compliance/redox-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Redox's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Interoperability
- FHIR
- Electronic Health Records
- Health Data
- Integration
- HL7
- Digital Health
- Healthcare API
---
