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
    text: SOC 2 Type II Compliant
    type: SOC 2 Type II
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type I Compliant
    type: SOC 2 Type I
  trust_center:
    url: https://trust.inference.net
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Inference
provenance_date: '2026-11-09'
provider_name: Inference
provider_slug: inference
slug: inference-compliance
source_date: '2026-11-09'
source_filename: inference-compliance.yml
source_heading: Compliance
source_page: https://trust.inference.net
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Inference\naid: inference\nurl: https://trust.inference.net\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.inference.net\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type II Compliant\n- framework: SOC2\n  type: SOC 2 Type I\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type I Compliant\n"
source_yaml_url: https://artifacts.apis.io/inference/compliance/inference-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Inference's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- LLM
- Inference
- Observability
- Model Training
- Model Deployment
- MCP
---
