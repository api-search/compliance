---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: 2026 - SOC2 Type II Report
    type: SOC 2 Type II Report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We are committed to protecting your data and ensuring that we remain fully compliant with GDPR and other applicable data protection regulations.
    type: GDPR compliance
  trust_center:
    url: https://trust.plain.com/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Plain
provenance_date: '2026-11-10'
provider_name: Plain
provider_slug: plain
slug: plain-compliance
source_date: '2026-11-10'
source_filename: plain-compliance.yml
source_heading: Compliance
source_page: https://trust.plain.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Plain\naid: plain\nurl: https://trust.plain.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/plain-trust-center.yml\ntrust_center:\n  url: https://trust.plain.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II Report\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: 2026 - SOC2 Type II Report\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are committed to protecting your data and ensuring that we remain fully compliant with GDPR and other\n    applicable data protection\
  \ regulations.\n"
source_yaml_url: https://artifacts.apis.io/plain/compliance/plain-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Plain's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Customer Service
- Help Desk
- Support
- Software-as-a-Service
- GraphQL
- Webhook
- MCP
- Developer Tools
---
