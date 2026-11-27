---
api_specs:
- filename: peachpayments-authentication-api-openapi.yml
  format: yaml
  label: Peach Payments Authentication API
  slug: peachpayments-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peachpayments/openapi/peachpayments-authentication-api-openapi.yml
- filename: peachpayments-checkout-api-openapi.yml
  format: yaml
  label: Peach Payments Checkout API
  slug: peachpayments-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peachpayments/openapi/peachpayments-checkout-api-openapi.yml
- filename: peachpayments-payment-links-api-openapi.yml
  format: yaml
  label: Peach Payments Payment Links API
  slug: peachpayments-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peachpayments/openapi/peachpayments-payment-links-api-openapi.yml
- filename: peachpayments-payments-api-openapi.yml
  format: yaml
  label: Peach Payments API
  slug: peachpayments-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peachpayments/openapi/peachpayments-payments-api-openapi.yml
- filename: peachpayments-payouts-api-openapi.yml
  format: yaml
  label: Peach Payments Payouts API
  slug: peachpayments-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peachpayments/openapi/peachpayments-payouts-api-openapi.yml
- filename: peachpayments-reconciliation-api-openapi.yml
  format: yaml
  label: Peach Payments Reconciliation API
  slug: peachpayments-reconciliation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peachpayments/openapi/peachpayments-reconciliation-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS Level 1 Certified
    type: Level 1 certification
  trust_center:
    url: https://www.peachpayments.com/security
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Peach Payments
provenance_date: '2026-11-10'
provider_name: Peach Payments
provider_slug: peachpayments
slug: peachpayments-compliance
source_date: '2026-11-10'
source_filename: peachpayments-compliance.yml
source_heading: Compliance
source_page: https://www.peachpayments.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Peach Payments\naid: peachpayments\nurl: https://www.peachpayments.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/peachpayments-trust-center.yml\ntrust_center:\n  url: https://www.peachpayments.com/security\nattestations:\n- framework: PCI-DSS\n  type: Level 1 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS Level 1 Certified\n"
source_yaml_url: https://artifacts.apis.io/peachpayments/compliance/peachpayments-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Peach Payments's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Fintech
- Africa
- Payment Gateway
- Checkout
- Payouts
---
