---
api_specs:
- filename: nebulock-entities-api-openapi.yml
  format: yaml
  label: Nebulock Entities API
  slug: nebulock-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nebulock/openapi/nebulock-entities-api-openapi.yml
- filename: nebulock-findings-api-openapi.yml
  format: yaml
  label: Nebulock Findings API
  slug: nebulock-findings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nebulock/openapi/nebulock-findings-api-openapi.yml
- filename: nebulock-hunts-api-openapi.yml
  format: yaml
  label: Nebulock Hunts API
  slug: nebulock-hunts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nebulock/openapi/nebulock-hunts-api-openapi.yml
- filename: nebulock-rules-api-openapi.yml
  format: yaml
  label: Nebulock Rules API
  slug: nebulock-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nebulock/openapi/nebulock-rules-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: SOC 2 Type II Report
    type: Type II report
  trust_center:
    url: https://trust.nebulock.io/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Nebulock
provenance_date: '2026-11-10'
provider_name: Nebulock
provider_slug: nebulock
slug: nebulock-compliance
source_date: '2026-11-10'
source_filename: nebulock-compliance.yml
source_heading: Compliance
source_page: https://trust.nebulock.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Nebulock\naid: nebulock\nurl: https://trust.nebulock.io/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.nebulock.io/\nattestations:\n- framework: SOC2\n  type: Type II report\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: SOC 2 Type II Report\n"
source_yaml_url: https://artifacts.apis.io/nebulock/compliance/nebulock-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Nebulock's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Threat Hunting
- Threat Detection
- Security Operations
- Detection Engineering
- AI Agents
- SIEM
---
