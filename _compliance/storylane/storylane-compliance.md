---
api_specs:
- filename: storylane-connect
  format: yaml
  label: Storylane External API
  slug: storylane-external-api
  spec_type: Postman
  url: https://www.postman.com/team-storylane/storylane-public/collection/2zkg7jc/storylane-connect
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Compliant
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: compliance
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 42001 v2023 Certified
    type: certification
  trust_center:
    url: https://trust.storylane.io/
frameworks:
- GDPR
- ISO42001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Storylane
provenance_date: '2026-11-10'
provider_name: Storylane
provider_slug: storylane
slug: storylane-compliance
source_date: '2026-11-10'
source_filename: storylane-compliance.yml
source_heading: Compliance
source_page: https://trust.storylane.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Storylane\naid: storylane\nurl: https://trust.storylane.io/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/storylane-trust-center.yml\ntrust_center:\n  url: https://trust.storylane.io/\nattestations:\n- framework: SOC2\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Compliant\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n- framework: ISO42001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ ISO 42001 v2023 Certified\n"
source_yaml_url: https://artifacts.apis.io/storylane/compliance/storylane-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Storylane's own page on 2026-11-10.
synthetic: false
tags:
- Interactive Demos
- Product Walkthroughs
- Sales Enablement
- Marketing
- Demo Analytics
- Demo Automation
- Buyer Hub
- Sales
- MCP
- Agent Tools
- Webhook
- Embed
- oEmbed
- Demo Automation Platform
---
