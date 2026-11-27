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
    text: We're hosted on AWS and maintain a SOC 2 Type II audit.
    type: SOC 2 Type II audit
  trust_center:
    url: https://docs.macro.com/faq.md
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Macro
provenance_date: '2026-11-10'
provider_name: Macro
provider_slug: macro
slug: macro-compliance
source_date: '2026-11-10'
source_filename: macro-compliance.yml
source_heading: Compliance
source_page: https://docs.macro.com/faq.md
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Macro\naid: macro\nurl: https://docs.macro.com/faq.md\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/macro-trust-center.yml\ntrust_center:\n  url: https://docs.macro.com/faq.md\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We're hosted on AWS and maintain a SOC 2 Type II audit.\n"
source_yaml_url: https://artifacts.apis.io/macro/compliance/macro-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Macro's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Productivity
- Email
- Collaboration
- Workspace
- CRM
- Task
- AI Agents
- MCP
- Open Source
---
