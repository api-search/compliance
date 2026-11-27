---
api_specs:
- filename: imprint-customer-links-api-openapi.yml
  format: yaml
  label: Imprint Customer Links API
  slug: imprint-customer-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-customer-links-api-openapi.yml
- filename: imprint-customer-sessions-api-openapi.yml
  format: yaml
  label: Imprint Customer Sessions API
  slug: imprint-customer-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-customer-sessions-api-openapi.yml
- filename: imprint-customers-api-openapi.yml
  format: yaml
  label: Imprint Customers API
  slug: imprint-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-customers-api-openapi.yml
- filename: imprint-keys-api-openapi.yml
  format: yaml
  label: Imprint Keys API
  slug: imprint-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-keys-api-openapi.yml
- filename: imprint-offers-api-openapi.yml
  format: yaml
  label: Imprint Offers API
  slug: imprint-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-offers-api-openapi.yml
- filename: imprint-order-events-api-openapi.yml
  format: yaml
  label: Imprint Order Events API
  slug: imprint-order-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-order-events-api-openapi.yml
- filename: imprint-orders-api-openapi.yml
  format: yaml
  label: Imprint Orders API
  slug: imprint-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-orders-api-openapi.yml
- filename: imprint-payment-methods-api-openapi.yml
  format: yaml
  label: Imprint Payment Methods API
  slug: imprint-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-payment-methods-api-openapi.yml
- filename: imprint-rewards-api-openapi.yml
  format: yaml
  label: Imprint Rewards API
  slug: imprint-rewards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-rewards-api-openapi.yml
- filename: imprint-simulate-reward-api-openapi.yml
  format: yaml
  label: Imprint Simulate Reward API
  slug: imprint-simulate-reward-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-simulate-reward-api-openapi.yml
- filename: imprint-simulate-statement-reward-api-openapi.yml
  format: yaml
  label: Imprint Simulate Statement Reward API
  slug: imprint-simulate-statement-reward-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-simulate-statement-reward-api-openapi.yml
- filename: imprint-simulate-transaction-event-api-openapi.yml
  format: yaml
  label: Imprint Simulate Transaction Event API
  slug: imprint-simulate-transaction-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-simulate-transaction-event-api-openapi.yml
- filename: imprint-transaction-intents-api-openapi.yml
  format: yaml
  label: Imprint Transaction Intents API
  slug: imprint-transaction-intents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-transaction-intents-api-openapi.yml
- filename: imprint-transactions-api-openapi.yml
  format: yaml
  label: Imprint Transactions API
  slug: imprint-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-transactions-api-openapi.yml
- filename: imprint-webhooks-api-openapi.yml
  format: yaml
  label: Imprint Webhooks API
  slug: imprint-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-webhooks-api-openapi.yml
- filename: imprint-applications-api-openapi.yml
  format: yaml
  label: Imprint Applications API
  slug: imprint-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-applications-api-openapi.yml
- filename: imprint-card-designs-api-openapi.yml
  format: yaml
  label: Imprint Card Designs API
  slug: imprint-card-designs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imprint/openapi/imprint-card-designs-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Request SOC 2 Type 2 LOA
    type: SOC 2 Type 2 report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Request PCI
    type: PCI DSS
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Request ISO 27001
    type: ISO 27001
  - framework: ISO27701
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Request ISO 27701
    type: ISO 27701
  trust_center:
    url: https://trust.imprint.co/
frameworks:
- ISO27001
- ISO27701
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Imprint
provenance_date: '2026-11-09'
provider_name: Imprint
provider_slug: imprint
slug: imprint-compliance
source_date: '2026-11-09'
source_filename: imprint-compliance.yml
source_heading: Compliance
source_page: https://trust.imprint.co/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Imprint\naid: imprint\nurl: https://trust.imprint.co/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.imprint.co/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Request SOC 2 Type 2 LOA\n- framework: PCI-DSS\n  type: PCI DSS\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Request PCI\n- framework: ISO27001\n  type: ISO 27001\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Request ISO 27001\n- framework: ISO27701\n  type: ISO\
  \ 27701\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Request ISO 27701\n"
source_yaml_url: https://artifacts.apis.io/imprint/compliance/imprint-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Imprint's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Credit Cards
- Co-Branded Cards
- Payments
- Loans
- Rewards
- Loyalty
- Embedded Finance
---
