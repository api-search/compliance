---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: TexAu
    period: null
    report_access: on_request
    scope: TexAu security program
    text: SOC 2 Through our parent company, TexAu. Report on request for enterprise customers.
    type: SOC 2 report via parent company
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR DPA available
    type: DPA available
  trust_center:
    url: https://richapi.ai/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: RichAPI
provenance_date: '2026-11-10'
provider_name: RichAPI
provider_slug: richapi
slug: richapi-compliance
source_date: '2026-11-10'
source_filename: richapi-compliance.yml
source_heading: Compliance
source_page: https://richapi.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: RichAPI\naid: richapi\nurl: https://richapi.ai/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://richapi.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 report via parent company\n  scope: TexAu security program\n  period: null\n  issuer: TexAu\n  report_access: on_request\n  text: SOC 2 Through our parent company, TexAu. Report on request for enterprise customers.\n- framework: GDPR\n  type: DPA available\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR DPA available\n"
source_yaml_url: https://artifacts.apis.io/richapi/compliance/richapi-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from RichAPI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Enrichment
- B2B
- MCP
---
