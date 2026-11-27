---
api_specs:
- filename: moondream-openai-compatibility-api-openapi.yml
  format: yaml
  label: Moondream OpenAI Compatibility API
  slug: moondream-openai-compatibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moondream/openapi/moondream-openai-compatibility-api-openapi.yml
- filename: moondream-skills-api-openapi.yml
  format: yaml
  label: Moondream Skills API
  slug: moondream-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moondream/openapi/moondream-skills-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Cloud hosted inference
    text: with HIPAA and SOC 2 available
    type: null
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Cloud hosted inference
    text: with HIPAA and SOC 2 available
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Enterprise plan
    text: HIPAA / BAA available
    type: BAA
  trust_center:
    url: https://moondream.ai/pricing
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Moondream
provenance_date: '2026-11-10'
provider_name: Moondream
provider_slug: moondream
slug: moondream-compliance
source_date: '2026-11-10'
source_filename: moondream-compliance.yml
source_heading: Compliance
source_page: https://moondream.ai/pricing
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Moondream\naid: moondream\nurl: https://moondream.ai/pricing\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://moondream.ai/pricing\nattestations:\n- framework: HIPAA\n  type: null\n  scope: Cloud hosted inference\n  period: null\n  issuer: null\n  report_access: unstated\n  text: with HIPAA and SOC 2 available\n- framework: SOC2\n  type: null\n  scope: Cloud hosted inference\n  period: null\n  issuer: null\n  report_access: unstated\n  text: with HIPAA and SOC 2 available\n- framework: HIPAA\n  type: BAA\n  scope: Enterprise plan\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\
  \ / BAA available\n"
source_yaml_url: https://artifacts.apis.io/moondream/compliance/moondream-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Moondream's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Computer Vision
- Vision Language Model
- Object Detection
- Image Captioning
- OCR
- Developer Tools
---
