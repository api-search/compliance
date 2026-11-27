---
api_specs:
- filename: syncly-health-api-openapi.yml
  format: yaml
  label: Syncly Health API
  slug: syncly-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/syncly/openapi/syncly-health-api-openapi.yml
- filename: syncly-well-known-api-openapi.yml
  format: yaml
  label: Syncly .well Known API
  slug: syncly-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/syncly/openapi/syncly-well-known-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Syncly is SOC 2 Type II compliant.
    type: Type II
  - framework: SOC3
    issuer: independent auditor
    period: null
    report_access: on_request
    scope: null
    text: An SOC3 report from an independent auditor is available upon request.
    type: report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Syncly is GDPR compliant.
    type: compliance
  trust_center:
    url: https://syncly.app/security
frameworks:
- GDPR
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Syncly
provenance_date: '2026-11-10'
provider_name: Syncly
provider_slug: syncly
slug: syncly-compliance
source_date: '2026-11-10'
source_filename: syncly-compliance.yml
source_heading: Compliance
source_page: https://syncly.app/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Syncly\naid: syncly\nurl: https://syncly.app/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://syncly.app/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Syncly is SOC 2 Type II compliant.\n- framework: SOC3\n  type: report\n  scope: null\n  period: null\n  issuer: independent auditor\n  report_access: on_request\n  text: An SOC3 report from an independent auditor is available upon request.\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: Syncly is GDPR compliant.\n"
source_yaml_url: https://artifacts.apis.io/syncly/compliance/syncly-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Syncly's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Intelligence
- Social Listening
- Customer Feedback
- Voice of Customer
- Creator Marketing
- Analytics
- Artificial Intelligence
- MCP
---
