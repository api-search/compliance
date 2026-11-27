---
api_specs:
- filename: bcu-bank-banking-account-balances-api-openapi.yml
  format: yaml
  label: BCU Bank Banking Account Balances API
  slug: bcu-bank-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcu-bank/openapi/bcu-bank-banking-account-balances-api-openapi.yml
- filename: bcu-bank-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: BCU Bank Banking Account Direct Debits API
  slug: bcu-bank-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcu-bank/openapi/bcu-bank-banking-account-direct-debits-api-openapi.yml
- filename: bcu-bank-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: BCU Bank Banking Account Scheduled Payments API
  slug: bcu-bank-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcu-bank/openapi/bcu-bank-banking-account-scheduled-payments-api-openapi.yml
- filename: bcu-bank-banking-account-transactions-api-openapi.yml
  format: yaml
  label: BCU Bank Banking Account Transactions API
  slug: bcu-bank-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcu-bank/openapi/bcu-bank-banking-account-transactions-api-openapi.yml
- filename: bcu-bank-banking-accounts-api-openapi.yml
  format: yaml
  label: BCU Bank Banking Accounts API
  slug: bcu-bank-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcu-bank/openapi/bcu-bank-banking-accounts-api-openapi.yml
- filename: bcu-bank-banking-payees-api-openapi.yml
  format: yaml
  label: BCU Bank Banking Payees API
  slug: bcu-bank-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcu-bank/openapi/bcu-bank-banking-payees-api-openapi.yml
- filename: bcu-bank-banking-products-api-openapi.yml
  format: yaml
  label: BCU Bank Banking Products API
  slug: bcu-bank-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcu-bank/openapi/bcu-bank-banking-products-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Redundant CDR data held by the Bank
    text: Under the CDR regime, the Bank has obligations to destroy, delete or de-identify any redundant CDR data that it holds
    type: Consumer Data Right regime obligations
  trust_center:
    url: https://www.bcu.com.au/important-information/consumer-data-right-policy/
frameworks:
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: BCU Bank
provenance_date: '2026-11-09'
provider_name: BCU Bank
provider_slug: bcu-bank
slug: bcu-bank-compliance
source_date: '2026-11-09'
source_filename: bcu-bank-compliance.yml
source_heading: Compliance
source_page: https://www.bcu.com.au/important-information/consumer-data-right-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: BCU Bank\naid: bcu-bank\nurl: https://www.bcu.com.au/important-information/consumer-data-right-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.bcu.com.au/important-information/consumer-data-right-policy/\nattestations:\n- framework: other\n  type: Consumer Data Right regime obligations\n  scope: Redundant CDR data held by the Bank\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Under the CDR regime, the Bank has obligations to destroy, delete or de-identify any redundant CDR data\n    that it holds\n"
source_yaml_url: https://artifacts.apis.io/bcu-bank/compliance/bcu-bank-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from BCU Bank's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Banks
- Open Banking
- CDR
- Consumer Data Right
- Consumer Banking
- Mutual Bank
- Australia
---
