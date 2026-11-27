---
api_specs:
- filename: medplum-fhir-api-openapi.yml
  format: yaml
  label: Medplum Fhir API
  slug: medplum-fhir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medplum/openapi/medplum-fhir-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC2 Type II
    type: Type II
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HITRUST e1 Certification
    type: e1
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA compliance
    type: null
  - framework: ISO9001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 9001
    type: null
  - framework: SOC2
    issuer: Prescient Assurance
    period: null
    report_access: on_request
    scope: Orangebot, Inc (dba Medplum) information security practices, policies, procedures, and operations
    source: https://www.medplum.com/security
    text: Customers can request access to the audit report.
    type: SOC 2 Type II audit
  trust_center:
    url: https://www.medplum.com/docs/compliance
frameworks:
- HIPAA
- HITRUST
- ISO9001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Medplum
provenance_date: '2026-11-10'
provider_name: Medplum
provider_slug: medplum
slug: medplum-compliance
source_date: '2026-11-10'
source_filename: medplum-compliance.yml
source_heading: Compliance
source_page: https://www.medplum.com/docs/compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Medplum\naid: medplum\nurl: https://www.medplum.com/docs/compliance\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/medplum-trust-center.yml\n  sources:\n  - https://www.medplum.com/docs/compliance\n  - https://www.medplum.com/security\ntrust_center:\n  url: https://www.medplum.com/docs/compliance\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 Type II\n- framework: HITRUST\n  type: e1\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HITRUST e1 Certification\n- framework: HIPAA\n\
  \  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA compliance\n- framework: ISO9001\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 9001\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: Orangebot, Inc (dba Medplum) information security practices, policies, procedures, and operations\n  period: null\n  issuer: Prescient Assurance\n  report_access: on_request\n  text: Customers can request access to the audit report.\n  source: https://www.medplum.com/security\n"
source_yaml_url: https://artifacts.apis.io/medplum/compliance/medplum-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Medplum's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- FHIR
- Open Source
- Developer Platform
- HIPAA
- SMART on FHIR
- Clinical
- Interoperability
---
