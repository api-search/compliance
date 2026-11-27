---
api_specs:
- filename: docs
  format: yaml
  label: Gladia Live (Real-time) API
  slug: gladia-live-real-time-api
  spec_type: AsyncAPI
  url: https://github.com/gladiaio/docs
- filename: gladia-audiototext-api-openapi.yml
  format: yaml
  label: Gladia AudioToText API
  slug: gladia-audiototext-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gladia/openapi/gladia-audiototext-api-openapi.yml
- filename: gladia-file-management-api-openapi.yml
  format: yaml
  label: Gladia File Management API
  slug: gladia-file-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gladia/openapi/gladia-file-management-api-openapi.yml
- filename: gladia-job-history-api-openapi.yml
  format: yaml
  label: Gladia Job History API
  slug: gladia-job-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gladia/openapi/gladia-job-history-api-openapi.yml
- filename: gladia-live-v2-api-openapi.yml
  format: yaml
  label: Gladia Live V2 API
  slug: gladia-live-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gladia/openapi/gladia-live-v2-api-openapi.yml
- filename: gladia-pre-recorded-v2-api-openapi.yml
  format: yaml
  label: Gladia Pre-recorded V2 API
  slug: gladia-pre-recorded-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gladia/openapi/gladia-pre-recorded-v2-api-openapi.yml
- filename: gladia-transcription-v1-api-openapi.yml
  format: yaml
  label: Gladia Transcription V1 API
  slug: gladia-transcription-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gladia/openapi/gladia-transcription-v1-api-openapi.yml
- filename: gladia-transcription-v2-api-openapi.yml
  format: yaml
  label: Gladia Transcription V2 API
  slug: gladia-transcription-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gladia/openapi/gladia-transcription-v2-api-openapi.yml
- filename: gladia-open-router-api-openapi.yml
  format: yaml
  label: Gladia Open Router API
  slug: gladia-open-router-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gladia/openapi/gladia-open-router-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Gladia has achieved SOC 2 Type 1 and Type 2 compliance
    type: Type 1 and Type 2
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Gladia is compliant with the General Data Protection Regulation (GDPR)
    type: compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: compliance
  trust_center:
    url: https://www.gladia.io/security
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Gladia
provenance_date: '2026-11-09'
provider_name: Gladia
provider_slug: gladia
slug: gladia-compliance
source_date: '2026-11-09'
source_filename: gladia-compliance.yml
source_heading: Compliance
source_page: https://www.gladia.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Gladia\naid: gladia\nurl: https://www.gladia.io/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/gladia-trust-center.yml\ntrust_center:\n  url: https://www.gladia.io/security\nattestations:\n- framework: SOC2\n  type: Type 1 and Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Gladia has achieved SOC 2 Type 1 and Type 2 compliance\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Gladia is compliant with the General Data Protection Regulation (GDPR)\n- framework: HIPAA\n  type: compliance\n\
  \  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n"
source_yaml_url: https://artifacts.apis.io/gladia/compliance/gladia-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Gladia's own page on 2026-11-09.
synthetic: false
tags:
- Speech-to-Text
- Transcription
- Audio Intelligence
- Real-Time
- Speaker Diarization
- Translation
- WebSocket
- REST
---
