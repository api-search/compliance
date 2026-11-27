---
api_specs:
- filename: payjp-3d-secure-api-openapi.yml
  format: yaml
  label: PAY.JP 3D Secure API
  slug: payjp-3d-secure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-3d-secure-api-openapi.yml
- filename: payjp-account-api-openapi.yml
  format: yaml
  label: PAY.JP Account API
  slug: payjp-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-account-api-openapi.yml
- filename: payjp-balances-api-openapi.yml
  format: yaml
  label: PAY.JP Balances API
  slug: payjp-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-balances-api-openapi.yml
- filename: payjp-cards-api-openapi.yml
  format: yaml
  label: PAY.JP Cards API
  slug: payjp-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-cards-api-openapi.yml
- filename: payjp-charges-api-openapi.yml
  format: yaml
  label: PAY.JP Charges API
  slug: payjp-charges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-charges-api-openapi.yml
- filename: payjp-customers-api-openapi.yml
  format: yaml
  label: PAY.JP Customers API
  slug: payjp-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-customers-api-openapi.yml
- filename: payjp-events-api-openapi.yml
  format: yaml
  label: PAY.JP Events API
  slug: payjp-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-events-api-openapi.yml
- filename: payjp-plans-api-openapi.yml
  format: yaml
  label: PAY.JP Plans API
  slug: payjp-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-plans-api-openapi.yml
- filename: payjp-platform-api-openapi.yml
  format: yaml
  label: PAY.JP Platform API
  slug: payjp-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-platform-api-openapi.yml
- filename: payjp-statements-api-openapi.yml
  format: yaml
  label: PAY.JP Statements API
  slug: payjp-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-statements-api-openapi.yml
- filename: payjp-subscriptions-api-openapi.yml
  format: yaml
  label: PAY.JP Subscriptions API
  slug: payjp-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-subscriptions-api-openapi.yml
- filename: payjp-terms-api-openapi.yml
  format: yaml
  label: PAY.JP Terms API
  slug: payjp-terms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-terms-api-openapi.yml
- filename: payjp-tokens-api-openapi.yml
  format: yaml
  label: PAY.JP Tokens API
  slug: payjp-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-tokens-api-openapi.yml
- filename: payjp-transfers-api-openapi.yml
  format: yaml
  label: PAY.JP Transfers API
  slug: payjp-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjp/openapi/payjp-transfers-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: PAY.JPは、PCI DSS Version 4.0 Level 1 Service Provider です。
    type: Level 1 Service Provider
  trust_center:
    url: https://pay.jp/security
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PAY.JP
provenance_date: '2026-11-10'
provider_name: PAY.JP
provider_slug: payjp
slug: payjp-compliance
source_date: '2026-11-10'
source_filename: payjp-compliance.yml
source_heading: Compliance
source_page: https://pay.jp/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PAY.JP\naid: payjp\nurl: https://pay.jp/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://pay.jp/security\nattestations:\n- framework: PCI-DSS\n  type: Level 1 Service Provider\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: PAY.JPは、PCI DSS Version 4.0 Level 1 Service Provider です。\n"
source_yaml_url: https://artifacts.apis.io/payjp/compliance/payjp-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from PAY.JP's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Fintech
- Japan
- Credit Cards
- Subscription
- Tokenization
---
