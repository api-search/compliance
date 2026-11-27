---
api_specs:
- filename: xcures-application-api-openapi.yml
  format: yaml
  label: xCures Application API
  slug: xcures-application-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-application-api-openapi.yml
- filename: xcures-checklist-api-openapi.yml
  format: yaml
  label: xCures Checklist API
  slug: xcures-checklist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-checklist-api-openapi.yml
- filename: xcures-clinical-concepts-api-openapi.yml
  format: yaml
  label: xCures Clinical Concepts API
  slug: xcures-clinical-concepts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-clinical-concepts-api-openapi.yml
- filename: xcures-document-api-openapi.yml
  format: yaml
  label: xCures Document API
  slug: xcures-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-document-api-openapi.yml
- filename: xcures-fhir-api-openapi.yml
  format: yaml
  label: xCures FHIR API
  slug: xcures-fhir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-fhir-api-openapi.yml
- filename: xcures-project-api-openapi.yml
  format: yaml
  label: xCures Project API
  slug: xcures-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-project-api-openapi.yml
- filename: xcures-query-api-openapi.yml
  format: yaml
  label: xCures Query API
  slug: xcures-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-query-api-openapi.yml
- filename: xcures-reciprocity-template-api-openapi.yml
  format: yaml
  label: xCures Reciprocity Template API
  slug: xcures-reciprocity-template-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-reciprocity-template-api-openapi.yml
- filename: xcures-subject-api-openapi.yml
  format: yaml
  label: xCures Subject API
  slug: xcures-subject-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-subject-api-openapi.yml
- filename: xcures-summary-api-openapi.yml
  format: yaml
  label: xCures Summary API
  slug: xcures-summary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-summary-api-openapi.yml
- filename: xcures-oauth-api-openapi.yml
  format: yaml
  label: xCures O Auth API
  slug: xcures-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xcures/openapi/xcures-oauth-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: xCures Clinical Clarity Engine
    text: The xCures Clinical Clarity Engine is HITRUST i1 certified .
    type: i1 certification
  - framework: HIPAA
    issuer: null
    period: annual
    report_access: unstated
    scope: xCures Clinical Clarity Engine
    text: HIPAA Compliant with annual HIPAA Evaluation and HITRUST certification program.
    type: HIPAA compliance with annual HIPAA evaluation
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: AWS infrastructure
    text: HITRUST r2 Certification
    type: r2 certification (AWS, inherited controls)
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: AWS infrastructure
    text: ISO 27001 2022 Certification
    type: 2022 certification (AWS)
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: AWS infrastructure
    text: SOC2 Type2 Attestation
    type: Type 2 attestation (AWS)
  trust_center:
    url: https://xcures.com/trust/
frameworks:
- HIPAA
- HITRUST
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: xCures
provenance_date: '2026-11-10'
provider_name: xCures
provider_slug: xcures
slug: xcures-compliance
source_date: '2026-11-10'
source_filename: xcures-compliance.yml
source_heading: Compliance
source_page: https://xcures.com/trust/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: xCures\naid: xcures\nurl: https://xcures.com/trust/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://xcures.com/trust/\nattestations:\n- framework: HITRUST\n  type: i1 certification\n  scope: xCures Clinical Clarity Engine\n  period: null\n  issuer: null\n  report_access: unstated\n  text: The xCures Clinical Clarity Engine is HITRUST i1 certified .\n- framework: HIPAA\n  type: HIPAA compliance with annual HIPAA evaluation\n  scope: xCures Clinical Clarity Engine\n  period: annual\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant with annual HIPAA Evaluation and HITRUST certification\
  \ program.\n- framework: HITRUST\n  type: r2 certification (AWS, inherited controls)\n  scope: AWS infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HITRUST r2 Certification\n- framework: ISO27001\n  type: 2022 certification (AWS)\n  scope: AWS infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 2022 Certification\n- framework: SOC2\n  type: Type 2 attestation (AWS)\n  scope: AWS infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 Type2 Attestation\n"
source_yaml_url: https://artifacts.apis.io/xcures/compliance/xcures-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from xCures's own page on 2026-11-10.
synthetic: false
tags:
- Health
- Healthcare
- Medical Records
- Interoperability
- FHIR
- Oncology
- Real-World Data
- Clinical Data
- Artificial Intelligence
- TEFCA
- Carequality
- Patient Data
- HITRUST
- HIPAA
- A2A
---
