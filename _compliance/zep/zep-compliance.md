---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Yes. Zep is SOC 2 Type II certified.
    type: SOC 2 Type II certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Enterprise plan
    text: HIPAA BAAs are available with the Enterprise plan.
    type: BAA
  trust_center:
    url: https://www.getzep.com/pricing/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Zep
provenance_date: '2026-11-10'
provider_name: Zep
provider_slug: zep
slug: zep-compliance
source_date: '2026-11-10'
source_filename: zep-compliance.yml
source_heading: Compliance
source_page: https://www.getzep.com/pricing/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Zep\naid: zep\nurl: https://www.getzep.com/pricing/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/zep-trust-center.yml\ntrust_center:\n  url: https://www.getzep.com/pricing/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yes. Zep is SOC 2 Type II certified.\n- framework: HIPAA\n  type: BAA\n  scope: Enterprise plan\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA BAAs are available with the Enterprise plan.\n"
source_yaml_url: https://artifacts.apis.io/zep/compliance/zep-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Zep's own page on 2026-11-10.
synthetic: false
tags:
- Memory
- AI Agents
- Knowledge Graph
- Temporal Graph
- Graph RAG
- Context Engineering
- LangChain
- LlamaIndex
- CrewAI
- LLM
- Personalization
- Retrieval
---
