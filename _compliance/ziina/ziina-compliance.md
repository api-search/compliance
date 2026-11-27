---
api_specs:
- filename: ziina-account-api-openapi.yml
  format: yaml
  label: Ziina Account API
  slug: ziina-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ziina/openapi/ziina-account-api-openapi.yml
- filename: ziina-log-api-openapi.yml
  format: yaml
  label: Ziina Log API
  slug: ziina-log-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ziina/openapi/ziina-log-api-openapi.yml
- filename: ziina-paymentintent-api-openapi.yml
  format: yaml
  label: Ziina PaymentIntent API
  slug: ziina-paymentintent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ziina/openapi/ziina-paymentintent-api-openapi.yml
- filename: ziina-refund-api-openapi.yml
  format: yaml
  label: Ziina Refund API
  slug: ziina-refund-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ziina/openapi/ziina-refund-api-openapi.yml
- filename: ziina-transfer-api-openapi.yml
  format: yaml
  label: Ziina Transfer API
  slug: ziina-transfer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ziina/openapi/ziina-transfer-api-openapi.yml
- filename: ziina-webhook-api-openapi.yml
  format: yaml
  label: Ziina Webhook API
  slug: ziina-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ziina/openapi/ziina-webhook-api-openapi.yml
- filename: ziina-health-check-api-openapi.yml
  format: yaml
  label: Ziina Health Check API
  slug: ziina-health-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ziina/openapi/ziina-health-check-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: other
    issuer: Central Bank of the UAE
    period: null
    report_access: unstated
    scope: Ziina Payment LLC
    text: Ziina Payment LLC is licensed and regulated by the Central Bank of the UAE.
    type: licence and regulation
  trust_center:
    url: https://ziina.com/help-center/7915275-is-ziina-safe-to-use
frameworks:
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ziina
provenance_date: '2026-11-10'
provider_name: Ziina
provider_slug: ziina
slug: ziina-compliance
source_date: '2026-11-10'
source_filename: ziina-compliance.yml
source_heading: Compliance
source_page: https://ziina.com/help-center/7915275-is-ziina-safe-to-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ziina\naid: ziina\nurl: https://ziina.com/help-center/7915275-is-ziina-safe-to-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/ziina-trust-center.yml\ntrust_center:\n  url: https://ziina.com/help-center/7915275-is-ziina-safe-to-use\nattestations:\n- framework: other\n  type: licence and regulation\n  scope: Ziina Payment LLC\n  period: null\n  issuer: Central Bank of the UAE\n  report_access: unstated\n  text: Ziina Payment LLC is licensed and regulated by the Central Bank of the UAE.\n"
source_yaml_url: https://artifacts.apis.io/ziina/compliance/ziina-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Ziina's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Fintech
- United Arab Emirates
- MENA
- Money Transfer
- Wallets
---
