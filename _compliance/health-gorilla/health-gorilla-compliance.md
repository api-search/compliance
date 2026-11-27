---
api_specs:
- filename: health-gorilla-binary-api-openapi.yml
  format: yaml
  label: Health Gorilla Binary API
  slug: health-gorilla-binary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-binary-api-openapi.yml
- filename: health-gorilla-coverage-api-openapi.yml
  format: yaml
  label: Health Gorilla Coverage API
  slug: health-gorilla-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-coverage-api-openapi.yml
- filename: health-gorilla-diagnosticreport-api-openapi.yml
  format: yaml
  label: Health Gorilla DiagnosticReport API
  slug: health-gorilla-diagnosticreport-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-diagnosticreport-api-openapi.yml
- filename: health-gorilla-observation-api-openapi.yml
  format: yaml
  label: Health Gorilla Observation API
  slug: health-gorilla-observation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-observation-api-openapi.yml
- filename: health-gorilla-patient-api-openapi.yml
  format: yaml
  label: Health Gorilla Patient API
  slug: health-gorilla-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-patient-api-openapi.yml
- filename: health-gorilla-practitioner-api-openapi.yml
  format: yaml
  label: Health Gorilla Practitioner API
  slug: health-gorilla-practitioner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-practitioner-api-openapi.yml
- filename: health-gorilla-requestgroup-api-openapi.yml
  format: yaml
  label: Health Gorilla RequestGroup API
  slug: health-gorilla-requestgroup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-requestgroup-api-openapi.yml
- filename: health-gorilla-servicerequest-api-openapi.yml
  format: yaml
  label: Health Gorilla ServiceRequest API
  slug: health-gorilla-servicerequest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-servicerequest-api-openapi.yml
- filename: health-gorilla-capability-statement-api-openapi.yml
  format: yaml
  label: Health Gorilla Capability Statement API
  slug: health-gorilla-capability-statement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-capability-statement-api-openapi.yml
- filename: health-gorilla-document-reference-api-openapi.yml
  format: yaml
  label: Health Gorilla Document Reference API
  slug: health-gorilla-document-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/health-gorilla/openapi/health-gorilla-document-reference-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We’re HITRUST R2 certified, which means that we successfully manage cybersecurity risks by exceeding industry-defined information security requirements.
    type: HITRUST R2 certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: controls relevant to data security, availability, processing, integrity, confidentiality, and privacy
    text: SOC 2 Type 2 is a stamp of approval on our controls relevant to data security, availability, processing, integrity, confidentiality, and privacy.
    type: SOC 2 Type 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Complying with applicable health data laws, including HIPAA, is ingrained in our culture, processes, and staff training.
    type: compliance with HIPAA
  trust_center:
    url: https://www.healthgorilla.com/home/company/health-data-security
frameworks:
- HIPAA
- HITRUST
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Health Gorilla
provenance_date: '2026-11-09'
provider_name: Health Gorilla
provider_slug: health-gorilla
slug: health-gorilla-compliance
source_date: '2026-11-09'
source_filename: health-gorilla-compliance.yml
source_heading: Compliance
source_page: https://www.healthgorilla.com/home/company/health-data-security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Health Gorilla\naid: health-gorilla\nurl: https://www.healthgorilla.com/home/company/health-data-security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.healthgorilla.com/home/company/health-data-security\nattestations:\n- framework: HITRUST\n  type: HITRUST R2 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We’re HITRUST R2 certified, which means that we successfully manage cybersecurity risks by exceeding industry-defined\n    information security requirements.\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: controls relevant to data security,\
  \ availability, processing, integrity, confidentiality, and privacy\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 is a stamp of approval on our controls relevant to data security, availability, processing,\n    integrity, confidentiality, and privacy.\n- framework: HIPAA\n  type: compliance with HIPAA\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Complying with applicable health data laws, including HIPAA, is ingrained in our culture, processes, and\n    staff training.\n"
source_yaml_url: https://artifacts.apis.io/health-gorilla/compliance/health-gorilla-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Health Gorilla's own page on 2026-11-09.
synthetic: false
tags:
- Health
- Interoperability
- FHIR
- Clinical Data
- Lab Ordering
- TEFCA
- QHIN
- Health Information Exchange
- Lab Results
- Clinical Documents
- SMART on FHIR
- Patient Records
- HL7
---
