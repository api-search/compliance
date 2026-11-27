---
api_specs:
- filename: predoc-authentication-api-openapi.yml
  format: yaml
  label: Predoc Authentication API
  slug: predoc-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/predoc/openapi/predoc-authentication-api-openapi.yml
- filename: predoc-documents-api-openapi.yml
  format: yaml
  label: Predoc Documents API
  slug: predoc-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/predoc/openapi/predoc-documents-api-openapi.yml
- filename: predoc-events-api-openapi.yml
  format: yaml
  label: Predoc Events API
  slug: predoc-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/predoc/openapi/predoc-events-api-openapi.yml
- filename: predoc-patient-api-openapi.yml
  format: yaml
  label: Predoc Patient API
  slug: predoc-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/predoc/openapi/predoc-patient-api-openapi.yml
- filename: predoc-record-request-api-openapi.yml
  format: yaml
  label: Predoc Record Request API
  slug: predoc-record-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/predoc/openapi/predoc-record-request-api-openapi.yml
- filename: predoc-record-upload-api-openapi.yml
  format: yaml
  label: Predoc Record Upload API
  slug: predoc-record-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/predoc/openapi/predoc-record-upload-api-openapi.yml
- filename: predoc-retrieval-api-openapi.yml
  format: yaml
  label: Predoc Retrieval API
  slug: predoc-retrieval-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/predoc/openapi/predoc-retrieval-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Privacy and Security Rules
    text: Full compliance with the Health Insurance Portability and Accountability Act (HIPAA) Privacy and Security Rules.
    type: compliance statement
  - framework: SOC2
    issuer: independent auditors
    period: null
    report_access: nda
    scope: Security, Availability, and Confidentiality
    text: Audit report available under NDA for qualified prospects
    type: Type II audit
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: electronic records and signatures for clinical research customers
    text: Predoc meets FDA requirements for electronic records and signatures.
    type: FDA 21 CFR Part 11 electronic records compliance
  trust_center:
    url: https://www.predoc.ai/security-compliance
frameworks:
- HIPAA
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Predoc
provenance_date: '2026-11-10'
provider_name: Predoc
provider_slug: predoc
slug: predoc-compliance
source_date: '2026-11-10'
source_filename: predoc-compliance.yml
source_heading: Compliance
source_page: https://www.predoc.ai/security-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Predoc\naid: predoc\nurl: https://www.predoc.ai/security-compliance\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.predoc.ai/security-compliance\nattestations:\n- framework: HIPAA\n  type: compliance statement\n  scope: Privacy and Security Rules\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Full compliance with the Health Insurance Portability and Accountability Act (HIPAA) Privacy and Security\n    Rules.\n- framework: SOC2\n  type: Type II audit\n  scope: Security, Availability, and Confidentiality\n  period: null\n  issuer: independent auditors\n  report_access: nda\n \
  \ text: Audit report available under NDA for qualified prospects\n- framework: other\n  type: FDA 21 CFR Part 11 electronic records compliance\n  scope: electronic records and signatures for clinical research customers\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Predoc meets FDA requirements for electronic records and signatures.\n"
source_yaml_url: https://artifacts.apis.io/predoc/compliance/predoc-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Predoc's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Medical Records
- Health Information Exchange
- FHIR
- Clinical Data
- Artificial Intelligence
- Interoperability
- EHR Integration
- Webhook
- Clinical Research
---
