---
api_specs:
- filename: unit-co-accounts-api-openapi.yml
  format: yaml
  label: Unit Accounts API
  slug: unit-co-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-accounts-api-openapi.yml
- filename: unit-co-api-tokens-api-openapi.yml
  format: yaml
  label: Unit API Tokens API
  slug: unit-co-api-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-api-tokens-api-openapi.yml
- filename: unit-co-applications-api-openapi.yml
  format: yaml
  label: Unit Applications API
  slug: unit-co-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-applications-api-openapi.yml
- filename: unit-co-authorizations-api-openapi.yml
  format: yaml
  label: Unit Authorizations API
  slug: unit-co-authorizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-authorizations-api-openapi.yml
- filename: unit-co-cards-api-openapi.yml
  format: yaml
  label: Unit Cards API
  slug: unit-co-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-cards-api-openapi.yml
- filename: unit-co-checks-api-openapi.yml
  format: yaml
  label: Unit Checks API
  slug: unit-co-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-checks-api-openapi.yml
- filename: unit-co-counterparties-api-openapi.yml
  format: yaml
  label: Unit Counterparties API
  slug: unit-co-counterparties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-counterparties-api-openapi.yml
- filename: unit-co-credit-and-repayments-api-openapi.yml
  format: yaml
  label: Unit Credit and Repayments API
  slug: unit-co-credit-and-repayments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-credit-and-repayments-api-openapi.yml
- filename: unit-co-customers-api-openapi.yml
  format: yaml
  label: Unit Customers API
  slug: unit-co-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-customers-api-openapi.yml
- filename: unit-co-events-api-openapi.yml
  format: yaml
  label: Unit Events API
  slug: unit-co-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-events-api-openapi.yml
- filename: unit-co-fees-and-rewards-api-openapi.yml
  format: yaml
  label: Unit Fees and Rewards API
  slug: unit-co-fees-and-rewards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-fees-and-rewards-api-openapi.yml
- filename: unit-co-payments-api-openapi.yml
  format: yaml
  label: Unit Payments API
  slug: unit-co-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-payments-api-openapi.yml
- filename: unit-co-risk-and-fraud-api-openapi.yml
  format: yaml
  label: Unit Risk and Fraud API
  slug: unit-co-risk-and-fraud-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-risk-and-fraud-api-openapi.yml
- filename: unit-co-statements-api-openapi.yml
  format: yaml
  label: Unit Statements API
  slug: unit-co-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-statements-api-openapi.yml
- filename: unit-co-tax-forms-api-openapi.yml
  format: yaml
  label: Unit Tax Forms API
  slug: unit-co-tax-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-tax-forms-api-openapi.yml
- filename: unit-co-transactions-api-openapi.yml
  format: yaml
  label: Unit Transactions API
  slug: unit-co-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-transactions-api-openapi.yml
- filename: unit-co-webhooks-api-openapi.yml
  format: yaml
  label: Unit Webhooks API
  slug: unit-co-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Unit systems, processes, compliance frameworks, and controls
    text: Unit is SOC 2 Type II compliant.
    type: SOC 2 Type II
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: Unit payment card data handling
    text: Unit is PCI-DSS Level 1 certified.
    type: PCI DSS Level 1 certification
  trust_center:
    url: https://www.unit.co/security
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Unit
provenance_date: '2026-11-10'
provider_name: Unit
provider_slug: unit-co
slug: unit-co-compliance
source_date: '2026-11-10'
source_filename: unit-co-compliance.yml
source_heading: Compliance
source_page: https://www.unit.co/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Unit\naid: unit-co\nurl: https://www.unit.co/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.unit.co/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Unit systems, processes, compliance frameworks, and controls\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Unit is SOC 2 Type II compliant.\n- framework: PCI-DSS\n  type: PCI DSS Level 1 certification\n  scope: Unit payment card data handling\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Unit is PCI-DSS Level 1 certified.\n"
source_yaml_url: https://artifacts.apis.io/unit-co/compliance/unit-co-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Unit's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Banking as a Service
- Banking
- Payments
- Card Issuing
- ACH
- Lending
- JSON:API
- Embedded Finance
---
