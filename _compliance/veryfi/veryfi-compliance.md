---
api_specs:
- filename: veryfi-any-documents-api-openapi.yml
  format: yaml
  label: Veryfi Any Documents API
  slug: veryfi-any-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veryfi/openapi/veryfi-any-documents-api-openapi.yml
- filename: veryfi-bank-statements-api-openapi.yml
  format: yaml
  label: Veryfi Bank Statements API
  slug: veryfi-bank-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veryfi/openapi/veryfi-bank-statements-api-openapi.yml
- filename: veryfi-checks-api-openapi.yml
  format: yaml
  label: Veryfi Checks API
  slug: veryfi-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veryfi/openapi/veryfi-checks-api-openapi.yml
- filename: veryfi-classification-api-openapi.yml
  format: yaml
  label: Veryfi Classification API
  slug: veryfi-classification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veryfi/openapi/veryfi-classification-api-openapi.yml
- filename: veryfi-documents-api-openapi.yml
  format: yaml
  label: Veryfi Documents API
  slug: veryfi-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veryfi/openapi/veryfi-documents-api-openapi.yml
- filename: veryfi-w-2-forms-api-openapi.yml
  format: yaml
  label: Veryfi W-2 Forms API
  slug: veryfi-w-2-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veryfi/openapi/veryfi-w-2-forms-api-openapi.yml
- filename: veryfi-w-9-forms-api-openapi.yml
  format: yaml
  label: Veryfi W-9 Forms API
  slug: veryfi-w-9-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veryfi/openapi/veryfi-w-9-forms-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Veryfi platform
    text: Upon request, a SOC 2 Type 2 report will outline how Veryfi safeguards customer data.
    type: Type 2 certified
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: PII data processed by Veryfi OCR API
    text: Veryfi will sign a BAA upon request to protect sensitive PII data processed by Veryfi OCR API.
    type: BAA available
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR, CCPA, HIPAA Compliant
    type: compliance statement
  trust_center:
    url: https://www.veryfi.com/security
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Veryfi
provenance_date: '2026-11-10'
provider_name: Veryfi
provider_slug: veryfi
slug: veryfi-compliance
source_date: '2026-11-10'
source_filename: veryfi-compliance.yml
source_heading: Compliance
source_page: https://www.veryfi.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Veryfi\naid: veryfi\nurl: https://www.veryfi.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/veryfi-trust-center.yml\ntrust_center:\n  url: https://www.veryfi.com/security\nattestations:\n- framework: SOC2\n  type: Type 2 certified\n  scope: Veryfi platform\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Upon request, a SOC 2 Type 2 report will outline how Veryfi safeguards customer data.\n- framework: HIPAA\n  type: BAA available\n  scope: PII data processed by Veryfi OCR API\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Veryfi will sign a\
  \ BAA upon request to protect sensitive PII data processed by Veryfi OCR API.\n- framework: GDPR\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR, CCPA, HIPAA Compliant\n"
source_yaml_url: https://artifacts.apis.io/veryfi/compliance/veryfi-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Veryfi's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Document Processing
- Finance
- Invoices
- OCR
- Receipts
- Tax Forms
---
