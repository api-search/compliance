---
api_specs:
- filename: gateway-bank-banking-account-balances-api-openapi.yml
  format: yaml
  label: Gateway Bank Banking Account Balances API
  slug: gateway-bank-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gateway-bank/openapi/gateway-bank-banking-account-balances-api-openapi.yml
- filename: gateway-bank-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: Gateway Bank Banking Account Direct Debits API
  slug: gateway-bank-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gateway-bank/openapi/gateway-bank-banking-account-direct-debits-api-openapi.yml
- filename: gateway-bank-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: Gateway Bank Banking Account Scheduled Payments API
  slug: gateway-bank-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gateway-bank/openapi/gateway-bank-banking-account-scheduled-payments-api-openapi.yml
- filename: gateway-bank-banking-account-transactions-api-openapi.yml
  format: yaml
  label: Gateway Bank Banking Account Transactions API
  slug: gateway-bank-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gateway-bank/openapi/gateway-bank-banking-account-transactions-api-openapi.yml
- filename: gateway-bank-banking-accounts-api-openapi.yml
  format: yaml
  label: Gateway Bank Banking Accounts API
  slug: gateway-bank-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gateway-bank/openapi/gateway-bank-banking-accounts-api-openapi.yml
- filename: gateway-bank-banking-payees-api-openapi.yml
  format: yaml
  label: Gateway Bank Banking Payees API
  slug: gateway-bank-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gateway-bank/openapi/gateway-bank-banking-payees-api-openapi.yml
- filename: gateway-bank-banking-products-api-openapi.yml
  format: yaml
  label: Gateway Bank Banking Products API
  slug: gateway-bank-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gateway-bank/openapi/gateway-bank-banking-products-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: other
    issuer: Australian Government
    period: null
    report_access: unstated
    scope: Sharing of product reference data and customer data for transaction accounts, savings accounts and term deposits
    text: 'In accordance with Australian Government’s phasing timetable, Gateway is now able to share the following types of data:'
    type: Consumer Data Right (CDR) open banking regime
  trust_center:
    url: https://www.gatewaybank.com.au/help-and-support/important-information/consumer-data-right-cdr/
frameworks:
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Gateway Bank
provenance_date: '2026-11-09'
provider_name: Gateway Bank
provider_slug: gateway-bank
slug: gateway-bank-compliance
source_date: '2026-11-09'
source_filename: gateway-bank-compliance.yml
source_heading: Compliance
source_page: https://www.gatewaybank.com.au/help-and-support/important-information/consumer-data-right-cdr/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Gateway Bank\naid: gateway-bank\nurl: https://www.gatewaybank.com.au/help-and-support/important-information/consumer-data-right-cdr/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.gatewaybank.com.au/help-and-support/important-information/consumer-data-right-cdr/\nattestations:\n- framework: other\n  type: Consumer Data Right (CDR) open banking regime\n  scope: Sharing of product reference data and customer data for transaction accounts, savings accounts and term\n    deposits\n  period: null\n  issuer: Australian Government\n  report_access: unstated\n  text: 'In accordance with Australian Government’s\
  \ phasing timetable, Gateway is now able to share the following\n    types of data:'\n"
source_yaml_url: https://artifacts.apis.io/gateway-bank/compliance/gateway-bank-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Gateway Bank's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Banks
- Open Banking
- CDR
- Consumer Banking
- Mutual Bank
- Customer Owned
- Australia
- Product Reference Data
---
