---
api_specs:
- filename: dlocal-payouts-api-openapi.yml
  format: yaml
  label: dLocal Payouts API
  slug: dlocal-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dlocal/openapi/dlocal-payouts-api-openapi.yml
- filename: dlocal-accounts-api-openapi.yml
  format: yaml
  label: dLocal Accounts API
  slug: dlocal-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dlocal/openapi/dlocal-accounts-api-openapi.yml
- filename: dlocal-balance-api-openapi.yml
  format: yaml
  label: dLocal Balance API
  slug: dlocal-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dlocal/openapi/dlocal-balance-api-openapi.yml
- filename: dlocal-bank-accounts-api-openapi.yml
  format: yaml
  label: dLocal Bank Accounts API
  slug: dlocal-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dlocal/openapi/dlocal-bank-accounts-api-openapi.yml
- filename: dlocal-chargebacks-api-openapi.yml
  format: yaml
  label: dLocal Chargebacks API
  slug: dlocal-chargebacks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dlocal/openapi/dlocal-chargebacks-api-openapi.yml
- filename: dlocal-currency-api-openapi.yml
  format: yaml
  label: dLocal Currency API
  slug: dlocal-currency-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dlocal/openapi/dlocal-currency-api-openapi.yml
- filename: dlocal-documents-api-openapi.yml
  format: yaml
  label: dLocal Documents API
  slug: dlocal-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dlocal/openapi/dlocal-documents-api-openapi.yml
- filename: dlocal-kyc-api-openapi.yml
  format: yaml
  label: dLocal KYC API
  slug: dlocal-kyc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dlocal/openapi/dlocal-kyc-api-openapi.yml
- filename: dlocal-payment-methods-api-openapi.yml
  format: yaml
  label: dLocal Payment Methods API
  slug: dlocal-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dlocal/openapi/dlocal-payment-methods-api-openapi.yml
- filename: dlocal-payments-api-openapi.yml
  format: yaml
  label: dLocal Payments API
  slug: dlocal-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dlocal/openapi/dlocal-payments-api-openapi.yml
- filename: dlocal-payouts-api-openapi.yml
  format: yaml
  label: dLocal Payouts API
  slug: dlocal-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dlocal/openapi/dlocal-payouts-api-openapi.yml
- filename: dlocal-refunds-api-openapi.yml
  format: yaml
  label: dLocal Refunds API
  slug: dlocal-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dlocal/openapi/dlocal-refunds-api-openapi.yml
- filename: dlocal-tokens-api-openapi.yml
  format: yaml
  label: dLocal Tokens API
  slug: dlocal-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dlocal/openapi/dlocal-tokens-api-openapi.yml
- filename: dlocal-transfers-api-openapi.yml
  format: yaml
  label: dLocal Transfers API
  slug: dlocal-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dlocal/openapi/dlocal-transfers-api-openapi.yml
- filename: dlocal-verifications-api-openapi.yml
  format: yaml
  label: dLocal Verifications API
  slug: dlocal-verifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dlocal/openapi/dlocal-verifications-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: dLocal payment processing
    text: Generally, however, if you are using dLocal you will rely on our PCI Level 1 status and complete the relevant SAQ.
    type: PCI Level 1 status
  trust_center:
    url: https://docs.dlocal.com/docs/pci-compliance
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: dLocal
provenance_date: '2026-11-09'
provider_name: dLocal
provider_slug: dlocal
slug: dlocal-compliance
source_date: '2026-11-09'
source_filename: dlocal-compliance.yml
source_heading: Compliance
source_page: https://docs.dlocal.com/docs/pci-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: dLocal\naid: dlocal\nurl: https://docs.dlocal.com/docs/pci-compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://docs.dlocal.com/docs/pci-compliance\nattestations:\n- framework: PCI-DSS\n  type: PCI Level 1 status\n  scope: dLocal payment processing\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Generally, however, if you are using dLocal you will rely on our PCI Level 1 status and complete the relevant\n    SAQ.\n"
source_yaml_url: https://artifacts.apis.io/dlocal/compliance/dlocal-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from dLocal's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Emerging Markets
- Pay-In
- Payouts
- Fintech
- Latin America
- Africa
- Asia
- Local Payment Methods
- Payment Processing
- Cross-Border Payments
---
