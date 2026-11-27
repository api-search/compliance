---
api_specs:
- filename: moneris-3d-secure-api-openapi.yml
  format: yaml
  label: Moneris 3D Secure API
  slug: moneris-3d-secure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneris/openapi/moneris-3d-secure-api-openapi.yml
- filename: moneris-customers-api-openapi.yml
  format: yaml
  label: Moneris Customers API
  slug: moneris-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneris/openapi/moneris-customers-api-openapi.yml
- filename: moneris-disputes-api-openapi.yml
  format: yaml
  label: Moneris Disputes API
  slug: moneris-disputes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneris/openapi/moneris-disputes-api-openapi.yml
- filename: moneris-installments-api-openapi.yml
  format: yaml
  label: Moneris Installments API
  slug: moneris-installments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneris/openapi/moneris-installments-api-openapi.yml
- filename: moneris-kount-api-openapi.yml
  format: yaml
  label: Moneris Kount API
  slug: moneris-kount-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneris/openapi/moneris-kount-api-openapi.yml
- filename: moneris-merchant-onboarding-api-openapi.yml
  format: yaml
  label: Moneris Merchant Onboarding API
  slug: moneris-merchant-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneris/openapi/moneris-merchant-onboarding-api-openapi.yml
- filename: moneris-multi-currency-pricing-rate-lookup-api-openapi.yml
  format: yaml
  label: Moneris Multi-Currency Pricing Rate Lookup API
  slug: moneris-multi-currency-pricing-rate-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneris/openapi/moneris-multi-currency-pricing-rate-lookup-api-openapi.yml
- filename: moneris-payment-methods-api-openapi.yml
  format: yaml
  label: Moneris Payment Methods API
  slug: moneris-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneris/openapi/moneris-payment-methods-api-openapi.yml
- filename: moneris-payments-api-openapi.yml
  format: yaml
  label: Moneris Payments API
  slug: moneris-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneris/openapi/moneris-payments-api-openapi.yml
- filename: moneris-products-api-openapi.yml
  format: yaml
  label: Moneris Products API
  slug: moneris-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneris/openapi/moneris-products-api-openapi.yml
- filename: moneris-refunds-api-openapi.yml
  format: yaml
  label: Moneris Refunds API
  slug: moneris-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneris/openapi/moneris-refunds-api-openapi.yml
- filename: moneris-subscriptions-api-openapi.yml
  format: yaml
  label: Moneris Subscriptions API
  slug: moneris-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneris/openapi/moneris-subscriptions-api-openapi.yml
- filename: moneris-surcharge-lookup-api-openapi.yml
  format: yaml
  label: Moneris Surcharge Lookup API
  slug: moneris-surcharge-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneris/openapi/moneris-surcharge-lookup-api-openapi.yml
- filename: moneris-terminal-service-orders-api-openapi.yml
  format: yaml
  label: Moneris Terminal & Service Orders API
  slug: moneris-terminal-service-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneris/openapi/moneris-terminal-service-orders-api-openapi.yml
- filename: moneris-validations-api-openapi.yml
  format: yaml
  label: Moneris Validations API
  slug: moneris-validations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moneris/openapi/moneris-validations-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: annual basis
    report_access: unstated
    scope: Moneris payment products, solutions and underlying infrastructure
    text: Moneris maintains its PCI DSS compliant Level 1 service provider status and our compliance is reported to all major Payment Card Networks on an annual basis.
    type: Level 1 service provider status
  trust_center:
    url: https://www.moneris.com/en/support/compliance-and-security/pci-data-security
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Moneris
provenance_date: '2026-11-10'
provider_name: Moneris
provider_slug: moneris
slug: moneris-compliance
source_date: '2026-11-10'
source_filename: moneris-compliance.yml
source_heading: Compliance
source_page: https://www.moneris.com/en/support/compliance-and-security/pci-data-security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Moneris\naid: moneris\nurl: https://www.moneris.com/en/support/compliance-and-security/pci-data-security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.moneris.com/en/support/compliance-and-security/pci-data-security\nattestations:\n- framework: PCI-DSS\n  type: Level 1 service provider status\n  scope: Moneris payment products, solutions and underlying infrastructure\n  period: annual basis\n  issuer: null\n  report_access: unstated\n  text: Moneris maintains its PCI DSS compliant Level 1 service provider status and our compliance is reported to\n    all major Payment Card Networks on an annual\
  \ basis.\n"
source_yaml_url: https://artifacts.apis.io/moneris/compliance/moneris-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Moneris's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Payments
- Payment Processing
- Card Payments
- Merchant Services
- Acquiring
- Canada
- Fintech
- Infrastructure
---
