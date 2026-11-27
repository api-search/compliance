---
api_specs:
- filename: zus-auth-api-openapi.yml
  format: yaml
  label: Zus Health Auth API
  slug: zus-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zus/openapi/zus-auth-api-openapi.yml
- filename: zus-documents-api-openapi.yml
  format: yaml
  label: Zus Health Documents API
  slug: zus-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zus/openapi/zus-documents-api-openapi.yml
- filename: zus-fhir-api-openapi.yml
  format: yaml
  label: Zus Health FHIR API
  slug: zus-fhir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zus/openapi/zus-fhir-api-openapi.yml
- filename: zus-patient-api-openapi.yml
  format: yaml
  label: Zus Health Patient API
  slug: zus-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zus/openapi/zus-patient-api-openapi.yml
- filename: zus-patient-history-api-openapi.yml
  format: yaml
  label: Zus Health Patient History API
  slug: zus-patient-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zus/openapi/zus-patient-history-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: data privacy
    text: We operate in compliance with HIPAA and applicable state privacy laws
    type: compliance with regulation
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: cybersecurity and information protection
    text: are HITRUST r2 and SOC 2 certified for cybersecurity and information protection
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: cybersecurity and information protection
    text: are HITRUST r2 and SOC 2 certified for cybersecurity and information protection
    type: certification
  trust_center:
    url: https://www.zushealth.com/platform
frameworks:
- HIPAA
- HITRUST
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Zus Health
provenance_date: '2026-11-10'
provider_name: Zus Health
provider_slug: zus
slug: zus-compliance
source_date: '2026-11-10'
source_filename: zus-compliance.yml
source_heading: Compliance
source_page: https://www.zushealth.com/platform
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Zus Health\naid: zus\nurl: https://www.zushealth.com/platform\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.zushealth.com/platform\nattestations:\n- framework: HIPAA\n  type: compliance with regulation\n  scope: data privacy\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We operate in compliance with HIPAA and applicable state privacy laws\n- framework: HITRUST\n  type: certification\n  scope: cybersecurity and information protection\n  period: null\n  issuer: null\n  report_access: unstated\n  text: are HITRUST r2 and SOC 2 certified for cybersecurity and information protection\n\
  - framework: SOC2\n  type: certification\n  scope: cybersecurity and information protection\n  period: null\n  issuer: null\n  report_access: unstated\n  text: are HITRUST r2 and SOC 2 certified for cybersecurity and information protection\n"
source_yaml_url: https://artifacts.apis.io/zus/compliance/zus-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Zus Health's own page on 2026-11-10.
synthetic: false
tags:
- Health
- FHIR
- Interoperability
- Patient Data
- Healthcare
---
