---
api_specs:
- filename: converra-ai-api-openapi-generated.yml
  format: yaml
  label: Converra API Reference API
  slug: api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converra-ai/openapi/_ae-authored/converra-ai-api-openapi-generated.yml
- filename: converra-ai-core-openapi-generated.yml
  format: yaml
  label: Converra core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converra-ai/openapi/_ae-authored/converra-ai-core-openapi-generated.yml
- filename: converra-ai-guide-openapi-generated.yml
  format: yaml
  label: Converra Guide API
  slug: guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converra-ai/openapi/_ae-authored/converra-ai-guide-openapi-generated.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Security trust service criteria (CC1–CC9)
    text: SOC 2 Type II In progress. Security trust service criteria (CC1–CC9).
    type: Type II
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: Infrastructure subprocessors (MongoDB Atlas, Render)
    text: Infrastructure subprocessors (MongoDB Atlas, Render) maintain their own SOC 2 Type II reports, available under NDA.
    type: Type II (subprocessors)
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: MongoDB Atlas
    text: 'Database: MongoDB Atlas (SOC 2 Type II, ISO 27001)'
    type: certification (subprocessor)
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: Converra acts as a Service Provider under CCPA
    text: CCPA/CPRA Supported. Converra acts as a "Service Provider" under CCPA.
    type: supported
  trust_center:
    url: https://converra.ai/trust
frameworks:
- CCPA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Converra
provenance_date: '2026-11-09'
provider_name: Converra
provider_slug: converra-ai
slug: converra-ai-compliance
source_date: '2026-11-09'
source_filename: converra-ai-compliance.yml
source_heading: Compliance
source_page: https://converra.ai/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Converra\naid: converra-ai\nurl: https://converra.ai/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://converra.ai/trust\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: Security trust service criteria (CC1–CC9)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II In progress. Security trust service criteria (CC1–CC9).\n- framework: SOC2\n  type: Type II (subprocessors)\n  scope: Infrastructure subprocessors (MongoDB Atlas, Render)\n  period: null\n  issuer: null\n  report_access: nda\n  text: Infrastructure subprocessors (MongoDB Atlas, Render) maintain their\
  \ own SOC 2 Type II reports, available\n    under NDA.\n- framework: ISO27001\n  type: certification (subprocessor)\n  scope: MongoDB Atlas\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'Database: MongoDB Atlas (SOC 2 Type II, ISO 27001)'\n- framework: CCPA\n  type: supported\n  scope: Converra acts as a Service Provider under CCPA\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA/CPRA Supported. Converra acts as a \"Service Provider\" under CCPA.\n"
source_yaml_url: https://artifacts.apis.io/converra-ai/compliance/converra-ai-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Converra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Agent Optimization
- LLM Observability
- Simulation Testing
- Prompt Engineering
- MCP
---
