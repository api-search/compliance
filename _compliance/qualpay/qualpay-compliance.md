---
api_specs:
- filename: qualpay-account-updater-api-openapi.yml
  format: yaml
  label: Qualpay Account Updater API
  slug: qualpay-account-updater-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-account-updater-api-openapi.yml
- filename: qualpay-application-boarding-api-openapi.yml
  format: yaml
  label: Qualpay Application Boarding API
  slug: qualpay-application-boarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-application-boarding-api-openapi.yml
- filename: qualpay-checkout-api-openapi.yml
  format: yaml
  label: Qualpay Checkout API
  slug: qualpay-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-checkout-api-openapi.yml
- filename: qualpay-customer-vault-api-openapi.yml
  format: yaml
  label: Qualpay Customer Vault API
  slug: qualpay-customer-vault-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-customer-vault-api-openapi.yml
- filename: qualpay-disputes-v0-5-api-openapi.yml
  format: yaml
  label: Qualpay Disputes v0.5 API
  slug: qualpay-disputes-v0-5-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-disputes-v0-5-api-openapi.yml
- filename: qualpay-disputes-v1-0-api-openapi.yml
  format: yaml
  label: Qualpay Disputes v1.0 API
  slug: qualpay-disputes-v1-0-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-disputes-v1-0-api-openapi.yml
- filename: qualpay-embedded-fields-api-openapi.yml
  format: yaml
  label: Qualpay Embedded Fields API
  slug: qualpay-embedded-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-embedded-fields-api-openapi.yml
- filename: qualpay-integrator-api-openapi.yml
  format: yaml
  label: Qualpay Integrator API
  slug: qualpay-integrator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-integrator-api-openapi.yml
- filename: qualpay-invoicing-api-openapi.yml
  format: yaml
  label: Qualpay Invoicing API
  slug: qualpay-invoicing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-invoicing-api-openapi.yml
- filename: qualpay-payee-vault-api-openapi.yml
  format: yaml
  label: Qualpay Payee Vault API
  slug: qualpay-payee-vault-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-payee-vault-api-openapi.yml
- filename: qualpay-payment-gateway-api-openapi.yml
  format: yaml
  label: Qualpay Payment Gateway API
  slug: qualpay-payment-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-payment-gateway-api-openapi.yml
- filename: qualpay-recurring-billing-api-openapi.yml
  format: yaml
  label: Qualpay Recurring Billing API
  slug: qualpay-recurring-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-recurring-billing-api-openapi.yml
- filename: qualpay-reporting-api-openapi.yml
  format: yaml
  label: Qualpay Reporting API
  slug: qualpay-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-reporting-api-openapi.yml
- filename: qualpay-token-api-openapi.yml
  format: yaml
  label: Qualpay Token API
  slug: qualpay-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-token-api-openapi.yml
- filename: qualpay-transaction-api-openapi.yml
  format: yaml
  label: Qualpay Transaction API
  slug: qualpay-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-transaction-api-openapi.yml
- filename: qualpay-webhooks-api-openapi.yml
  format: yaml
  label: Qualpay Webhooks API
  slug: qualpay-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: approved QSA (Qualified Security Assessor)
    period: null
    report_access: on_request
    scope: Qualpay payment services
    text: Qualpay is a PCI DSS Level 1 certified service provider .
    type: Level 1 certified service provider (QSA annual assessment)
  trust_center:
    url: https://www.qualpay.com/security
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Qualpay
provenance_date: '2026-11-10'
provider_name: Qualpay
provider_slug: qualpay
slug: qualpay-compliance
source_date: '2026-11-10'
source_filename: qualpay-compliance.yml
source_heading: Compliance
source_page: https://www.qualpay.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Qualpay\naid: qualpay\nurl: https://www.qualpay.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.qualpay.com/security\nattestations:\n- framework: PCI-DSS\n  type: Level 1 certified service provider (QSA annual assessment)\n  scope: Qualpay payment services\n  period: null\n  issuer: approved QSA (Qualified Security Assessor)\n  report_access: on_request\n  text: Qualpay is a PCI DSS Level 1 certified service provider .\n"
source_yaml_url: https://artifacts.apis.io/qualpay/compliance/qualpay-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Qualpay's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Payment Processing
- Merchant Services
- B2B Payments
- Reporting
- Tokenization
---
