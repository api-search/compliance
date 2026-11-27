---
api_specs:
- filename: lmnt-ai-api-openapi.yml
  format: yaml
  label: LMNT Ai API
  slug: lmnt-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lmnt/openapi/lmnt-ai-api-openapi.yml
- filename: lmnt-health-check-api-openapi.yml
  format: yaml
  label: LMNT Health Check API
  slug: lmnt-health-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lmnt/openapi/lmnt-health-check-api-openapi.yml
- filename: lmnt-speech-api-openapi.yml
  format: yaml
  label: LMNT Speech API
  slug: lmnt-speech-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lmnt/openapi/lmnt-speech-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We prioritize security and are SOC 2 Type II compliant, so you can trust our technology.
    type: SOC 2 Type II
  trust_center:
    url: https://trust.lmnt.com/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: LMNT
provenance_date: '2026-11-09'
provider_name: LMNT
provider_slug: lmnt
slug: lmnt-compliance
source_date: '2026-11-09'
source_filename: lmnt-compliance.yml
source_heading: Compliance
source_page: https://trust.lmnt.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: LMNT\naid: lmnt\nurl: https://trust.lmnt.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/lmnt-trust-center.yml\ntrust_center:\n  url: https://trust.lmnt.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We prioritize security and are SOC 2 Type II compliant, so you can trust our technology.\n"
source_yaml_url: https://artifacts.apis.io/lmnt/compliance/lmnt-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from LMNT's own page on 2026-11-09.
synthetic: false
tags:
- Text-to-Speech
- Voice Synthesis
- Voice Cloning
- Audio Streaming
- Conversational AI
- Low Latency
- Real-Time Audio
---
