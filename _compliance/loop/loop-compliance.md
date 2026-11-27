---
api_specs:
- filename: loop-artifacts-api-openapi.yml
  format: yaml
  label: Loop Artifacts API
  slug: loop-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-artifacts-api-openapi.yml
- filename: loop-artifacts-schema-validated-api-openapi.yml
  format: yaml
  label: Loop Artifacts Schema Validated API
  slug: loop-artifacts-schema-validated-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-artifacts-schema-validated-api-openapi.yml
- filename: loop-business-exceptions-api-openapi.yml
  format: yaml
  label: Loop Business Exceptions API
  slug: loop-business-exceptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-business-exceptions-api-openapi.yml
- filename: loop-factoring-relationships-api-openapi.yml
  format: yaml
  label: Loop Factoring Relationships API
  slug: loop-factoring-relationships-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-factoring-relationships-api-openapi.yml
- filename: loop-invoicing-relationships-api-openapi.yml
  format: yaml
  label: Loop Invoicing Relationships API
  slug: loop-invoicing-relationships-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-invoicing-relationships-api-openapi.yml
- filename: loop-onboarding-api-loop-com-api-openapi.yml
  format: yaml
  label: Loop Onboarding.api.loop.com API
  slug: loop-onboarding-api-loop-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-onboarding-api-loop-com-api-openapi.yml
- filename: loop-organizations-api-openapi.yml
  format: yaml
  label: Loop Organizations API
  slug: loop-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-organizations-api-openapi.yml
- filename: loop-payable-allocations-api-openapi.yml
  format: yaml
  label: Loop Payable Allocations API
  slug: loop-payable-allocations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-payable-allocations-api-openapi.yml
- filename: loop-payable-invoice-reviews-api-openapi.yml
  format: yaml
  label: Loop Payable Invoice Reviews API
  slug: loop-payable-invoice-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-payable-invoice-reviews-api-openapi.yml
- filename: loop-payable-invoices-api-openapi.yml
  format: yaml
  label: Loop Payable Invoices API
  slug: loop-payable-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-payable-invoices-api-openapi.yml
- filename: loop-payments-api-openapi.yml
  format: yaml
  label: Loop Payments API
  slug: loop-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-payments-api-openapi.yml
- filename: loop-ping-api-openapi.yml
  format: yaml
  label: Loop Ping API
  slug: loop-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-ping-api-openapi.yml
- filename: loop-receivable-invoices-api-openapi.yml
  format: yaml
  label: Loop Receivable Invoices API
  slug: loop-receivable-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-receivable-invoices-api-openapi.yml
- filename: loop-shipment-jobs-api-openapi.yml
  format: yaml
  label: Loop Shipment Jobs API
  slug: loop-shipment-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loop/openapi/loop-shipment-jobs-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: SOC 2 Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliance Policy
    type: HIPAA compliance
  trust_center:
    url: https://trust.loop.com/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Loop
provenance_date: '2026-11-09'
provider_name: Loop
provider_slug: loop
slug: loop-compliance
source_date: '2026-11-09'
source_filename: loop-compliance.yml
source_heading: Compliance
source_page: https://trust.loop.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Loop\naid: loop\nurl: https://trust.loop.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.loop.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliance Policy\n"
source_yaml_url: https://artifacts.apis.io/loop/compliance/loop-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Loop's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Supply Chain
- Freight
- Freight Audit
- Payments
- Transportation
- Artificial Intelligence
- Data Platform
---
