---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  trust_center:
    url: https://security.kubit.ai/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Kubit AI
provenance_date: '2026-11-09'
provider_name: Kubit AI
provider_slug: kubit-ai-inc
slug: kubit-ai-inc-compliance
source_date: '2026-11-09'
source_filename: kubit-ai-inc-compliance.yml
source_heading: Compliance
source_page: https://security.kubit.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Kubit AI\naid: kubit-ai-inc\nurl: https://security.kubit.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/kubit-ai-inc-trust-center.yml\ntrust_center:\n  url: https://security.kubit.ai/\nattestations:\n- framework: SOC2\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/kubit-ai-inc/compliance/kubit-ai-inc-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Kubit AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Analytics
- Product Analytics
- Data Warehouse
- LLM Observability
- MCP
- Agent Analytics
- OpenTelemetry
- DevOps
---
