---
api_specs:
- filename: bitso-asyncapi.yml
  format: yaml
  label: Bitso WebSocket API
  slug: websocket
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/bitso/asyncapi/bitso-asyncapi.yml
- filename: bitso-private-api-openapi.yml
  format: yaml
  label: Bitso Private API
  slug: bitso-private-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitso/openapi/bitso-private-api-openapi.yml
- filename: bitso-public-api-openapi.yml
  format: yaml
  label: Bitso Public API
  slug: bitso-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitso/openapi/bitso-public-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We’re ISO/IEC 27001:2022 certified.
    type: certification
  trust_center:
    url: https://bitso.com/trust
frameworks:
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Bitso
provenance_date: '2026-11-09'
provider_name: Bitso
provider_slug: bitso
slug: bitso-compliance
source_date: '2026-11-09'
source_filename: bitso-compliance.yml
source_heading: Compliance
source_page: https://bitso.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Bitso\naid: bitso\nurl: https://bitso.com/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/bitso-trust-center.yml\ntrust_center:\n  url: https://bitso.com/trust\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We’re ISO/IEC 27001:2022 certified.\n"
source_yaml_url: https://artifacts.apis.io/bitso/compliance/bitso-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Bitso's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- Exchange
- Trading
- Stablecoins
- Payouts
- Cross-Border
- Latin America
- Mexico
- Fintech
- Real-Time
---
