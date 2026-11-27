---
api_specs:
- filename: warp-agent-api-openapi.yml
  format: yaml
  label: Warp Agent API
  slug: warp-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/warp/openapi/warp-agent-api-openapi.yml
- filename: warp-harness-support-api-openapi.yml
  format: yaml
  label: Warp Harness Support API
  slug: warp-harness-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/warp/openapi/warp-harness-support-api-openapi.yml
- filename: warp-schedules-api-openapi.yml
  format: yaml
  label: Warp Schedules API
  slug: warp-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/warp/openapi/warp-schedules-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: accredited third party
    period: null
    report_access: on_request
    scope: null
    text: Yes, Warp has obtained a SOC 2 Type 2 attestation from an accredited third party. Visit Warp’s Trust Center to request the report.
    type: Type 2 attestation
  trust_center:
    url: https://www.warp.dev/legal/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Warp
provenance_date: '2026-11-10'
provider_name: Warp
provider_slug: warp
slug: warp-compliance
source_date: '2026-11-10'
source_filename: warp-compliance.yml
source_heading: Compliance
source_page: https://www.warp.dev/legal/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Warp\naid: warp\nurl: https://www.warp.dev/legal/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/warp-trust-center.yml\ntrust_center:\n  url: https://www.warp.dev/legal/security\nattestations:\n- framework: SOC2\n  type: Type 2 attestation\n  scope: null\n  period: null\n  issuer: accredited third party\n  report_access: on_request\n  text: Yes, Warp has obtained a SOC 2 Type 2 attestation from an accredited third party. Visit Warp’s Trust Center\n    to request the report.\n"
source_yaml_url: https://artifacts.apis.io/warp/compliance/warp-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Warp's own page on 2026-11-10.
synthetic: false
tags:
- Developer Tools
- Terminal
- AI Agents
- Cloud Agents
- Agentic Development
---
