---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type II Report Request access
    type: SOC 2 Type II Report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: ISO 27001 Certificate Request access
    type: ISO 27001 Certificate
  trust_center:
    url: https://trust.solveintelligence.com/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Solve Intelligence
provenance_date: '2026-11-10'
provider_name: Solve Intelligence
provider_slug: solve-intelligence
slug: solve-intelligence-compliance
source_date: '2026-11-10'
source_filename: solve-intelligence-compliance.yml
source_heading: Compliance
source_page: https://trust.solveintelligence.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Solve Intelligence\naid: solve-intelligence\nurl: https://trust.solveintelligence.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/solve-intelligence-trust-center.yml\ntrust_center:\n  url: https://trust.solveintelligence.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II Report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type II Report Request access\n- framework: ISO27001\n  type: ISO 27001 Certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO 27001 Certificate Request access\n"
source_yaml_url: https://artifacts.apis.io/solve-intelligence/compliance/solve-intelligence-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Solve Intelligence's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Intellectual Property
- Patents
- Artificial Intelligence
- Document Generation
- Search
- MCP
- Agents
---
