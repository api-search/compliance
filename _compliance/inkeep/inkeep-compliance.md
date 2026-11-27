---
api_specs:
- filename: inkeep-analytics-api-openapi.yml
  format: yaml
  label: Inkeep Analytics API
  slug: inkeep-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inkeep/openapi/inkeep-analytics-api-openapi.yml
- filename: inkeep-challenge-api-openapi.yml
  format: yaml
  label: Inkeep Challenge API
  slug: inkeep-challenge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inkeep/openapi/inkeep-challenge-api-openapi.yml
- filename: inkeep-chat-sessions-api-openapi.yml
  format: yaml
  label: Inkeep Chat Sessions API
  slug: inkeep-chat-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inkeep/openapi/inkeep-chat-sessions-api-openapi.yml
- filename: inkeep-hello-api-openapi.yml
  format: yaml
  label: Inkeep Hello API
  slug: inkeep-hello-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inkeep/openapi/inkeep-hello-api-openapi.yml
- filename: inkeep-chat-completions-api-openapi.yml
  format: yaml
  label: Inkeep Chat Completions API
  slug: inkeep-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inkeep/openapi/inkeep-chat-completions-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: platform
    text: SOC 2 Type II certified platform with comprehensive data governance, PII protection, and granular access controls.
    type: SOC 2 Type II certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: platform
    text: SOC 2 Type II certified and GDPR compliant. Annual third-party audits.
    type: GDPR compliance
  trust_center:
    url: https://inkeep.com/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Inkeep
provenance_date: '2026-11-09'
provider_name: Inkeep
provider_slug: inkeep
slug: inkeep-compliance
source_date: '2026-11-09'
source_filename: inkeep-compliance.yml
source_heading: Compliance
source_page: https://inkeep.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Inkeep\naid: inkeep\nurl: https://inkeep.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/inkeep-trust-center.yml\ntrust_center:\n  url: https://inkeep.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II certified platform with comprehensive data governance, PII protection, and granular access\n    controls.\n- framework: GDPR\n  type: GDPR compliance\n  scope: platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II certified\
  \ and GDPR compliant. Annual third-party audits.\n"
source_yaml_url: https://artifacts.apis.io/inkeep/compliance/inkeep-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Inkeep's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Support
- RAG
- Agents
- Documentation
- Real-Time
---
