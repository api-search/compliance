---
api_specs:
- filename: trustly-accounts-api-openapi.yml
  format: yaml
  label: Trustly Group Accounts API
  slug: trustly-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-accounts-api-openapi.yml
- filename: trustly-api-api-openapi.yml
  format: yaml
  label: Trustly Group API
  slug: trustly-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-api-api-openapi.yml
- filename: trustly-countries-api-openapi.yml
  format: yaml
  label: Trustly Group Countries API
  slug: trustly-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-countries-api-openapi.yml
- filename: trustly-customers-api-openapi.yml
  format: yaml
  label: Trustly Group Customers API
  slug: trustly-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-customers-api-openapi.yml
- filename: trustly-identity-api-openapi.yml
  format: yaml
  label: Trustly Group Identity API
  slug: trustly-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-identity-api-openapi.yml
- filename: trustly-networkcheckapi-api-openapi.yml
  format: yaml
  label: Trustly Group Network Check API
  slug: trustly-networkcheckapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-networkcheckapi-api-openapi.yml
- filename: trustly-payments-api-openapi.yml
  format: yaml
  label: Trustly Group Payments API
  slug: trustly-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-payments-api-openapi.yml
- filename: trustly-transactions-api-openapi.yml
  format: yaml
  label: Trustly Group Transactions API
  slug: trustly-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-transactions-api-openapi.yml
- filename: trustly-verifycustomer-api-openapi.yml
  format: yaml
  label: Trustly Group Verify Customer API
  slug: trustly-verifycustomer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-verifycustomer-api-openapi.yml
- filename: trustly-account-data-api-openapi.yml
  format: yaml
  label: Trustly Group Account Data API
  slug: trustly-account-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-account-data-api-openapi.yml
- filename: trustly-dispute-management-api-openapi.yml
  format: yaml
  label: Trustly Group Dispute Management API
  slug: trustly-dispute-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-dispute-management-api-openapi.yml
- filename: trustly-payment-providers-api-openapi.yml
  format: yaml
  label: Trustly Group Payment Providers API
  slug: trustly-payment-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-payment-providers-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Trustly organisation; servers hosted at ISO 27001-certified facilities
    text: Trustly is ISO 27001-certified and servers are hosted at ISO 27001-certified facilities.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Trustly
    text: Trustly is GDPR-compliant and treats privacy as critical to secure payments.
    type: compliance
  trust_center:
    url: https://www.trustly.com/security
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Trustly Group
provenance_date: '2026-11-10'
provider_name: Trustly Group
provider_slug: trustly
slug: trustly-compliance
source_date: '2026-11-10'
source_filename: trustly-compliance.yml
source_heading: Compliance
source_page: https://www.trustly.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Trustly Group\naid: trustly\nurl: https://www.trustly.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.trustly.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Trustly organisation; servers hosted at ISO 27001-certified facilities\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Trustly is ISO 27001-certified and servers are hosted at ISO 27001-certified facilities.\n- framework: GDPR\n  type: compliance\n  scope: Trustly\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Trustly is GDPR-compliant and treats privacy\
  \ as critical to secure payments.\n"
source_yaml_url: https://artifacts.apis.io/trustly/compliance/trustly-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Trustly Group's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Pay by Bank
- Open Banking
- Account-to-Account
- Payouts
- Direct Debit
- Bank Account Verification
- Identity Verification
- Fintech
- Webhook
- MCP
---
