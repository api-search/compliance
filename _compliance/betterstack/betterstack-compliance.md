---
api_specs:
- filename: betterstack-heartbeats-api-openapi.yml
  format: yaml
  label: Better Stack Heartbeats API
  slug: betterstack-heartbeats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betterstack/openapi/betterstack-heartbeats-api-openapi.yml
- filename: betterstack-incidents-api-openapi.yml
  format: yaml
  label: Better Stack Incidents API
  slug: betterstack-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betterstack/openapi/betterstack-incidents-api-openapi.yml
- filename: betterstack-monitors-api-openapi.yml
  format: yaml
  label: Better Stack Monitors API
  slug: betterstack-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betterstack/openapi/betterstack-monitors-api-openapi.yml
- filename: betterstack-status-pages-api-openapi.yml
  format: yaml
  label: Better Stack Status Pages API
  slug: betterstack-status-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betterstack/openapi/betterstack-status-pages-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Yes, Better Stack is SOC2 Type 2 compliant. Contact us for more details or to access the latest report.
    type: Type 2
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Yes. For more information, see our Data Processing Agreement .
    type: null
  trust_center:
    url: https://betterstack.com/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Better Stack
provenance_date: '2026-11-09'
provider_name: Better Stack
provider_slug: betterstack
slug: betterstack-compliance
source_date: '2026-11-09'
source_filename: betterstack-compliance.yml
source_heading: Compliance
source_page: https://betterstack.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Better Stack\naid: betterstack\nurl: https://betterstack.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/betterstack-trust-center.yml\ntrust_center:\n  url: https://betterstack.com/security\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Yes, Better Stack is SOC2 Type 2 compliant. Contact us for more details or to access the latest report.\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yes. For more information, see our Data Processing\
  \ Agreement .\n"
source_yaml_url: https://artifacts.apis.io/betterstack/compliance/betterstack-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Better Stack's own page on 2026-11-09.
synthetic: false
tags:
- Observability
- Uptime Monitoring
- Incidents
- Logs
- Monitoring
- Status Pages
- On-Call
- Error Tracking
- OpenTelemetry
- MCP
---
