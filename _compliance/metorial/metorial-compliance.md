---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: security, availability, and confidentiality
    text: Independently audited for security, availability, and confidentiality. Reports under NDA.
    type: SOC 2 Type 2 audit
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR compliant, with a DPA , a subprocessor list , and data retention controls.
    type: GDPR compliance
  trust_center:
    url: https://metorial.com/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Metorial
provenance_date: '2026-11-10'
provider_name: Metorial
provider_slug: metorial
slug: metorial-compliance
source_date: '2026-11-10'
source_filename: metorial-compliance.yml
source_heading: Compliance
source_page: https://metorial.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Metorial\naid: metorial\nurl: https://metorial.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://metorial.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 audit\n  scope: security, availability, and confidentiality\n  period: null\n  issuer: null\n  report_access: nda\n  text: Independently audited for security, availability, and confidentiality. Reports under NDA.\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR compliant, with a DPA , a subprocessor list , and data retention controls.\n"
source_yaml_url: https://artifacts.apis.io/metorial/compliance/metorial-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Metorial's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MCP
- AI Agents
- Agentic Infrastructure
- Integration
- Developer Tools
- Serverless
---
