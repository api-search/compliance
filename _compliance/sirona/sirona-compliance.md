---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent third-party auditors
    period: null
    report_access: nda
    scope: Sirona platform
    text: SOC 2 Type II — active audit program
    type: Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Sirona platform
    text: 'HIPAA-compliant by design: encryption at rest and in transit, audit logging of changes to clinical information, and role-based access controls.'
    type: HIPAA compliance by design
  trust_center:
    url: https://sironamedical.com/solutions/security-regulatory-compliance
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sirona Medical
provenance_date: '2026-11-10'
provider_name: Sirona Medical
provider_slug: sirona
slug: sirona-compliance
source_date: '2026-11-10'
source_filename: sirona-compliance.yml
source_heading: Compliance
source_page: https://sironamedical.com/solutions/security-regulatory-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sirona Medical\naid: sirona\nurl: https://sironamedical.com/solutions/security-regulatory-compliance\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://sironamedical.com/solutions/security-regulatory-compliance\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: Sirona platform\n  period: null\n  issuer: independent third-party auditors\n  report_access: nda\n  text: SOC 2 Type II — active audit program\n- framework: HIPAA\n  type: HIPAA compliance by design\n  scope: Sirona platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'HIPAA-compliant by design: encryption at rest\
  \ and in transit, audit logging of changes to clinical information,\n    and role-based access controls.'\n"
source_yaml_url: https://artifacts.apis.io/sirona/compliance/sirona-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Sirona Medical's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Medical Imaging
- Radiology
- PACS
- DICOM
- HL7
- FHIR
- Cloud
- Artificial Intelligence
- Health IT
---
