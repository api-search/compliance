---
api_specs:
- filename: niural-authentication-api-openapi.yml
  format: yaml
  label: Niural Authentication API
  slug: niural-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/niural/openapi/niural-authentication-api-openapi.yml
- filename: niural-contracts-api-openapi.yml
  format: yaml
  label: Niural Contracts API
  slug: niural-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/niural/openapi/niural-contracts-api-openapi.yml
- filename: niural-invoices-api-openapi.yml
  format: yaml
  label: Niural Invoices API
  slug: niural-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/niural/openapi/niural-invoices-api-openapi.yml
- filename: niural-transactions-api-openapi.yml
  format: yaml
  label: Niural Transactions API
  slug: niural-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/niural/openapi/niural-transactions-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: on_request
    scope: null
    text: Niural SOC 2 Type 2 2026 Request
    type: Type 2
  - framework: SOC2
    issuer: null
    period: '2024'
    report_access: on_request
    scope: null
    text: Niural SOC 2 Type 1 2024 Audit Request
    type: Type 1
  trust_center:
    url: https://trust.niural.com/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Niural
provenance_date: '2026-11-10'
provider_name: Niural
provider_slug: niural
slug: niural-compliance
source_date: '2026-11-10'
source_filename: niural-compliance.yml
source_heading: Compliance
source_page: https://trust.niural.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Niural\naid: niural\nurl: https://trust.niural.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.niural.com/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: on_request\n  text: Niural SOC 2 Type 2 2026 Request\n- framework: SOC2\n  type: Type 1\n  scope: null\n  period: '2024'\n  issuer: null\n  report_access: on_request\n  text: Niural SOC 2 Type 1 2024 Audit Request\n"
source_yaml_url: https://artifacts.apis.io/niural/compliance/niural-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Niural's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payroll
- Human Resources
- Employer of Record
- Contractor Management
- Global Payments
- Invoicing
- Compliance
- Fintech
---
