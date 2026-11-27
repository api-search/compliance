---
api_specs:
- filename: hotel-engine-catalogservice-api-openapi.yml
  format: yaml
  label: Engine Catalog Service API
  slug: hotel-engine-catalogservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hotel-engine/openapi/hotel-engine-catalogservice-api-openapi.yml
- filename: hotel-engine-lodgingbookingservice-api-openapi.yml
  format: yaml
  label: Engine Lodging Booking Service API
  slug: hotel-engine-lodgingbookingservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hotel-engine/openapi/hotel-engine-lodgingbookingservice-api-openapi.yml
- filename: hotel-engine-lodgingshoppingservice-api-openapi.yml
  format: yaml
  label: Engine Lodging Shopping Service API
  slug: hotel-engine-lodgingshoppingservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hotel-engine/openapi/hotel-engine-lodgingshoppingservice-api-openapi.yml
- filename: hotel-engine-content-service-api-openapi.yml
  format: yaml
  label: Engine Content Service API
  slug: hotel-engine-content-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hotel-engine/openapi/hotel-engine-content-service-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Engine SOC 2 Type II
    type: SOC 2 Type II audit report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: PCI-DSS AOC 4.0.1
    type: PCI-DSS Attestation of Compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  trust_center:
    url: https://trust.engine.com/
frameworks:
- CCPA
- GDPR
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Engine
provenance_date: '2026-11-09'
provider_name: Engine
provider_slug: hotel-engine
slug: hotel-engine-compliance
source_date: '2026-11-09'
source_filename: hotel-engine-compliance.yml
source_heading: Compliance
source_page: https://trust.engine.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Engine\naid: hotel-engine\nurl: https://trust.engine.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.engine.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Engine SOC 2 Type II\n- framework: PCI-DSS\n  type: PCI-DSS Attestation of Compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: PCI-DSS AOC 4.0.1\n- framework: CCPA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA\n- framework: GDPR\n\
  \  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/hotel-engine/compliance/hotel-engine-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Engine's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Business Travel
- Lodging
- Hotels
- Booking
- Travel Management
- Expense Management
- Payments
- gRPC
- Protobuf
- Partner API
---
