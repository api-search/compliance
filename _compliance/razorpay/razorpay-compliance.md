---
api_specs:
- filename: overview
  format: yaml
  label: Razorpay Core REST API
  slug: core-api
  spec_type: Postman
  url: https://www.postman.com/razorpaydev/razorpay-public-workspace/overview
- filename: razorpay-webhooks-asyncapi.yml
  format: yaml
  label: Razorpay Webhooks
  slug: webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/razorpay/asyncapi/razorpay-webhooks-asyncapi.yml
- filename: razorpay-orders-api-openapi.yml
  format: yaml
  label: Razorpay Orders API
  slug: razorpay-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/razorpay/openapi/razorpay-orders-api-openapi.yml
- filename: razorpay-payments-api-openapi.yml
  format: yaml
  label: Razorpay Payments API
  slug: razorpay-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/razorpay/openapi/razorpay-payments-api-openapi.yml
- filename: razorpay-refunds-api-openapi.yml
  format: yaml
  label: Razorpay Refunds API
  slug: razorpay-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/razorpay/openapi/razorpay-refunds-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: payment service provider handling card data
    text: As a payment service provider dealing with card data, we have PCI-DSS certification .
    type: certification
  trust_center:
    url: https://razorpay.com/docs/us/security
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Razorpay
provenance_date: '2026-11-10'
provider_name: Razorpay
provider_slug: razorpay
slug: razorpay-compliance
source_date: '2026-11-10'
source_filename: razorpay-compliance.yml
source_heading: Compliance
source_page: https://razorpay.com/docs/us/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Razorpay\naid: razorpay\nurl: https://razorpay.com/docs/us/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/razorpay-trust-center.yml\ntrust_center:\n  url: https://razorpay.com/docs/us/security\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: payment service provider handling card data\n  period: null\n  issuer: null\n  report_access: on_request\n  text: As a payment service provider dealing with card data, we have PCI-DSS certification .\n"
source_yaml_url: https://artifacts.apis.io/razorpay/compliance/razorpay-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Razorpay's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Payment Gateway
- Fintech
- India
- UPI
- Subscription
- Payouts
- Checkout
- A2A
- Payment Processing
---
