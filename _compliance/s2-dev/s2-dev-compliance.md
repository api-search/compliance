---
api_specs:
- filename: s2-dev-access-tokens-api-openapi.yml
  format: yaml
  label: S2 Dev Access Tokens API
  slug: s2-dev-access-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/s2-dev/openapi/s2-dev-access-tokens-api-openapi.yml
- filename: s2-dev-basins-api-openapi.yml
  format: yaml
  label: S2 Dev Basins API
  slug: s2-dev-basins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/s2-dev/openapi/s2-dev-basins-api-openapi.yml
- filename: s2-dev-locations-api-openapi.yml
  format: yaml
  label: S2 Dev Locations API
  slug: s2-dev-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/s2-dev/openapi/s2-dev-locations-api-openapi.yml
- filename: s2-dev-metrics-api-openapi.yml
  format: yaml
  label: S2 Dev Metrics API
  slug: s2-dev-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/s2-dev/openapi/s2-dev-metrics-api-openapi.yml
- filename: s2-dev-records-api-openapi.yml
  format: yaml
  label: S2 Dev Records API
  slug: s2-dev-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/s2-dev/openapi/s2-dev-records-api-openapi.yml
- filename: s2-dev-streams-api-openapi.yml
  format: yaml
  label: S2 Dev Streams API
  slug: s2-dev-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/s2-dev/openapi/s2-dev-streams-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Email trust@s2.dev to request access to our SOC 2 report
    type: SOC 2 report
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: for HIPAA BAA
    type: Business Associate Agreement (BAA)
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: or GDPR DPA
    type: Data Processing Agreement (DPA)
  trust_center:
    url: https://s2.dev/docs/platform/security
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: S2 Dev
provenance_date: '2026-11-10'
provider_name: S2 Dev
provider_slug: s2-dev
slug: s2-dev-compliance
source_date: '2026-11-10'
source_filename: s2-dev-compliance.yml
source_heading: Compliance
source_page: https://s2.dev/docs/platform/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: S2 Dev\naid: s2-dev\nurl: https://s2.dev/docs/platform/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://s2.dev/docs/platform/security\nattestations:\n- framework: SOC2\n  type: SOC 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Email trust@s2.dev to request access to our SOC 2 report\n- framework: HIPAA\n  type: Business Associate Agreement (BAA)\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: for HIPAA BAA\n- framework: GDPR\n  type: Data Processing Agreement (DPA)\n  scope: null\n  period: null\n  issuer: null\n\
  \  report_access: on_request\n  text: or GDPR DPA\n"
source_yaml_url: https://artifacts.apis.io/s2-dev/compliance/s2-dev-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from S2 Dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Streaming
- Real-Time
- Event Streaming
- Durable Storage
- Message Streaming
- Data Feed
- Observability
- Developer Tools
- Infrastructure
---
