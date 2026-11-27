---
api_specs:
- filename: pointcheckout-branches-api-openapi.yml
  format: yaml
  label: PointCheckout Branches API
  slug: pointcheckout-branches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointcheckout/openapi/pointcheckout-branches-api-openapi.yml
- filename: pointcheckout-checkout-api-openapi.yml
  format: yaml
  label: PointCheckout Checkout API
  slug: pointcheckout-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointcheckout/openapi/pointcheckout-checkout-api-openapi.yml
- filename: pointcheckout-customer-subscription-api-openapi.yml
  format: yaml
  label: PointCheckout Customer subscription API
  slug: pointcheckout-customer-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointcheckout/openapi/pointcheckout-customer-subscription-api-openapi.yml
- filename: pointcheckout-webhooks-api-openapi.yml
  format: yaml
  label: PointCheckout Webhooks API
  slug: pointcheckout-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointcheckout/openapi/pointcheckout-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Paymennt.com is PCI DSS Level 1 compliant.
    type: compliance claim
  trust_center:
    url: https://www.paymennt.com/%20(footer%20/%20security%20statement
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PointCheckout
provenance_date: '2026-11-10'
provider_name: PointCheckout
provider_slug: pointcheckout
slug: pointcheckout-compliance
source_date: '2026-11-10'
source_filename: pointcheckout-compliance.yml
source_heading: Compliance
source_page: https://www.paymennt.com/%20(footer%20/%20security%20statement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PointCheckout\naid: pointcheckout\nurl: https://www.paymennt.com/%20(footer%20/%20security%20statement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/pointcheckout-trust-center.yml\ntrust_center:\n  url: https://www.paymennt.com/%20(footer%20/%20security%20statement\nattestations:\n- framework: PCI-DSS\n  type: compliance claim\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Paymennt.com is PCI DSS Level 1 compliant.\n"
source_yaml_url: https://artifacts.apis.io/pointcheckout/compliance/pointcheckout-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from PointCheckout's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Checkout
- Subscription
- Rewards
- Loyalty
- Webhook
- MENA
- E-Commerce
---
