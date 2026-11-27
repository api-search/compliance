---
api_specs:
- filename: fasten-health-bridge-api-openapi.yml
  format: yaml
  label: Fasten Health Bridge API
  slug: fasten-health-bridge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fasten-health/openapi/fasten-health-bridge-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: on_request
    scope: null
    text: Request Fasten Health SOC 2 Type 1 2025 Audit
    type: Type 1 audit
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: on_request
    scope: null
    text: Request Fasten Health SOC 2 Type 2 2026
    type: Type 2 report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Request Fasten Health - HIPAA Assessment.docx
    type: HIPAA assessment
  trust_center:
    url: https://trust.fastenhealth.com/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Fasten Health
provenance_date: '2026-11-09'
provider_name: Fasten Health
provider_slug: fasten-health
slug: fasten-health-compliance
source_date: '2026-11-09'
source_filename: fasten-health-compliance.yml
source_heading: Compliance
source_page: https://trust.fastenhealth.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Fasten Health\naid: fasten-health\nurl: https://trust.fastenhealth.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.fastenhealth.com/\nattestations:\n- framework: SOC2\n  type: Type 1 audit\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: on_request\n  text: Request Fasten Health SOC 2 Type 1 2025 Audit\n- framework: SOC2\n  type: Type 2 report\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: on_request\n  text: Request Fasten Health SOC 2 Type 2 2026\n- framework: HIPAA\n  type: HIPAA assessment\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ on_request\n  text: Request Fasten Health - HIPAA Assessment.docx\n"
source_yaml_url: https://artifacts.apis.io/fasten-health/compliance/fasten-health-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Fasten Health's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- FHIR
- Personal Health Record
- Electronic Medical Record
- Health Data Interoperability
- TEFCA
- EHI Export
- Patient Consent
- Self-Hosted
- Open Source
- HL7
- Healthcare Connectivity
- A2A
---
