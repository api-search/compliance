---
api_specs:
- filename: maesn-accounting-api-openapi.yml
  format: yaml
  label: Maesn Accounting API
  slug: maesn-accounting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maesn/openapi/maesn-accounting-api-openapi.yml
- filename: maesn-auth-api-openapi.yml
  format: yaml
  label: Maesn Auth API
  slug: maesn-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maesn/openapi/maesn-auth-api-openapi.yml
- filename: maesn-tenants-api-openapi.yml
  format: yaml
  label: Maesn Tenants API
  slug: maesn-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maesn/openapi/maesn-tenants-api-openapi.yml
- filename: maesn-user-api-openapi.yml
  format: yaml
  label: Maesn User API
  slug: maesn-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maesn/openapi/maesn-user-api-openapi.yml
- filename: maesn-webhook-api-openapi.yml
  format: yaml
  label: Maesn Webhook API
  slug: maesn-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maesn/openapi/maesn-webhook-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Maesn
    text: Maesn is ISO 27001 certified and audited every year. You can find the current certificate in our Trust Center.
    type: certification
  - framework: GDPR
    issuer: null
    period: annual
    report_access: on_request
    scope: Maesn
    text: We run annual GDPR audits and process data to the strictest European standards. Audit reports are available in the Trust Center.
    type: annual GDPR audits
  trust_center:
    url: https://www.maesn.com/security/
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Maesn
provenance_date: '2026-11-10'
provider_name: Maesn
provider_slug: maesn
slug: maesn-compliance
source_date: '2026-11-10'
source_filename: maesn-compliance.yml
source_heading: Compliance
source_page: https://www.maesn.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Maesn\naid: maesn\nurl: https://www.maesn.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.maesn.com/security/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Maesn\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Maesn is ISO 27001 certified and audited every year. You can find the current certificate in our Trust Center.\n- framework: GDPR\n  type: annual GDPR audits\n  scope: Maesn\n  period: annual\n  issuer: null\n  report_access: on_request\n  text: We run annual GDPR audits and process data to the strictest European standards. Audit\
  \ reports are available\n    in the Trust Center.\n"
source_yaml_url: https://artifacts.apis.io/maesn/compliance/maesn-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Maesn's own page on 2026-11-10.
synthetic: false
tags:
- ERP
- Accounting
- Integration
- Software-as-a-Service
---
