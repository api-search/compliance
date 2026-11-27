---
api_specs:
- filename: telr-agreements-api-openapi.yml
  format: yaml
  label: Telr Agreements API
  slug: telr-agreements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telr/openapi/telr-agreements-api-openapi.yml
- filename: telr-hosted-payment-page-api-openapi.yml
  format: yaml
  label: Telr Hosted Payment Page API
  slug: telr-hosted-payment-page-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telr/openapi/telr-hosted-payment-page-api-openapi.yml
- filename: telr-payments-api-api-openapi.yml
  format: yaml
  label: Telr Payments API
  slug: telr-payments-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telr/openapi/telr-payments-api-api-openapi.yml
- filename: telr-remote-api-openapi.yml
  format: yaml
  label: Telr Remote API
  slug: telr-remote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telr/openapi/telr-remote-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: proprietary risk management and anti-fraud solutions
    text: Our proprietary risk management and anti-fraud solutions are PCI DSS v4.0 level 1 certified.
    type: certification
  trust_center:
    url: https://telr.com/secure
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Telr
provenance_date: '2026-11-10'
provider_name: Telr
provider_slug: telr
slug: telr-compliance
source_date: '2026-11-10'
source_filename: telr-compliance.yml
source_heading: Compliance
source_page: https://telr.com/secure
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Telr\naid: telr\nurl: https://telr.com/secure\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://telr.com/secure\nattestations:\n- framework: PCI-DSS\n  type: certification\n  scope: proprietary risk management and anti-fraud solutions\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our proprietary risk management and anti-fraud solutions are PCI DSS v4.0 level 1 certified.\n"
source_yaml_url: https://artifacts.apis.io/telr/compliance/telr-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Telr's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Payment Gateway
- Fintech
- MENA
- United Arab Emirates
---
