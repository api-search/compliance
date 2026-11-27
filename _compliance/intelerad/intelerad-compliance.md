---
api_specs:
- filename: intelerad-hl7-api-openapi.yml
  format: yaml
  label: Intelerad HL7 API
  slug: intelerad-hl7-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelerad/openapi/intelerad-hl7-api-openapi.yml
- filename: intelerad-namespace-api-openapi.yml
  format: yaml
  label: Intelerad Namespace API
  slug: intelerad-namespace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelerad/openapi/intelerad-namespace-api-openapi.yml
- filename: intelerad-order-api-openapi.yml
  format: yaml
  label: Intelerad Order API
  slug: intelerad-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelerad/openapi/intelerad-order-api-openapi.yml
- filename: intelerad-patient-api-openapi.yml
  format: yaml
  label: Intelerad Patient API
  slug: intelerad-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelerad/openapi/intelerad-patient-api-openapi.yml
- filename: intelerad-report-api-openapi.yml
  format: yaml
  label: Intelerad Report API
  slug: intelerad-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelerad/openapi/intelerad-report-api-openapi.yml
- filename: intelerad-session-api-openapi.yml
  format: yaml
  label: Intelerad Session API
  slug: intelerad-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelerad/openapi/intelerad-session-api-openapi.yml
- filename: intelerad-storage-api-openapi.yml
  format: yaml
  label: Intelerad Storage API
  slug: intelerad-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelerad/openapi/intelerad-storage-api-openapi.yml
- filename: intelerad-study-api-openapi.yml
  format: yaml
  label: Intelerad Study API
  slug: intelerad-study-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelerad/openapi/intelerad-study-api-openapi.yml
- filename: intelerad-webhook-api-openapi.yml
  format: yaml
  label: Intelerad Webhook API
  slug: intelerad-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelerad/openapi/intelerad-webhook-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: ISMS
    text: ISO 27001:2022 Certificate
    type: certification
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: SOC 2 Type II - Intelerad - 2026
    type: Type II
  - framework: HIPAA
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: HIPAA Report - 2026
    type: report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliance Checklist
    type: compliance checklist
  - framework: CyberEssentials
    issuer: Insignia
    period: '2026'
    report_access: unstated
    scope: null
    text: Cyber Essential Certificate 2026 - Insignia
    type: certificate
  trust_center:
    url: https://trust.intelerad.com/
frameworks:
- CyberEssentials
- GDPR
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Intelerad
provenance_date: '2026-11-09'
provider_name: Intelerad
provider_slug: intelerad
slug: intelerad-compliance
source_date: '2026-11-09'
source_filename: intelerad-compliance.yml
source_heading: Compliance
source_page: https://trust.intelerad.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Intelerad\naid: intelerad\nurl: https://trust.intelerad.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/intelerad-trust-center.yml\ntrust_center:\n  url: https://trust.intelerad.com/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: ISMS\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 Certificate\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II - Intelerad - 2026\n- framework: HIPAA\n  type: report\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access:\
  \ unstated\n  text: HIPAA Report - 2026\n- framework: GDPR\n  type: compliance checklist\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliance Checklist\n- framework: CyberEssentials\n  type: certificate\n  scope: null\n  period: '2026'\n  issuer: Insignia\n  report_access: unstated\n  text: Cyber Essential Certificate 2026 - Insignia\n"
source_yaml_url: https://artifacts.apis.io/intelerad/compliance/intelerad-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Intelerad's own page on 2026-11-09.
synthetic: false
tags:
- Medical Imaging
- PACS
- Enterprise Imaging
- Radiology
- DICOM
- DICOMweb
- HL7
- FHIR
- Healthcare
- Interoperability
- Image Exchange
---
