---
api_specs:
- filename: anrok-customer-certificates-api-openapi.yml
  format: yaml
  label: Anrok Customer certificates API
  slug: anrok-customer-certificates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anrok/openapi/anrok-customer-certificates-api-openapi.yml
- filename: anrok-filings-api-openapi.yml
  format: yaml
  label: Anrok Filings API
  slug: anrok-filings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anrok/openapi/anrok-filings-api-openapi.yml
- filename: anrok-product-mappings-api-openapi.yml
  format: yaml
  label: Anrok Product mappings API
  slug: anrok-product-mappings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anrok/openapi/anrok-product-mappings-api-openapi.yml
- filename: anrok-products-api-openapi.yml
  format: yaml
  label: Anrok Products API
  slug: anrok-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anrok/openapi/anrok-products-api-openapi.yml
- filename: anrok-tax-id-validation-api-openapi.yml
  format: yaml
  label: Anrok Tax ID validation API
  slug: anrok-tax-id-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anrok/openapi/anrok-tax-id-validation-api-openapi.yml
- filename: anrok-transactions-api-openapi.yml
  format: yaml
  label: Anrok Transactions API
  slug: anrok-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anrok/openapi/anrok-transactions-api-openapi.yml
- filename: anrok-address-resolution-api-openapi.yml
  format: yaml
  label: Anrok Address resolution API
  slug: anrok-address-resolution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anrok/openapi/anrok-address-resolution-api-openapi.yml
- filename: anrok-customers-api-openapi.yml
  format: yaml
  label: Anrok Customers API
  slug: anrok-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anrok/openapi/anrok-customers-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: independent firm
    period: null
    report_access: unstated
    scope: internal controls relevant to customer financial reporting
    text: Anrok is SOC 1 Type II compliant.
    type: SOC 1 Type II
  - framework: SOC2
    issuer: independent firm
    period: null
    report_access: unstated
    scope: Security, Availability, and Confidentiality trust services criteria
    text: Anrok is SOC 2 Type II compliant.
    type: SOC 2 Type II
  trust_center:
    url: https://www.anrok.com/security
frameworks:
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Anrok
provenance_date: '2026-11-09'
provider_name: Anrok
provider_slug: anrok
slug: anrok-compliance
source_date: '2026-11-09'
source_filename: anrok-compliance.yml
source_heading: Compliance
source_page: https://www.anrok.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Anrok\naid: anrok\nurl: https://www.anrok.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/anrok-trust-center.yml\ntrust_center:\n  url: https://www.anrok.com/security\nattestations:\n- framework: SOC1\n  type: SOC 1 Type II\n  scope: internal controls relevant to customer financial reporting\n  period: null\n  issuer: independent firm\n  report_access: unstated\n  text: Anrok is SOC 1 Type II compliant.\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Security, Availability, and Confidentiality trust services criteria\n  period: null\n  issuer: independent firm\n  report_access: unstated\n\
  \  text: Anrok is SOC 2 Type II compliant.\n"
source_yaml_url: https://artifacts.apis.io/anrok/compliance/anrok-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Anrok's own page on 2026-11-09.
synthetic: false
tags:
- Sales Tax
- VAT
- Tax Compliance
- Software-as-a-Service
- Fintech
- Tax Automation
- Nexus
- E-Invoicing
- Tax
---
