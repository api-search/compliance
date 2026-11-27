---
api_specs:
- filename: aircover-discovery-api-openapi.yml
  format: yaml
  label: Aircover Discovery API
  slug: aircover-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aircover/openapi/aircover-discovery-api-openapi.yml
- filename: aircover-mcp-api-openapi.yml
  format: yaml
  label: Aircover MCP API
  slug: aircover-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aircover/openapi/aircover-mcp-api-openapi.yml
- filename: aircover-oauth-api-openapi.yml
  format: yaml
  label: Aircover OAuth API
  slug: aircover-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aircover/openapi/aircover-oauth-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Aircover is SOC 2 Type 2 certified, ensuring your data's security and privacy with rigorous audits.
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Aircover complies with GDPR, safeguarding your privacy with utmost care and transparency in handling personal information.
    type: null
  trust_center:
    url: https://www.aircover.ai/trust-center
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Aircover
provenance_date: '2026-11-09'
provider_name: Aircover
provider_slug: aircover
slug: aircover-compliance
source_date: '2026-11-09'
source_filename: aircover-compliance.yml
source_heading: Compliance
source_page: https://www.aircover.ai/trust-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Aircover\naid: aircover\nurl: https://www.aircover.ai/trust-center\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.aircover.ai/trust-center\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Aircover is SOC 2 Type 2 certified, ensuring your data's security and privacy with rigorous audits.\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Aircover complies with GDPR, safeguarding your privacy with utmost care and transparency in handling personal\n \
  \   information.\n"
source_yaml_url: https://artifacts.apis.io/aircover/compliance/aircover-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Aircover's own page on 2026-11-09.
synthetic: false
tags:
- Sales Enablement
- Conversation Intelligence
- Sales Coaching
- Revenue Intelligence
- AI Agents
- MCP
- Agent-Native
- CRM
- Meetings
- Transcription
- OAuth
- Authentication
---
