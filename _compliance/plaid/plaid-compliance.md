---
api_specs:
- filename: plaid-plaid-api-openapi.yml
  format: yaml
  label: Plaid API
  slug: plaid-plaid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plaid/openapi/plaid-plaid-api-openapi.yml
- filename: plaid-account-information-api-openapi.yml
  format: yaml
  label: Plaid Account Information API
  slug: plaid-account-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plaid/openapi/plaid-account-information-api-openapi.yml
- filename: plaid-account-statements-api-openapi.yml
  format: yaml
  label: Plaid Account Statements API
  slug: plaid-account-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plaid/openapi/plaid-account-statements-api-openapi.yml
- filename: plaid-account-transactions-api-openapi.yml
  format: yaml
  label: Plaid Account Transactions API
  slug: plaid-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plaid/openapi/plaid-account-transactions-api-openapi.yml
- filename: plaid-asset-transfer-networks-information-api-openapi.yml
  format: yaml
  label: Plaid Asset Transfer Networks Information API
  slug: plaid-asset-transfer-networks-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plaid/openapi/plaid-asset-transfer-networks-information-api-openapi.yml
- filename: plaid-payment-networks-information-api-openapi.yml
  format: yaml
  label: Plaid Payment Networks Information API
  slug: plaid-payment-networks-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plaid/openapi/plaid-payment-networks-information-api-openapi.yml
- filename: plaid-personal-information-api-openapi.yml
  format: yaml
  label: Plaid Personal Information API
  slug: plaid-personal-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plaid/openapi/plaid-personal-information-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: SOC 2 Type 2
    type: SOC 2 Type 2
  - framework: ISO27001
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: ISO-27001
    type: ISO 27001 certification
  - framework: ISO27701
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: ISO 27701
    type: ISO 27701 certification
  trust_center:
    url: https://security.plaid.com/
frameworks:
- ISO27001
- ISO27701
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Plaid
provenance_date: '2026-11-10'
provider_name: Plaid
provider_slug: plaid
slug: plaid-compliance
source_date: '2026-11-10'
source_filename: plaid-compliance.yml
source_heading: Compliance
source_page: https://security.plaid.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Plaid\naid: plaid\nurl: https://security.plaid.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/plaid-trust-center.yml\ntrust_center:\n  url: https://security.plaid.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: SOC 2 Type 2\n- framework: ISO27001\n  type: ISO 27001 certification\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: ISO-27001\n- framework: ISO27701\n  type: ISO 27701 certification\n  scope: unstated\n  period: null\n  issuer: unstated\n \
  \ report_access: unstated\n  text: ISO 27701\n"
source_yaml_url: https://artifacts.apis.io/plaid/compliance/plaid-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Plaid's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Fintech
- Open Banking
- Bank Accounts
- Data Aggregation
- Payments
- United States
---
