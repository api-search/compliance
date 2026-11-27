---
api_specs:
- filename: gov-uk-pay-agreements-api-openapi.yml
  format: yaml
  label: GOV.UK Pay Agreements API
  slug: gov-uk-pay-agreements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gov-uk-pay/openapi/gov-uk-pay-agreements-api-openapi.yml
- filename: gov-uk-pay-authorise-card-payments-api-openapi.yml
  format: yaml
  label: GOV.UK Pay Authorise card payments API
  slug: gov-uk-pay-authorise-card-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gov-uk-pay/openapi/gov-uk-pay-authorise-card-payments-api-openapi.yml
- filename: gov-uk-pay-card-payments-api-openapi.yml
  format: yaml
  label: GOV.UK Pay Card payments API
  slug: gov-uk-pay-card-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gov-uk-pay/openapi/gov-uk-pay-card-payments-api-openapi.yml
- filename: gov-uk-pay-disputes-api-openapi.yml
  format: yaml
  label: GOV.UK Pay Disputes API
  slug: gov-uk-pay-disputes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gov-uk-pay/openapi/gov-uk-pay-disputes-api-openapi.yml
- filename: gov-uk-pay-refunding-card-payments-api-openapi.yml
  format: yaml
  label: GOV.UK Pay Refunding card payments API
  slug: gov-uk-pay-refunding-card-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gov-uk-pay/openapi/gov-uk-pay-refunding-card-payments-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: GOV.UK Pay service
    text: GOV.UK Pay is certified as fully compliant as a Level 1 Service Provider with the latest version of PCI DSS.
    type: Level 1 Service Provider certification
  trust_center:
    url: https://docs.payments.service.gov.uk/security/
frameworks:
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: GOV.UK Pay
provenance_date: '2026-11-09'
provider_name: GOV.UK Pay
provider_slug: gov-uk-pay
slug: gov-uk-pay-compliance
source_date: '2026-11-09'
source_filename: gov-uk-pay-compliance.yml
source_heading: Compliance
source_page: https://docs.payments.service.gov.uk/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: GOV.UK Pay\naid: gov-uk-pay\nurl: https://docs.payments.service.gov.uk/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/gov-uk-pay-trust-center.yml\ntrust_center:\n  url: https://docs.payments.service.gov.uk/security/\nattestations:\n- framework: PCI-DSS\n  type: Level 1 Service Provider certification\n  scope: GOV.UK Pay service\n  period: null\n  issuer: null\n  report_access: on_request\n  text: GOV.UK Pay is certified as fully compliant as a Level 1 Service Provider with the latest version of PCI\n    DSS.\n"
source_yaml_url: https://artifacts.apis.io/gov-uk-pay/compliance/gov-uk-pay-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from GOV.UK Pay's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Government
- United Kingdom
- Public Sector
- REST
- PCI DSS
- Refunds
- Recurring Payments
- Webhook
---
