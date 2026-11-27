---
api_specs:
- filename: barndoor-agents-api-openapi.yml
  format: yaml
  label: Barndoor Agents API
  slug: barndoor-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barndoor/openapi/barndoor-agents-api-openapi.yml
- filename: barndoor-connections-api-openapi.yml
  format: yaml
  label: Barndoor Connections API
  slug: barndoor-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barndoor/openapi/barndoor-connections-api-openapi.yml
- filename: barndoor-mcp-proxy-api-openapi.yml
  format: yaml
  label: Barndoor MCP Proxy API
  slug: barndoor-mcp-proxy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barndoor/openapi/barndoor-mcp-proxy-api-openapi.yml
- filename: barndoor-policies-api-openapi.yml
  format: yaml
  label: Barndoor Policies API
  slug: barndoor-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barndoor/openapi/barndoor-policies-api-openapi.yml
- filename: barndoor-policy-api-openapi.yml
  format: yaml
  label: Barndoor Policy API
  slug: barndoor-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barndoor/openapi/barndoor-policy-api-openapi.yml
- filename: barndoor-servers-api-openapi.yml
  format: yaml
  label: Barndoor Servers API
  slug: barndoor-servers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barndoor/openapi/barndoor-servers-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II Report
    type: SOC 2 Type II Report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO/IEC 27001:2022 Certificate
    type: ISO/IEC 27001:2022 Certificate
  trust_center:
    url: https://trust.barndoor.ai/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Barndoor
provenance_date: '2026-11-09'
provider_name: Barndoor
provider_slug: barndoor
slug: barndoor-compliance
source_date: '2026-11-09'
source_filename: barndoor-compliance.yml
source_heading: Compliance
source_page: https://trust.barndoor.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Barndoor\naid: barndoor\nurl: https://trust.barndoor.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.barndoor.ai/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II Report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II Report\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 Certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO/IEC 27001:2022 Certificate\n"
source_yaml_url: https://artifacts.apis.io/barndoor/compliance/barndoor-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Barndoor's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- AI Governance
- MCP
- Policy Enforcement
- OAuth
- Identity
- Security
- Audit
- Control Plane
- Authentication
---
