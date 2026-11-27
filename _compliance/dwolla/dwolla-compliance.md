---
api_specs:
- filename: dwolla-accounts-api-openapi.yml
  format: yaml
  label: Dwolla Accounts API
  slug: dwolla-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-accounts-api-openapi.yml
- filename: dwolla-beneficial-owners-api-openapi.yml
  format: yaml
  label: Dwolla beneficial owners API
  slug: dwolla-beneficial-owners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-beneficial-owners-api-openapi.yml
- filename: dwolla-client-tokens-api-openapi.yml
  format: yaml
  label: Dwolla client tokens API
  slug: dwolla-client-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-client-tokens-api-openapi.yml
- filename: dwolla-customers-api-openapi.yml
  format: yaml
  label: Dwolla Customers API
  slug: dwolla-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-customers-api-openapi.yml
- filename: dwolla-documents-api-openapi.yml
  format: yaml
  label: Dwolla Documents API
  slug: dwolla-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-documents-api-openapi.yml
- filename: dwolla-events-api-openapi.yml
  format: yaml
  label: Dwolla Events API
  slug: dwolla-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-events-api-openapi.yml
- filename: dwolla-exchange-sessions-api-openapi.yml
  format: yaml
  label: Dwolla exchange sessions API
  slug: dwolla-exchange-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-exchange-sessions-api-openapi.yml
- filename: dwolla-exchanges-api-openapi.yml
  format: yaml
  label: Dwolla Exchanges API
  slug: dwolla-exchanges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-exchanges-api-openapi.yml
- filename: dwolla-funding-sources-api-openapi.yml
  format: yaml
  label: Dwolla funding sources API
  slug: dwolla-funding-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-funding-sources-api-openapi.yml
- filename: dwolla-kba-api-openapi.yml
  format: yaml
  label: Dwolla Kba API
  slug: dwolla-kba-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-kba-api-openapi.yml
- filename: dwolla-labels-api-openapi.yml
  format: yaml
  label: Dwolla Labels API
  slug: dwolla-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-labels-api-openapi.yml
- filename: dwolla-mass-payments-api-openapi.yml
  format: yaml
  label: Dwolla mass payments API
  slug: dwolla-mass-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-mass-payments-api-openapi.yml
- filename: dwolla-root-api-openapi.yml
  format: yaml
  label: Dwolla Root API
  slug: dwolla-root-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-root-api-openapi.yml
- filename: dwolla-sandbox-simulations-api-openapi.yml
  format: yaml
  label: Dwolla sandbox simulations API
  slug: dwolla-sandbox-simulations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-sandbox-simulations-api-openapi.yml
- filename: dwolla-tokens-api-openapi.yml
  format: yaml
  label: Dwolla Tokens API
  slug: dwolla-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-tokens-api-openapi.yml
- filename: dwolla-transfers-api-openapi.yml
  format: yaml
  label: Dwolla Transfers API
  slug: dwolla-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-transfers-api-openapi.yml
- filename: dwolla-webhook-subscriptions-api-openapi.yml
  format: yaml
  label: Dwolla webhook subscriptions API
  slug: dwolla-webhook-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-webhook-subscriptions-api-openapi.yml
- filename: dwolla-webhooks-api-openapi.yml
  format: yaml
  label: Dwolla Webhooks API
  slug: dwolla-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dwolla/openapi/dwolla-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: Dwolla SOC II Report 2026
    type: SOC 2 report
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: unstated
    scope: null
    text: Dwolla SOC II Report 2025
    type: SOC 2 report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Security trust principle
    source: https://www.dwolla.com/features/security
    text: Dwolla maintains a SOC 2 type 2 report focused on the Security trust principle
    type: SOC 2 Type 2 report
  trust_center:
    url: https://trust.dwolla.com/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Dwolla
provenance_date: '2026-11-09'
provider_name: Dwolla
provider_slug: dwolla
slug: dwolla-compliance
source_date: '2026-11-09'
source_filename: dwolla-compliance.yml
source_heading: Compliance
source_page: https://trust.dwolla.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Dwolla\naid: dwolla\nurl: https://trust.dwolla.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/dwolla-trust-center.yml\n  sources:\n  - https://trust.dwolla.com/\n  - https://www.dwolla.com/features/security\ntrust_center:\n  url: https://trust.dwolla.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 report\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: Dwolla SOC II Report 2026\n- framework: SOC2\n  type: SOC 2 report\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: unstated\n  text: Dwolla SOC II Report 2025\n- framework: SOC2\n  type:\
  \ SOC 2 Type 2 report\n  scope: Security trust principle\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Dwolla maintains a SOC 2 type 2 report focused on the Security trust principle\n  source: https://www.dwolla.com/features/security\n"
source_yaml_url: https://artifacts.apis.io/dwolla/compliance/dwolla-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Dwolla's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- ACH
- Bank Transfers
- Fintech
- Account-to-Account Payments
- Money Movement
- Instant Payments
- Open Banking
- Webhook
- KYC
- United States
- Open Finance
- Same-Day ACH
- RTP
- FedNow
- Mass Payments
- Drop-in Components
- SDK
- Sandbox
---
