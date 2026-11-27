---
api_specs:
- filename: paymongo-checkout-sessions-api-openapi.yml
  format: yaml
  label: PayMongo Checkout Sessions API
  slug: paymongo-checkout-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-checkout-sessions-api-openapi.yml
- filename: paymongo-customers-api-openapi.yml
  format: yaml
  label: PayMongo Customers API
  slug: paymongo-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-customers-api-openapi.yml
- filename: paymongo-payment-intents-api-openapi.yml
  format: yaml
  label: PayMongo Payment Intents API
  slug: paymongo-payment-intents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-payment-intents-api-openapi.yml
- filename: paymongo-payment-links-api-openapi.yml
  format: yaml
  label: PayMongo Payment Links API
  slug: paymongo-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-payment-links-api-openapi.yml
- filename: paymongo-payment-methods-api-openapi.yml
  format: yaml
  label: PayMongo Payment Methods API
  slug: paymongo-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-payment-methods-api-openapi.yml
- filename: paymongo-payments-api-openapi.yml
  format: yaml
  label: PayMongo Payments API
  slug: paymongo-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-payments-api-openapi.yml
- filename: paymongo-qr-ph-api-openapi.yml
  format: yaml
  label: PayMongo QR Ph API
  slug: paymongo-qr-ph-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-qr-ph-api-openapi.yml
- filename: paymongo-refunds-api-openapi.yml
  format: yaml
  label: PayMongo Refunds API
  slug: paymongo-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-refunds-api-openapi.yml
- filename: paymongo-sources-api-openapi.yml
  format: yaml
  label: PayMongo Sources API
  slug: paymongo-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-sources-api-openapi.yml
- filename: paymongo-webhooks-api-openapi.yml
  format: yaml
  label: PayMongo Webhooks API
  slug: paymongo-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: PayMongo platform card payments
    text: PayMongo is PCI-DSS Level 1 compliant, the highest level of certification
    type: certification
  trust_center:
    url: https://www.paymongo.com/secure
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PayMongo
provenance_date: '2026-11-10'
provider_name: PayMongo
provider_slug: paymongo
slug: paymongo-compliance
source_date: '2026-11-10'
source_filename: paymongo-compliance.yml
source_heading: Compliance
source_page: https://www.paymongo.com/secure
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PayMongo\naid: paymongo\nurl: https://www.paymongo.com/secure\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.paymongo.com/secure\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: PayMongo platform card payments\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PayMongo is PCI-DSS Level 1 compliant, the highest level of certification\n"
source_yaml_url: https://artifacts.apis.io/paymongo/compliance/paymongo-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from PayMongo's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Fintech
- Philippines
- Southeast Asia
- GCash
- Digital Wallet
- Card Payments
---
