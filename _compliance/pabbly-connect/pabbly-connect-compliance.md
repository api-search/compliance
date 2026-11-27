---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: services audited for security, availability, and confidentiality
    text: Pabbly is currently ISO 27001:2022 and SOC2 Type 2 certified.
    type: Type 2
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Pabbly is SOC2 Type 2 and ISO 27001:2022 certified.
    type: ISO 27001:2022 certification
  trust_center:
    url: https://www.pabbly.com/security
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Pabbly Connect
provenance_date: '2026-11-10'
provider_name: Pabbly Connect
provider_slug: pabbly-connect
slug: pabbly-connect-compliance
source_date: '2026-11-10'
source_filename: pabbly-connect-compliance.yml
source_heading: Compliance
source_page: https://www.pabbly.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Pabbly Connect\naid: pabbly-connect\nurl: https://www.pabbly.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/pabbly-connect-trust-center.yml\ntrust_center:\n  url: https://www.pabbly.com/security\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: services audited for security, availability, and confidentiality\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Pabbly is currently ISO 27001:2022 and SOC2 Type 2 certified.\n- framework: ISO27001\n  type: ISO 27001:2022 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ Pabbly is SOC2 Type 2 and ISO 27001:2022 certified.\n"
source_yaml_url: https://artifacts.apis.io/pabbly-connect/compliance/pabbly-connect-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Pabbly Connect's own page on 2026-11-10.
synthetic: false
tags:
- No-Code
- Workflow Automation
---
