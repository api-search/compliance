---
api_specs:
- filename: waxell-cost-management-api-openapi.yml
  format: yaml
  label: Waxell Cost Management API
  slug: waxell-cost-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/waxell/openapi/waxell-cost-management-api-openapi.yml
- filename: waxell-governance-api-openapi.yml
  format: yaml
  label: Waxell Governance API
  slug: waxell-governance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/waxell/openapi/waxell-governance-api-openapi.yml
- filename: waxell-prompts-api-openapi.yml
  format: yaml
  label: Waxell Prompts API
  slug: waxell-prompts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/waxell/openapi/waxell-prompts-api-openapi.yml
- filename: waxell-runs-api-openapi.yml
  format: yaml
  label: Waxell Runs API
  slug: waxell-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/waxell/openapi/waxell-runs-api-openapi.yml
- filename: waxell-telemetry-api-openapi.yml
  format: yaml
  label: Waxell Telemetry API
  slug: waxell-telemetry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/waxell/openapi/waxell-telemetry-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Full compliance with EU General Data Protection Regulation. DPA available for all customers.
    type: Compliance with EU General Data Protection Regulation
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: US operations
    text: California Consumer Privacy Act compliance for US operations.
    type: Compliance with California Consumer Privacy Act
  - framework: ISO27001
    issuer: null
    period: 'Target: Q4 2026'
    report_access: unstated
    scope: Full platform
    text: 'ISO 27001 Information Security Management System certification planned for 2026. Target: Q4 2026 Scope: Full platform'
    type: ISO 27001 certification planned
  trust_center:
    url: https://waxell.ai/docs/security
frameworks:
- CCPA
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Waxell
provenance_date: '2026-11-10'
provider_name: Waxell
provider_slug: waxell
slug: waxell-compliance
source_date: '2026-11-10'
source_filename: waxell-compliance.yml
source_heading: Compliance
source_page: https://waxell.ai/docs/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Waxell\naid: waxell\nurl: https://waxell.ai/docs/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://waxell.ai/docs/security\nattestations:\n- framework: GDPR\n  type: Compliance with EU General Data Protection Regulation\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Full compliance with EU General Data Protection Regulation. DPA available for all customers.\n- framework: CCPA\n  type: Compliance with California Consumer Privacy Act\n  scope: US operations\n  period: null\n  issuer: null\n  report_access: unstated\n  text: California Consumer Privacy Act compliance\
  \ for US operations.\n- framework: ISO27001\n  type: ISO 27001 certification planned\n  scope: Full platform\n  period: 'Target: Q4 2026'\n  issuer: null\n  report_access: unstated\n  text: 'ISO 27001 Information Security Management System certification planned for 2026. Target: Q4 2026 Scope:\n    Full platform'\n"
source_yaml_url: https://artifacts.apis.io/waxell/compliance/waxell-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Waxell's own page on 2026-11-10.
synthetic: false
tags:
- AI Agent Governance
- Observability
- Policy Enforcement
- LLM Telemetry
- Cost Management
- MCP
- Agent Runtime
---
