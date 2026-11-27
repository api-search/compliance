---
api_specs:
- filename: shippo-addresses-api-openapi.yml
  format: yaml
  label: Shippo Addresses API
  slug: shippo-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippo/openapi/shippo-addresses-api-openapi.yml
- filename: shippo-carrier-accounts-api-openapi.yml
  format: yaml
  label: Shippo Carrier Accounts API
  slug: shippo-carrier-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippo/openapi/shippo-carrier-accounts-api-openapi.yml
- filename: shippo-parcels-api-openapi.yml
  format: yaml
  label: Shippo Parcels API
  slug: shippo-parcels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippo/openapi/shippo-parcels-api-openapi.yml
- filename: shippo-rates-api-openapi.yml
  format: yaml
  label: Shippo Rates API
  slug: shippo-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippo/openapi/shippo-rates-api-openapi.yml
- filename: shippo-refunds-api-openapi.yml
  format: yaml
  label: Shippo Refunds API
  slug: shippo-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippo/openapi/shippo-refunds-api-openapi.yml
- filename: shippo-shipments-api-openapi.yml
  format: yaml
  label: Shippo Shipments API
  slug: shippo-shipments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippo/openapi/shippo-shipments-api-openapi.yml
- filename: shippo-tracking-api-openapi.yml
  format: yaml
  label: Shippo Tracking API
  slug: shippo-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippo/openapi/shippo-tracking-api-openapi.yml
- filename: shippo-transactions-api-openapi.yml
  format: yaml
  label: Shippo Transactions API
  slug: shippo-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippo/openapi/shippo-transactions-api-openapi.yml
- filename: shippo-webhooks-api-openapi.yml
  format: yaml
  label: Shippo Webhooks API
  slug: shippo-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippo/openapi/shippo-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent third-party auditors
    period: Report covers November 2024 through November 2025 Observation period.
    report_access: on_request
    scope: null
    text: Report covers November 2024 through November 2025 Observation period.
    type: SOC 2 Type II report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Shippo maintains compliance with industry recognized standards including SOC 2 Type II and PCI DSS, validated by independent third-party auditors.
    type: PCI DSS SAQ-A and Attestation of Compliance
  trust_center:
    url: https://trust.goshippo.com/
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Shippo
provenance_date: '2026-11-10'
provider_name: Shippo
provider_slug: shippo
slug: shippo-compliance
source_date: '2026-11-10'
source_filename: shippo-compliance.yml
source_heading: Compliance
source_page: https://trust.goshippo.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Shippo\naid: shippo\nurl: https://trust.goshippo.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/shippo-trust-center.yml\ntrust_center:\n  url: https://trust.goshippo.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: Report covers November 2024 through November 2025 Observation period.\n  issuer: independent third-party auditors\n  report_access: on_request\n  text: Report covers November 2024 through November 2025 Observation period.\n- framework: PCI-DSS\n  type: PCI DSS SAQ-A and Attestation of Compliance\n  scope: null\n  period: null\n  issuer:\
  \ null\n  report_access: on_request\n  text: Shippo maintains compliance with industry recognized standards including SOC 2 Type II and PCI DSS, validated\n    by independent third-party auditors.\n"
source_yaml_url: https://artifacts.apis.io/shippo/compliance/shippo-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Shippo's own page on 2026-11-10.
synthetic: false
tags:
- E-Commerce
- Labels
- Logistics
- Returns
- Shipping
- Tracking
---
