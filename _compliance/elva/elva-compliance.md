---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: Theneo
    period: null
    report_access: nda
    scope: Infrastructure Elva runs on
    text: Held by Theneo, covering the infrastructure Elva runs on.
    type: Type II
  - framework: ISO27001
    issuer: Theneo
    period: null
    report_access: on_request
    scope: Information security and privacy management
    text: Information security and privacy management, held by Theneo.
    type: certified
  - framework: ISO27701
    issuer: Theneo
    period: null
    report_access: on_request
    scope: Information security and privacy management
    text: Information security and privacy management, held by Theneo.
    type: certified
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR compliant
    type: compliant
  trust_center:
    url: https://getelva.ai/security
frameworks:
- GDPR
- ISO27001
- ISO27701
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Elva
provenance_date: '2026-11-09'
provider_name: Elva
provider_slug: elva
slug: elva-compliance
source_date: '2026-11-09'
source_filename: elva-compliance.yml
source_heading: Compliance
source_page: https://getelva.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Elva\naid: elva\nurl: https://getelva.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/elva-trust-center.yml\ntrust_center:\n  url: https://getelva.ai/security\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: Infrastructure Elva runs on\n  period: null\n  issuer: Theneo\n  report_access: nda\n  text: Held by Theneo, covering the infrastructure Elva runs on.\n- framework: ISO27001\n  type: certified\n  scope: Information security and privacy management\n  period: null\n  issuer: Theneo\n  report_access: on_request\n  text: Information security and privacy management, held by Theneo.\n\
  - framework: ISO27701\n  type: certified\n  scope: Information security and privacy management\n  period: null\n  issuer: Theneo\n  report_access: on_request\n  text: Information security and privacy management, held by Theneo.\n- framework: GDPR\n  type: compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR compliant\n"
source_yaml_url: https://artifacts.apis.io/elva/compliance/elva-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Elva's own page on 2026-11-09.
synthetic: false
tags:
- API Management
- MCP Server
- MCP Logs
- MCP Insights
- API Client
- API Contract
- API Governance
- API Discovery
- OpenAPI
- API Testing
- Developer Tools
- AI Agent Infrastructure
---
