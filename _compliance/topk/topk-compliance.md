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
    text: SOC 2 Type 1
    type: Type 1
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2
    type: Type 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: null
  trust_center:
    url: https://trust.topk.io/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Topk
provenance_date: '2026-11-10'
provider_name: Topk
provider_slug: topk
slug: topk-compliance
source_date: '2026-11-10'
source_filename: topk-compliance.yml
source_heading: Compliance
source_page: https://trust.topk.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Topk\naid: topk\nurl: https://trust.topk.io/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.topk.io/\nattestations:\n- framework: SOC2\n  type: Type 1\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 1\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n"
source_yaml_url: https://artifacts.apis.io/topk/compliance/topk-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Topk's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Search
- Vector Search
- Hybrid Search
- Multi-Vector Retrieval
- Semantic Search
- BM25
- Retrieval
- RAG
- Question Answering
- AI Infrastructure
- Embeddings
- MCP
---
