---
api_specs:
- filename: digio-documents-api-openapi.yml
  format: yaml
  label: Digio Documents API
  slug: digio-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digio/openapi/digio-documents-api-openapi.yml
- filename: digio-emandate-api-openapi.yml
  format: yaml
  label: Digio eMandate API
  slug: digio-emandate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digio/openapi/digio-emandate-api-openapi.yml
- filename: digio-kyc-api-openapi.yml
  format: yaml
  label: Digio KYC API
  slug: digio-kyc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digio/openapi/digio-kyc-api-openapi.yml
- filename: digio-client-api-openapi.yml
  format: yaml
  label: Digio Client API
  slug: digio-client-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digio/openapi/digio-client-api-openapi.yml
- filename: digio-form-api-openapi.yml
  format: yaml
  label: Digio Form API
  slug: digio-form-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digio/openapi/digio-form-api-openapi.yml
- filename: digio-sign-api-openapi.yml
  format: yaml
  label: Digio Sign API
  slug: digio-sign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digio/openapi/digio-sign-api-openapi.yml
- filename: digio-user-api-openapi.yml
  format: yaml
  label: Digio User API
  slug: digio-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digio/openapi/digio-user-api-openapi.yml
- filename: digio-e-sign-api-openapi.yml
  format: yaml
  label: Digio e Sign API
  slug: digio-e-sign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digio/openapi/digio-e-sign-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 Certified
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Compliant
    type: null
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: RBI Authorised Payment Aggregator Certificate of Authorisation No. 166/2024
    type: RBI Authorised Payment Aggregator
  trust_center:
    url: https://www.digio.in/
frameworks:
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Digio
provenance_date: '2026-11-09'
provider_name: Digio
provider_slug: digio
slug: digio-compliance
source_date: '2026-11-09'
source_filename: digio-compliance.yml
source_heading: Compliance
source_page: https://www.digio.in/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Digio\naid: digio\nurl: https://www.digio.in/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/digio-trust-center.yml\ntrust_center:\n  url: https://www.digio.in/\nattestations:\n- framework: ISO27001\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Certified\n- framework: SOC2\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Compliant\n- framework: other\n  type: RBI Authorised Payment Aggregator\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: RBI Authorised\
  \ Payment Aggregator Certificate of Authorisation No. 166/2024\n"
source_yaml_url: https://artifacts.apis.io/digio/compliance/digio-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Digio's own page on 2026-11-09.
synthetic: false
tags:
- E-Signature
- KYC
- eNACH
- eMandate
- Digital Signature
- India
- Fintech
- Identity Verification
---
