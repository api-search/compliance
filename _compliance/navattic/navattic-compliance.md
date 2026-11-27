---
api_specs:
- filename: navattic-health-api-openapi.yml
  format: yaml
  label: Navattic Health API
  slug: navattic-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/navattic/openapi/navattic-health-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: not stated
    text: Navattic SOC 2 Type II
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: not stated
    text: GDPR
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Navattic
    source: https://docs.navattic.com/workspace/security
    text: Current certifications, including SOC 2 Type II and GDPR compliance, are listed on the Navattic Trust Center .
    type: SOC 2 Type II certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: Navattic
    source: https://docs.navattic.com/workspace/security
    text: Current certifications, including SOC 2 Type II and GDPR compliance, are listed on the Navattic Trust Center .
    type: GDPR compliance
  trust_center:
    url: https://trust.navattic.com/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Navattic
provenance_date: '2026-11-10'
provider_name: Navattic
provider_slug: navattic
slug: navattic-compliance
source_date: '2026-11-10'
source_filename: navattic-compliance.yml
source_heading: Compliance
source_page: https://trust.navattic.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Navattic\naid: navattic\nurl: https://trust.navattic.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/navattic-trust-center.yml\n  sources:\n  - https://docs.navattic.com/workspace/security\n  - https://trust.navattic.com/\ntrust_center:\n  url: https://trust.navattic.com/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: not stated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Navattic SOC 2 Type II\n- framework: GDPR\n  type: null\n  scope: not stated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: SOC2\n  type: SOC 2 Type\
  \ II certification\n  scope: Navattic\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Current certifications, including SOC 2 Type II and GDPR compliance, are listed on the Navattic Trust Center\n    .\n  source: https://docs.navattic.com/workspace/security\n- framework: GDPR\n  type: GDPR compliance\n  scope: Navattic\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Current certifications, including SOC 2 Type II and GDPR compliance, are listed on the Navattic Trust Center\n    .\n  source: https://docs.navattic.com/workspace/security\n"
source_yaml_url: https://artifacts.apis.io/navattic/compliance/navattic-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Navattic's own page on 2026-11-10.
synthetic: false
tags:
- Interactive Demos
- Product Demo
- Sales Enablement
- Marketing
- No-Code
- Webhook
- CRM Integration
- Sales Automation
- MCP
- Agents
- Product Analytics
- A2A
---
