---
api_specs:
- filename: project44-shipments-api-openapi.yml
  format: yaml
  label: project44 Shipments API
  slug: project44-shipments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/project44/openapi/project44-shipments-api-openapi.yml
- filename: project44-status-api-openapi.yml
  format: yaml
  label: project44 Status API
  slug: project44-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/project44/openapi/project44-status-api-openapi.yml
- filename: project44-tracking-api-openapi.yml
  format: yaml
  label: project44 Tracking API
  slug: project44-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/project44/openapi/project44-tracking-api-openapi.yml
- filename: project44-webhooks-api-openapi.yml
  format: yaml
  label: project44 Webhooks API
  slug: project44-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/project44/openapi/project44-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Movement platform and Last Mile platform
    text: 'Certifications: SOC 2 Type 2 , ISO 27001 , TISAX'
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: Type II audit
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: TISAX
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: EU-US DPF
    type: data transfer framework
  trust_center:
    url: https://trust.project44.com/
frameworks:
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: project44
provenance_date: '2026-11-10'
provider_name: project44
provider_slug: project44
slug: project44-compliance
source_date: '2026-11-10'
source_filename: project44-compliance.yml
source_heading: Compliance
source_page: https://trust.project44.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: project44\naid: project44\nurl: https://trust.project44.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/project44-trust-center.yml\ntrust_center:\n  url: https://trust.project44.com/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Movement platform and Last Mile platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'Certifications: SOC 2 Type 2 , ISO 27001 , TISAX'\n- framework: SOC2\n  type: Type II audit\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: other\n  type: certification\n  scope:\
  \ null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TISAX\n- framework: other\n  type: data transfer framework\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: EU-US DPF\n"
source_yaml_url: https://artifacts.apis.io/project44/compliance/project44-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from project44's own page on 2026-11-10.
synthetic: false
tags:
- Logistics
- Supply Chain Visibility
- Tracking
- Freight
- Multi-Modal
---
