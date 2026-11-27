---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: calendar year 2025
    report_access: on_request
    scope: security, confidentiality, and privacy
    text: Yes. The Browser Company completed a SOC 2 Type II examination for Dia covering security, confidentiality, and privacy for calendar year 2025.
    type: Type II
  trust_center:
    url: https://www.diabrowser.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Dia (The Browser Company)
provenance_date: '2026-11-09'
provider_name: Dia (The Browser Company)
provider_slug: dia-browser
slug: dia-browser-compliance
source_date: '2026-11-09'
source_filename: dia-browser-compliance.yml
source_heading: Compliance
source_page: https://www.diabrowser.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Dia (The Browser Company)\naid: dia-browser\nurl: https://www.diabrowser.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/dia-browser-trust-center.yml\ntrust_center:\n  url: https://www.diabrowser.com/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: security, confidentiality, and privacy\n  period: calendar year 2025\n  issuer: null\n  report_access: on_request\n  text: Yes. The Browser Company completed a SOC 2 Type II examination for Dia covering security, confidentiality,\n    and privacy for calendar year 2025.\n"
source_yaml_url: https://artifacts.apis.io/dia-browser/compliance/dia-browser-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Dia (The Browser Company)'s own page on 2026-11-09.
synthetic: false
tags:
- Browser
- AI Browser
- Agents
- Consumer
- The Browser Company
---
