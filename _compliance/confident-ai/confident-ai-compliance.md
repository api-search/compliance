---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 TYPE II
    type: Type II badge
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA COMPLIANT
    type: compliance badge
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR COMPLIANT
    type: compliance badge
  trust_center:
    url: https://www.confident-ai.com/security
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Confident AI
provenance_date: '2026-11-09'
provider_name: Confident AI
provider_slug: confident-ai
slug: confident-ai-compliance
source_date: '2026-11-09'
source_filename: confident-ai-compliance.yml
source_heading: Compliance
source_page: https://www.confident-ai.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Confident AI\naid: confident-ai\nurl: https://www.confident-ai.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.confident-ai.com/security\nattestations:\n- framework: SOC2\n  type: Type II badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 TYPE II\n- framework: HIPAA\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA COMPLIANT\n- framework: GDPR\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR COMPLIANT\n"
source_yaml_url: https://artifacts.apis.io/confident-ai/compliance/confident-ai-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Confident AI's own page on 2026-11-09.
synthetic: false
tags:
- LLM Evaluation
- Open Source
- Observability
- Red Teaming
- Guardrails
- Python
- TypeScript
---
