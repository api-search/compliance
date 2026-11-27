---
api_specs:
- filename: blnkfinance-accounts-api-openapi.yml
  format: yaml
  label: Blnk Finance Accounts API
  slug: blnkfinance-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blnkfinance/openapi/blnkfinance-accounts-api-openapi.yml
- filename: blnkfinance-backup-api-openapi.yml
  format: yaml
  label: Blnk Finance Backup API
  slug: blnkfinance-backup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blnkfinance/openapi/blnkfinance-backup-api-openapi.yml
- filename: blnkfinance-balance-monitors-api-openapi.yml
  format: yaml
  label: Blnk Finance Balance Monitors API
  slug: blnkfinance-balance-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blnkfinance/openapi/blnkfinance-balance-monitors-api-openapi.yml
- filename: blnkfinance-balances-api-openapi.yml
  format: yaml
  label: Blnk Finance Balances API
  slug: blnkfinance-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blnkfinance/openapi/blnkfinance-balances-api-openapi.yml
- filename: blnkfinance-identities-api-openapi.yml
  format: yaml
  label: Blnk Finance Identities API
  slug: blnkfinance-identities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blnkfinance/openapi/blnkfinance-identities-api-openapi.yml
- filename: blnkfinance-ledgers-api-openapi.yml
  format: yaml
  label: Blnk Finance Ledgers API
  slug: blnkfinance-ledgers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blnkfinance/openapi/blnkfinance-ledgers-api-openapi.yml
- filename: blnkfinance-refund-transaction-api-openapi.yml
  format: yaml
  label: Blnk Finance Refund Transaction API
  slug: blnkfinance-refund-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blnkfinance/openapi/blnkfinance-refund-transaction-api-openapi.yml
- filename: blnkfinance-transactions-api-openapi.yml
  format: yaml
  label: Blnk Finance Transactions API
  slug: blnkfinance-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blnkfinance/openapi/blnkfinance-transactions-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Blnk's ISMS
    text: Blnk’s ISMS is certified to ISO/IEC 27001.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Personal data processing
    text: Personal data is processed under GDPR.
    type: compliance
  trust_center:
    url: https://blnkfinance.com/security
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Blnk Finance
provenance_date: '2026-11-09'
provider_name: Blnk Finance
provider_slug: blnkfinance
slug: blnkfinance-compliance
source_date: '2026-11-09'
source_filename: blnkfinance-compliance.yml
source_heading: Compliance
source_page: https://blnkfinance.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Blnk Finance\naid: blnkfinance\nurl: https://blnkfinance.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/blnkfinance-trust-center.yml\ntrust_center:\n  url: https://blnkfinance.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Blnk's ISMS\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Blnk’s ISMS is certified to ISO/IEC 27001.\n- framework: GDPR\n  type: compliance\n  scope: Personal data processing\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Personal data is processed under GDPR.\n"
source_yaml_url: https://artifacts.apis.io/blnkfinance/compliance/blnkfinance-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Blnk Finance's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Financial Services
- Ledger
- Double-Entry
- Payments
- Wallets
- Lending
- Banking Infrastructure
- Open Source
- MCP
- AI Agents
- Developer Tools
- A2A
---
