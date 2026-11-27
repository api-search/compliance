---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: SOC 2 Type II 2026
    type: SOC 2 Type II
  trust_center:
    url: https://trust.raindrop.ai/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Raindrop
provenance_date: '2026-11-10'
provider_name: Raindrop
provider_slug: raindrop
slug: raindrop-compliance
source_date: '2026-11-10'
source_filename: raindrop-compliance.yml
source_heading: Compliance
source_page: https://trust.raindrop.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Raindrop\naid: raindrop\nurl: https://trust.raindrop.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/raindrop-trust-center.yml\ntrust_center:\n  url: https://trust.raindrop.ai/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II 2026\n"
source_yaml_url: https://artifacts.apis.io/raindrop/compliance/raindrop-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Raindrop's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- Observability
- Monitoring
- LLMOps
- Developer Tools
- Tracing
---
