---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: You can ask us for our report at any time.
    type: SOC 2 Type 2
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: RunReveal is CCPA compliant.
    type: compliance claim
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: RunReveal is GDPR compliant.
    type: compliance claim
  trust_center:
    url: https://runreveal.com/security
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: RunReveal
provenance_date: '2026-11-10'
provider_name: RunReveal
provider_slug: runreveal
slug: runreveal-compliance
source_date: '2026-11-10'
source_filename: runreveal-compliance.yml
source_heading: Compliance
source_page: https://runreveal.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: RunReveal\naid: runreveal\nurl: https://runreveal.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://runreveal.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: You can ask us for our report at any time.\n- framework: CCPA\n  type: compliance claim\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: RunReveal is CCPA compliant.\n- framework: GDPR\n  type: compliance claim\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: RunReveal\
  \ is GDPR compliant.\n"
source_yaml_url: https://artifacts.apis.io/runreveal/compliance/runreveal-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from RunReveal's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- SIEM
- Security Log Management
- Detection Engineering
- Threat Detection
- Incident Response
- Observability
- SQL
- MCP
- Artificial Intelligence
---
