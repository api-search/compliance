---
api_specs:
- filename: doku-access-token-api-openapi.yml
  format: yaml
  label: DOKU Access Token API
  slug: doku-access-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doku/openapi/doku-access-token-api-openapi.yml
- filename: doku-checkout-api-openapi.yml
  format: yaml
  label: DOKU Checkout API
  slug: doku-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doku/openapi/doku-checkout-api-openapi.yml
- filename: doku-direct-debit-e-wallet-api-openapi.yml
  format: yaml
  label: DOKU Direct Debit & e-Wallet API
  slug: doku-direct-debit-e-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doku/openapi/doku-direct-debit-e-wallet-api-openapi.yml
- filename: doku-payout-api-openapi.yml
  format: yaml
  label: DOKU Payout API
  slug: doku-payout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doku/openapi/doku-payout-api-openapi.yml
- filename: doku-qris-api-openapi.yml
  format: yaml
  label: DOKU QRIS API
  slug: doku-qris-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doku/openapi/doku-qris-api-openapi.yml
- filename: doku-virtual-account-api-openapi.yml
  format: yaml
  label: DOKU Virtual Account API
  slug: doku-virtual-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doku/openapi/doku-virtual-account-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: Visa Global Registry of Service
    period: null
    report_access: unstated
    scope: Credit card transactions for PT Nusa Satu Inti Artha and Simplepay Gateway Sdn Bhd (dba DOKU)
    text: holds PCI-DSS (Payment Card Industry Data Security Standard) Level 1 Service Provider
    type: PCI-DSS Level 1 Service Provider
  trust_center:
    url: https://docs.doku.com/security/licenses
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: DOKU
provenance_date: '2026-11-09'
provider_name: DOKU
provider_slug: doku
slug: doku-compliance
source_date: '2026-11-09'
source_filename: doku-compliance.yml
source_heading: Compliance
source_page: https://docs.doku.com/security/licenses
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: DOKU\naid: doku\nurl: https://docs.doku.com/security/licenses\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://docs.doku.com/security/licenses\nattestations:\n- framework: PCI-DSS\n  type: PCI-DSS Level 1 Service Provider\n  scope: Credit card transactions for PT Nusa Satu Inti Artha and Simplepay Gateway Sdn Bhd (dba DOKU)\n  period: null\n  issuer: Visa Global Registry of Service\n  report_access: unstated\n  text: holds PCI-DSS (Payment Card Industry Data Security Standard) Level 1 Service Provider\n"
source_yaml_url: https://artifacts.apis.io/doku/compliance/doku-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from DOKU's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Payment Gateway
- Fintech
- Indonesia
- SEA
- SNAP
- Virtual Accounts
- Digital Wallet
- QRIS
- Direct Debit
- Payouts
---
