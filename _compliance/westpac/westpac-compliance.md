---
api_specs:
- filename: postman_collection.quickstreamapi.json
  format: json
  label: Westpac QuickStream REST API
  slug: westpac-quickstream-rest-api
  spec_type: Postman
  url: https://quickstream.westpac.com.au/docs/downloads/postman_collection.quickstreamapi.json
- filename: westpac-banking-account-balances-api-openapi.yml
  format: yaml
  label: Westpac Banking Corporation Banking Account Balances API
  slug: westpac-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/westpac/openapi/westpac-banking-account-balances-api-openapi.yml
- filename: westpac-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: Westpac Banking Corporation Banking Account Direct Debits API
  slug: westpac-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/westpac/openapi/westpac-banking-account-direct-debits-api-openapi.yml
- filename: westpac-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: Westpac Banking Corporation Banking Account Scheduled Payments API
  slug: westpac-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/westpac/openapi/westpac-banking-account-scheduled-payments-api-openapi.yml
- filename: westpac-banking-account-transactions-api-openapi.yml
  format: yaml
  label: Westpac Banking Corporation Banking Account Transactions API
  slug: westpac-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/westpac/openapi/westpac-banking-account-transactions-api-openapi.yml
- filename: westpac-banking-accounts-api-openapi.yml
  format: yaml
  label: Westpac Banking Corporation Banking Accounts API
  slug: westpac-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/westpac/openapi/westpac-banking-accounts-api-openapi.yml
- filename: westpac-banking-payees-api-openapi.yml
  format: yaml
  label: Westpac Banking Corporation Banking Payees API
  slug: westpac-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/westpac/openapi/westpac-banking-payees-api-openapi.yml
- filename: westpac-banking-products-api-openapi.yml
  format: yaml
  label: Westpac Banking Corporation Banking Products API
  slug: westpac-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/westpac/openapi/westpac-banking-products-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: QuickStream, hosted by Qvalent Pty Ltd
    text: Qvalent is a Level 1 PCI DSS Compliant Service Provider.
    type: Level 1 Compliant Service Provider
  trust_center:
    url: https://quickstream.westpac.com.au/docs/general/pci-compliance/
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Westpac
provenance_date: '2026-11-10'
provider_name: Westpac
provider_slug: westpac
slug: westpac-compliance
source_date: '2026-11-10'
source_filename: westpac-compliance.yml
source_heading: Compliance
source_page: https://quickstream.westpac.com.au/docs/general/pci-compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Westpac\naid: westpac\nurl: https://quickstream.westpac.com.au/docs/general/pci-compliance/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://quickstream.westpac.com.au/docs/general/pci-compliance/\nattestations:\n- framework: PCI-DSS\n  type: Level 1 Compliant Service Provider\n  scope: QuickStream, hosted by Qvalent Pty Ltd\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Qvalent is a Level 1 PCI DSS Compliant Service Provider.\n"
source_yaml_url: https://artifacts.apis.io/westpac/compliance/westpac-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Westpac's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Banks
- Open Banking
- CDR
- Consumer Banking
- Australia
- Product Reference Data
- ADI
---
