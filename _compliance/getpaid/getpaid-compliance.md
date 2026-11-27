---
api_specs:
- filename: getpaid-accounts-api-openapi.yml
  format: yaml
  label: GetPaid Accounts API
  slug: getpaid-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getpaid/openapi/getpaid-accounts-api-openapi.yml
- filename: getpaid-applications-api-openapi.yml
  format: yaml
  label: GetPaid Applications API
  slug: getpaid-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getpaid/openapi/getpaid-applications-api-openapi.yml
- filename: getpaid-authentication-api-openapi.yml
  format: yaml
  label: GetPaid Authentication API
  slug: getpaid-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getpaid/openapi/getpaid-authentication-api-openapi.yml
- filename: getpaid-checkouts-api-openapi.yml
  format: yaml
  label: GetPaid Checkouts API
  slug: getpaid-checkouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getpaid/openapi/getpaid-checkouts-api-openapi.yml
- filename: getpaid-payments-api-openapi.yml
  format: yaml
  label: GetPaid Payments API
  slug: getpaid-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getpaid/openapi/getpaid-payments-api-openapi.yml
- filename: getpaid-queries-api-openapi.yml
  format: yaml
  label: GetPaid Queries API
  slug: getpaid-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getpaid/openapi/getpaid-queries-api-openapi.yml
- filename: getpaid-accept-payments-webhooks-api-openapi.yml
  format: yaml
  label: GetPaid Accept payments webhooks API
  slug: getpaid-accept-payments-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getpaid/openapi/getpaid-accept-payments-webhooks-api-openapi.yml
- filename: getpaid-onboard-sellers-webhooks-api-openapi.yml
  format: yaml
  label: GetPaid Onboard sellers webhooks API
  slug: getpaid-onboard-sellers-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getpaid/openapi/getpaid-onboard-sellers-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: card data handling via PCI DSS Level 1 certified partners
    text: Card data is handled end to end by PCI DSS Level 1 certified partners and never touches your infrastructure.
    type: certification held by partners
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: data hosting in the EU and processing
    text: Data is hosted in the EU and processed in line with GDPR.
    type: compliance statement
  trust_center:
    url: https://getpaid.io/compliance/
frameworks:
- GDPR
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: GetPaid
provenance_date: '2026-11-09'
provider_name: GetPaid
provider_slug: getpaid
slug: getpaid-compliance
source_date: '2026-11-09'
source_filename: getpaid-compliance.yml
source_heading: Compliance
source_page: https://getpaid.io/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: GetPaid\naid: getpaid\nurl: https://getpaid.io/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://getpaid.io/compliance/\nattestations:\n- framework: PCI-DSS\n  type: certification held by partners\n  scope: card data handling via PCI DSS Level 1 certified partners\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Card data is handled end to end by PCI DSS Level 1 certified partners and never touches your infrastructure.\n- framework: GDPR\n  type: compliance statement\n  scope: data hosting in the EU and processing\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: Data is hosted in the EU and processed in line with GDPR.\n"
source_yaml_url: https://artifacts.apis.io/getpaid/compliance/getpaid-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from GetPaid's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Embedded Payments
- Split Settlement
- Checkout
- Marketplace
- Onboarding
- Subscription
- Agentic Payments
- Europe
---
