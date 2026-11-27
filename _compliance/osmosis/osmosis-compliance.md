---
api_specs:
- filename: osmosis-agent-api-openapi.yml
  format: yaml
  label: Osmosis Agent API
  slug: osmosis-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osmosis/openapi/osmosis-agent-api-openapi.yml
- filename: osmosis-knowledge-api-openapi.yml
  format: yaml
  label: Osmosis Knowledge API
  slug: osmosis-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osmosis/openapi/osmosis-knowledge-api-openapi.yml
- filename: osmosis-osmosis-agent-improvement-api-api-openapi.yml
  format: yaml
  label: Osmosis Agent Improvement API
  slug: osmosis-osmosis-agent-improvement-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osmosis/openapi/osmosis-osmosis-agent-improvement-api-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: compliance status
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: compliance status
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 Compliant
    type: SOC 2 Type 2
  trust_center:
    url: https://trust.osmosis.ai/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Osmosis
provenance_date: '2026-11-10'
provider_name: Osmosis
provider_slug: osmosis
slug: osmosis-compliance
source_date: '2026-11-10'
source_filename: osmosis-compliance.yml
source_heading: Compliance
source_page: https://trust.osmosis.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Osmosis\naid: osmosis\nurl: https://trust.osmosis.ai/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.osmosis.ai/\nattestations:\n- framework: HIPAA\n  type: compliance status\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n- framework: GDPR\n  type: compliance status\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Compliant\n"
source_yaml_url: https://artifacts.apis.io/osmosis/compliance/osmosis-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Osmosis's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Reinforcement Learning
- LLM
- Post-Training
- Model Training
- Agents
- Machine Learning
- Developer Tools
---
