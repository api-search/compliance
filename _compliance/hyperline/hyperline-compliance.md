---
api_specs:
- filename: hyperline-billable-events-api-openapi.yml
  format: yaml
  label: Hyperline Billable Events API
  slug: hyperline-billable-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperline/openapi/hyperline-billable-events-api-openapi.yml
- filename: hyperline-customers-api-openapi.yml
  format: yaml
  label: Hyperline Customers API
  slug: hyperline-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperline/openapi/hyperline-customers-api-openapi.yml
- filename: hyperline-invoices-api-openapi.yml
  format: yaml
  label: Hyperline Invoices API
  slug: hyperline-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperline/openapi/hyperline-invoices-api-openapi.yml
- filename: hyperline-payments-api-openapi.yml
  format: yaml
  label: Hyperline Payments API
  slug: hyperline-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperline/openapi/hyperline-payments-api-openapi.yml
- filename: hyperline-products-api-openapi.yml
  format: yaml
  label: Hyperline Products API
  slug: hyperline-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperline/openapi/hyperline-products-api-openapi.yml
- filename: hyperline-subscriptions-api-openapi.yml
  format: yaml
  label: Hyperline Subscriptions API
  slug: hyperline-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperline/openapi/hyperline-subscriptions-api-openapi.yml
- filename: hyperline-webhooks-api-openapi.yml
  format: yaml
  label: Hyperline Webhooks API
  slug: hyperline-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperline/openapi/hyperline-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC2 type 2 report
    type: Type 2 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 'ISO 27001 : 2022'
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR (In progress)
    type: in progress
  trust_center:
    url: https://trust.hyperline.co/
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Hyperline
provenance_date: '2026-11-09'
provider_name: Hyperline
provider_slug: hyperline
slug: hyperline-compliance
source_date: '2026-11-09'
source_filename: hyperline-compliance.yml
source_heading: Compliance
source_page: https://trust.hyperline.co/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Hyperline\naid: hyperline\nurl: https://trust.hyperline.co/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/hyperline-trust-center.yml\ntrust_center:\n  url: https://trust.hyperline.co/\nattestations:\n- framework: SOC2\n  type: Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 type 2 report\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'ISO 27001 : 2022'\n- framework: GDPR\n  type: in progress\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: GDPR (In progress)\n"
source_yaml_url: https://artifacts.apis.io/hyperline/compliance/hyperline-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Hyperline's own page on 2026-11-09.
synthetic: false
tags:
- Billing
- Subscription
- Usage-Based
- Metering
- Payments
- Invoicing
- FinOps
---
