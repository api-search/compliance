---
api_specs:
- filename: polly-io-event-types-api-openapi.yml
  format: yaml
  label: Polly Event Types API
  slug: polly-io-event-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polly-io/openapi/polly-io-event-types-api-openapi.yml
- filename: polly-io-lock-confirmation-documents-api-openapi.yml
  format: yaml
  label: Polly Lock Confirmation Documents API
  slug: polly-io-lock-confirmation-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polly-io/openapi/polly-io-lock-confirmation-documents-api-openapi.yml
- filename: polly-io-mi-quotes-api-openapi.yml
  format: yaml
  label: Polly Mi Quotes API
  slug: polly-io-mi-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polly-io/openapi/polly-io-mi-quotes-api-openapi.yml
- filename: polly-io-webhooks-api-openapi.yml
  format: yaml
  label: Polly Webhooks API
  slug: polly-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polly-io/openapi/polly-io-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: InfoSec management systems
    text: ISO/IEC 27001 Certificate available upon request.
    type: Certification
  - framework: SOC2
    issuer: licensed CPA firm
    period: null
    report_access: nda
    scope: AICPA Trust Services Criteria
    text: The full report is available under NDA.
    type: SOC 2 Type II Attestation
  trust_center:
    url: https://polly.io/vendor-due-diligence
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Polly
provenance_date: '2026-11-10'
provider_name: Polly
provider_slug: polly-io
slug: polly-io-compliance
source_date: '2026-11-10'
source_filename: polly-io-compliance.yml
source_heading: Compliance
source_page: https://polly.io/vendor-due-diligence
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Polly\naid: polly-io\nurl: https://polly.io/vendor-due-diligence\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://polly.io/vendor-due-diligence\nattestations:\n- framework: ISO27001\n  type: Certification\n  scope: InfoSec management systems\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO/IEC 27001 Certificate available upon request.\n- framework: SOC2\n  type: SOC 2 Type II Attestation\n  scope: AICPA Trust Services Criteria\n  period: null\n  issuer: licensed CPA firm\n  report_access: nda\n  text: The full report is available under NDA.\n"
source_yaml_url: https://artifacts.apis.io/polly-io/compliance/polly-io-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Polly's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Capital Markets
- Mortgage
- API Platform
- Artificial Intelligence
---
