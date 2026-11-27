---
api_specs:
- filename: gocardless-billing-request-flows-api-openapi.yml
  format: yaml
  label: GoCardless Billing Request Flows API
  slug: gocardless-billing-request-flows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gocardless/openapi/gocardless-billing-request-flows-api-openapi.yml
- filename: gocardless-billing-requests-api-openapi.yml
  format: yaml
  label: GoCardless Billing Requests API
  slug: gocardless-billing-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gocardless/openapi/gocardless-billing-requests-api-openapi.yml
- filename: gocardless-blocks-api-openapi.yml
  format: yaml
  label: GoCardless Blocks API
  slug: gocardless-blocks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gocardless/openapi/gocardless-blocks-api-openapi.yml
- filename: gocardless-creditor-bank-accounts-api-openapi.yml
  format: yaml
  label: GoCardless Creditor Bank Accounts API
  slug: gocardless-creditor-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gocardless/openapi/gocardless-creditor-bank-accounts-api-openapi.yml
- filename: gocardless-creditors-api-openapi.yml
  format: yaml
  label: GoCardless Creditors API
  slug: gocardless-creditors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gocardless/openapi/gocardless-creditors-api-openapi.yml
- filename: gocardless-customer-bank-accounts-api-openapi.yml
  format: yaml
  label: GoCardless Customer Bank Accounts API
  slug: gocardless-customer-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gocardless/openapi/gocardless-customer-bank-accounts-api-openapi.yml
- filename: gocardless-customers-api-openapi.yml
  format: yaml
  label: GoCardless Customers API
  slug: gocardless-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gocardless/openapi/gocardless-customers-api-openapi.yml
- filename: gocardless-events-api-openapi.yml
  format: yaml
  label: GoCardless Events API
  slug: gocardless-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gocardless/openapi/gocardless-events-api-openapi.yml
- filename: gocardless-instalment-schedules-api-openapi.yml
  format: yaml
  label: GoCardless Instalment Schedules API
  slug: gocardless-instalment-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gocardless/openapi/gocardless-instalment-schedules-api-openapi.yml
- filename: gocardless-institutions-api-openapi.yml
  format: yaml
  label: GoCardless Institutions API
  slug: gocardless-institutions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gocardless/openapi/gocardless-institutions-api-openapi.yml
- filename: gocardless-mandates-api-openapi.yml
  format: yaml
  label: GoCardless Mandates API
  slug: gocardless-mandates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gocardless/openapi/gocardless-mandates-api-openapi.yml
- filename: gocardless-payer-authorisations-api-openapi.yml
  format: yaml
  label: GoCardless Payer Authorisations API
  slug: gocardless-payer-authorisations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gocardless/openapi/gocardless-payer-authorisations-api-openapi.yml
- filename: gocardless-payments-api-openapi.yml
  format: yaml
  label: GoCardless Payments API
  slug: gocardless-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gocardless/openapi/gocardless-payments-api-openapi.yml
- filename: gocardless-payouts-api-openapi.yml
  format: yaml
  label: GoCardless Payouts API
  slug: gocardless-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gocardless/openapi/gocardless-payouts-api-openapi.yml
- filename: gocardless-refunds-api-openapi.yml
  format: yaml
  label: GoCardless Refunds API
  slug: gocardless-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gocardless/openapi/gocardless-refunds-api-openapi.yml
- filename: gocardless-subscriptions-api-openapi.yml
  format: yaml
  label: GoCardless Subscriptions API
  slug: gocardless-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gocardless/openapi/gocardless-subscriptions-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Security protocols across our business, services and products
    text: ISO27001 certified since 2016
    type: certification
  trust_center:
    url: https://gocardless.com/security
frameworks:
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: GoCardless
provenance_date: '2026-11-09'
provider_name: GoCardless
provider_slug: gocardless
slug: gocardless-compliance
source_date: '2026-11-09'
source_filename: gocardless-compliance.yml
source_heading: Compliance
source_page: https://gocardless.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: GoCardless\naid: gocardless\nurl: https://gocardless.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/gocardless-trust-center.yml\ntrust_center:\n  url: https://gocardless.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Security protocols across our business, services and products\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO27001 certified since 2016\n"
source_yaml_url: https://artifacts.apis.io/gocardless/compliance/gocardless-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from GoCardless's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Direct Debit
- Bank Debit
- Recurring Payments
- Subscription
- SEPA
- Bacs
- ACH
- Open Banking
- Fintech
---
