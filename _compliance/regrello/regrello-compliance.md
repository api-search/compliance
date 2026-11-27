---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Regrello service
    text: To receive a copy of our SOC 2 Type 2 report please contact compliance@regrello.com
    type: SOC 2 Type 2 report
  trust_center:
    url: https://www.regrello.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Regrello
provenance_date: '2026-11-10'
provider_name: Regrello
provider_slug: regrello
slug: regrello-compliance
source_date: '2026-11-10'
source_filename: regrello-compliance.yml
source_heading: Compliance
source_page: https://www.regrello.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Regrello\naid: regrello\nurl: https://www.regrello.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/regrello-trust-center.yml\ntrust_center:\n  url: https://www.regrello.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: Regrello service\n  period: null\n  issuer: null\n  report_access: on_request\n  text: To receive a copy of our SOC 2 Type 2 report please contact compliance@regrello.com\n"
source_yaml_url: https://artifacts.apis.io/regrello/compliance/regrello-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Regrello's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Manufacturing
- Supply Chain
- Workflow Automation
- Artificial Intelligence
- AI Agents
- Process Orchestration
---
