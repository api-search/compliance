---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 1
    type: Type 1 report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2
    type: Type 2 report
  trust_center:
    url: https://trust.useprox.com/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Prox
provenance_date: '2026-11-10'
provider_name: Prox
provider_slug: prox
slug: prox-compliance
source_date: '2026-11-10'
source_filename: prox-compliance.yml
source_heading: Compliance
source_page: https://trust.useprox.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Prox\naid: prox\nurl: https://trust.useprox.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/prox-trust-center.yml\ntrust_center:\n  url: https://trust.useprox.com/\nattestations:\n- framework: SOC2\n  type: Type 1 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 1\n- framework: SOC2\n  type: Type 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2\n"
source_yaml_url: https://artifacts.apis.io/prox/compliance/prox-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Prox's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- MCP
- Manufacturing
- Product Support
- Knowledge Base
- Documentation
- Agents
---
