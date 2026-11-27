---
api_specs:
- filename: bilt-default-payment-method-api-openapi.yml
  format: yaml
  label: BILT Default payment method API
  slug: bilt-default-payment-method-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bilt/openapi/bilt-default-payment-method-api-openapi.yml
- filename: bilt-headless-payments-api-openapi.yml
  format: yaml
  label: BILT Headless payments API
  slug: bilt-headless-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bilt/openapi/bilt-headless-payments-api-openapi.yml
- filename: bilt-one-time-payments-api-openapi.yml
  format: yaml
  label: BILT One-time payments API
  slug: bilt-one-time-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bilt/openapi/bilt-one-time-payments-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 Compliance Report
    type: Type 2 report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS 4.0.1 AOC
    type: Attestation of Compliance
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 1 Type 2 Report
    type: Type 2 report
  trust_center:
    url: https://trust.bilt.com/
frameworks:
- PCI-DSS
- SOC1
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: BILT
provenance_date: '2026-11-09'
provider_name: BILT
provider_slug: bilt
slug: bilt-compliance
source_date: '2026-11-09'
source_filename: bilt-compliance.yml
source_heading: Compliance
source_page: https://trust.bilt.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: BILT\naid: bilt\nurl: https://trust.bilt.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.bilt.com/\nattestations:\n- framework: SOC2\n  type: Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Compliance Report\n- framework: PCI-DSS\n  type: Attestation of Compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS 4.0.1 AOC\n- framework: SOC1\n  type: Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1 Type 2 Report\n"
source_yaml_url: https://artifacts.apis.io/bilt/compliance/bilt-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from BILT's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Loyalty
- Payments
- RentRewards
- Credit Cards
- Real Estate
---
