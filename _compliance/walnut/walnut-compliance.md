---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CSA STAR - Self Assessment
    type: Self Assessment
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC2 Request
    type: null
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA GDPR
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA GDPR
    type: null
  trust_center:
    url: https://security.walnut.io/
frameworks:
- CCPA
- CSA-STAR
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Walnut
provenance_date: '2026-11-10'
provider_name: Walnut
provider_slug: walnut
slug: walnut-compliance
source_date: '2026-11-10'
source_filename: walnut-compliance.yml
source_heading: Compliance
source_page: https://security.walnut.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Walnut\naid: walnut\nurl: https://security.walnut.io/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/walnut-trust-center.yml\ntrust_center:\n  url: https://security.walnut.io/\nattestations:\n- framework: CSA-STAR\n  type: Self Assessment\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA STAR - Self Assessment\n- framework: SOC2\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC2 Request\n- framework: CCPA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA GDPR\n\
  - framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA GDPR\n"
source_yaml_url: https://artifacts.apis.io/walnut/compliance/walnut-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Walnut's own page on 2026-11-10.
synthetic: false
tags:
- Sales Demo
- Interactive Demos
- Product Demos
- Sales Enablement
- Demo Analytics
- Go-To-Market
- Webhook
- MCP
- Analytics
---
