---
api_specs:
- filename: kurrent-admin-api-openapi.yml
  format: yaml
  label: Kurrent Admin API
  slug: kurrent-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kurrent/openapi/kurrent-admin-api-openapi.yml
- filename: kurrent-gossip-api-openapi.yml
  format: yaml
  label: Kurrent Gossip API
  slug: kurrent-gossip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kurrent/openapi/kurrent-gossip-api-openapi.yml
- filename: kurrent-info-api-openapi.yml
  format: yaml
  label: Kurrent Info API
  slug: kurrent-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kurrent/openapi/kurrent-info-api-openapi.yml
- filename: kurrent-projections-api-openapi.yml
  format: yaml
  label: Kurrent Projections API
  slug: kurrent-projections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kurrent/openapi/kurrent-projections-api-openapi.yml
- filename: kurrent-statistics-api-openapi.yml
  format: yaml
  label: Kurrent Statistics API
  slug: kurrent-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kurrent/openapi/kurrent-statistics-api-openapi.yml
- filename: kurrent-streams-api-openapi.yml
  format: yaml
  label: Kurrent Streams API
  slug: kurrent-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kurrent/openapi/kurrent-streams-api-openapi.yml
- filename: kurrent-subscriptions-api-openapi.yml
  format: yaml
  label: Kurrent Subscriptions API
  slug: kurrent-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kurrent/openapi/kurrent-subscriptions-api-openapi.yml
- filename: kurrent-users-api-openapi.yml
  format: yaml
  label: Kurrent Users API
  slug: kurrent-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kurrent/openapi/kurrent-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Kurrent SOC 2 Type 2 Report 07.31.25.pdf
    type: SOC 2 Type 2 report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Kurrent SOC 2 Bridge Letter 2026-08
    type: SOC 2 bridge letter
  trust_center:
    url: https://trust.kurrent.io/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Kurrent
provenance_date: '2026-11-09'
provider_name: Kurrent
provider_slug: kurrent
slug: kurrent-compliance
source_date: '2026-11-09'
source_filename: kurrent-compliance.yml
source_heading: Compliance
source_page: https://trust.kurrent.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Kurrent\naid: kurrent\nurl: https://trust.kurrent.io/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.kurrent.io/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Kurrent SOC 2 Type 2 Report 07.31.25.pdf\n- framework: SOC2\n  type: SOC 2 bridge letter\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Kurrent SOC 2 Bridge Letter 2026-08\n"
source_yaml_url: https://artifacts.apis.io/kurrent/compliance/kurrent-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Kurrent's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Database
- Event Sourcing
- Event Streaming
- Event-Driven Architecture
- CQRS
- Data Infrastructure
- Developer Tools
- Cloud
- Open Source
- gRPC
- AI Agents
---
