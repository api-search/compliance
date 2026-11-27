---
api_specs:
- filename: processout-balances-api-openapi.yml
  format: yaml
  label: ProcessOut Balances API
  slug: processout-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-balances-api-openapi.yml
- filename: processout-cards-api-openapi.yml
  format: yaml
  label: ProcessOut Cards API
  slug: processout-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-cards-api-openapi.yml
- filename: processout-customers-api-openapi.yml
  format: yaml
  label: ProcessOut Customers API
  slug: processout-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-customers-api-openapi.yml
- filename: processout-events-api-openapi.yml
  format: yaml
  label: ProcessOut Events API
  slug: processout-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-events-api-openapi.yml
- filename: processout-invoices-api-openapi.yml
  format: yaml
  label: ProcessOut Invoices API
  slug: processout-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-invoices-api-openapi.yml
- filename: processout-network-tokens-api-openapi.yml
  format: yaml
  label: ProcessOut Network Tokens API
  slug: processout-network-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-network-tokens-api-openapi.yml
- filename: processout-payouts-api-openapi.yml
  format: yaml
  label: ProcessOut Payouts API
  slug: processout-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-payouts-api-openapi.yml
- filename: processout-projects-api-openapi.yml
  format: yaml
  label: ProcessOut Projects API
  slug: processout-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-projects-api-openapi.yml
- filename: processout-transactions-api-openapi.yml
  format: yaml
  label: ProcessOut Transactions API
  slug: processout-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-transactions-api-openapi.yml
- filename: processout-uploads-api-openapi.yml
  format: yaml
  label: ProcessOut Uploads API
  slug: processout-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-uploads-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: independent entity (auditor not named)
    period: null
    report_access: unstated
    scope: ProcessOut as Service Provider
    text: ProcessOut is certified for PCI DSS Level 1 Service Provider, which is the highest possible level of PCI compliance.
    type: certification
  trust_center:
    url: https://www.processout.com/security
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ProcessOut
provenance_date: '2026-11-10'
provider_name: ProcessOut
provider_slug: processout
slug: processout-compliance
source_date: '2026-11-10'
source_filename: processout-compliance.yml
source_heading: Compliance
source_page: https://www.processout.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ProcessOut\naid: processout\nurl: https://www.processout.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.processout.com/security\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: ProcessOut as Service Provider\n  period: null\n  issuer: independent entity (auditor not named)\n  report_access: unstated\n  text: ProcessOut is certified for PCI DSS Level 1 Service Provider, which is the highest possible level of PCI\n    compliance.\n"
source_yaml_url: https://artifacts.apis.io/processout/compliance/processout-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from ProcessOut's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Payment Orchestration
- Smart Routing
- Tokenization
- Checkout
- Reconciliation
- Fraud Prevention
- 3D Secure
- Company
---
