---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: null
    text: Immersa, the company behind MarcoPolo, is SOC 2 Type II compliant.
    type: SOC 2 Type II
  trust_center:
    url: https://www.marcopolo.dev/trust
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Marco Polo
provenance_date: '2026-11-10'
provider_name: Marco Polo
provider_slug: marco-polo
slug: marco-polo-compliance
source_date: '2026-11-10'
source_filename: marco-polo-compliance.yml
source_heading: Compliance
source_page: https://www.marcopolo.dev/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Marco Polo\naid: marco-polo\nurl: https://www.marcopolo.dev/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/marco-polo-trust-center.yml\ntrust_center:\n  url: https://www.marcopolo.dev/trust\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: nda\n  text: Immersa, the company behind MarcoPolo, is SOC 2 Type II compliant.\n"
source_yaml_url: https://artifacts.apis.io/marco-polo/compliance/marco-polo-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Marco Polo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MCP
- Enterprise AI
- Data Governance
- AI Agents
- Data Integration
- Security
- OAuth
- Authentication
---
