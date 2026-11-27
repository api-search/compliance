---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Compliance SOC 2
    type: null
  trust_center:
    url: https://trust.tolmo.com/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Tolmo
provenance_date: '2026-11-10'
provider_name: Tolmo
provider_slug: tolmo
slug: tolmo-compliance
source_date: '2026-11-10'
source_filename: tolmo-compliance.yml
source_heading: Compliance
source_page: https://trust.tolmo.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Tolmo\naid: tolmo\nurl: https://trust.tolmo.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/tolmo-trust-center.yml\ntrust_center:\n  url: https://trust.tolmo.com/\nattestations:\n- framework: SOC2\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliance SOC 2\n"
source_yaml_url: https://artifacts.apis.io/tolmo/compliance/tolmo-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Tolmo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Cloud Security
- Vulnerability Management
- CLI
- DevSecOps
- AI Agents
- Infrastructure Graph
---
