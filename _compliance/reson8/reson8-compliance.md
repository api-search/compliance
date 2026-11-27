---
api_specs:
- filename: reson8-auth-api-openapi.yml
  format: yaml
  label: Reson8 Auth API
  slug: reson8-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reson8/openapi/reson8-auth-api-openapi.yml
- filename: reson8-custom-models-api-openapi.yml
  format: yaml
  label: Reson8 Custom Models API
  slug: reson8-custom-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reson8/openapi/reson8-custom-models-api-openapi.yml
- filename: reson8-speech-to-text-api-openapi.yml
  format: yaml
  label: Reson8 Speech to Text API
  slug: reson8-speech-to-text-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reson8/openapi/reson8-speech-to-text-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022 Certificate
    type: Certificate and audit report
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: Compliance listing
  trust_center:
    url: https://trust.reson8.dev/
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Reson8
provenance_date: '2026-11-10'
provider_name: Reson8
provider_slug: reson8
slug: reson8-compliance
source_date: '2026-11-10'
source_filename: reson8-compliance.yml
source_heading: Compliance
source_page: https://trust.reson8.dev/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Reson8\naid: reson8\nurl: https://trust.reson8.dev/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.reson8.dev/\nattestations:\n- framework: ISO27001\n  type: Certificate and audit report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 Certificate\n- framework: GDPR\n  type: Compliance listing\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/reson8/compliance/reson8-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Reson8's own page on 2026-11-10.
synthetic: false
tags:
- Speech Recognition
- Speech-to-Text
- Voice AI
- Transcription
- Diarization
- Machine Learning
- Developers
---
