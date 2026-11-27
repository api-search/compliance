---
api_specs:
- filename: betteruptime-heartbeats-api-openapi.yml
  format: yaml
  label: Better Uptime Heartbeats API
  slug: betteruptime-heartbeats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betteruptime/openapi/betteruptime-heartbeats-api-openapi.yml
- filename: betteruptime-incidents-api-openapi.yml
  format: yaml
  label: Better Uptime Incidents API
  slug: betteruptime-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betteruptime/openapi/betteruptime-incidents-api-openapi.yml
- filename: betteruptime-monitors-api-openapi.yml
  format: yaml
  label: Better Uptime Monitors API
  slug: betteruptime-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betteruptime/openapi/betteruptime-monitors-api-openapi.yml
- filename: betteruptime-status-pages-api-openapi.yml
  format: yaml
  label: Better Uptime Status Pages API
  slug: betteruptime-status-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betteruptime/openapi/betteruptime-status-pages-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Better Stack
    text: Yes, Better Stack is SOC2 Type 2 compliant. Contact us for more details or to access the latest report.
    type: Type 2
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Better Stack
    text: Yes. For more information, see our Data Processing Agreement .
    type: null
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: EU data centers used by default
    text: By default, all data is stored in the EU regions in GDPR-compliant DIN ISO/IEC 27001-certified data centers.
    type: null
  trust_center:
    url: https://betterstack.com/security
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Better Uptime
provenance_date: '2026-11-09'
provider_name: Better Uptime
provider_slug: betteruptime
slug: betteruptime-compliance
source_date: '2026-11-09'
source_filename: betteruptime-compliance.yml
source_heading: Compliance
source_page: https://betterstack.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Better Uptime\naid: betteruptime\nurl: https://betterstack.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/betteruptime-trust-center.yml\ntrust_center:\n  url: https://betterstack.com/security\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: Better Stack\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Yes, Better Stack is SOC2 Type 2 compliant. Contact us for more details or to access the latest report.\n- framework: GDPR\n  type: null\n  scope: Better Stack\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yes. For more information, see\
  \ our Data Processing Agreement .\n- framework: ISO27001\n  type: null\n  scope: EU data centers used by default\n  period: null\n  issuer: null\n  report_access: unstated\n  text: By default, all data is stored in the EU regions in GDPR-compliant DIN ISO/IEC 27001-certified data centers.\n"
source_yaml_url: https://artifacts.apis.io/betteruptime/compliance/betteruptime-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Better Uptime's own page on 2026-11-09.
synthetic: false
tags:
- Uptime Monitoring
- Incident Management
- Status Pages
- On-Call Scheduling
- Observability
- DevOps
---
