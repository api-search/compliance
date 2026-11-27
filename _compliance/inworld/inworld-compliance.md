---
api_specs:
- filename: inworld-models-api-openapi.yml
  format: yaml
  label: Inworld AI Models API
  slug: inworld-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inworld/openapi/inworld-models-api-openapi.yml
- filename: inworld-realtime-api-openapi.yml
  format: yaml
  label: Inworld AI Realtime API
  slug: inworld-realtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inworld/openapi/inworld-realtime-api-openapi.yml
- filename: inworld-router-api-openapi.yml
  format: yaml
  label: Inworld AI Router API
  slug: inworld-router-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inworld/openapi/inworld-router-api-openapi.yml
- filename: inworld-stt-api-openapi.yml
  format: yaml
  label: Inworld AI STT API
  slug: inworld-stt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inworld/openapi/inworld-stt-api-openapi.yml
- filename: inworld-tts-api-openapi.yml
  format: yaml
  label: Inworld AI TTS API
  slug: inworld-tts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inworld/openapi/inworld-tts-api-openapi.yml
- filename: inworld-voices-api-openapi.yml
  format: yaml
  label: Inworld AI Voices API
  slug: inworld-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inworld/openapi/inworld-voices-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: unstated
    scope: Security, Availability and Confidentiality
    text: An independent auditor examines our security controls every year for SOC 2 Type II.
    type: SOC 2 Type II certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: US rules for protecting health information
    text: We meet HIPAA, the US rules for protecting health information.
    type: HIPAA compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU regional deployment keeps processing and storage inside the EU
    text: An EU regional deployment also keeps processing and storage inside the EU.
    type: GDPR compliance
  trust_center:
    url: https://inworld.ai/security
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Inworld AI
provenance_date: '2026-11-09'
provider_name: Inworld AI
provider_slug: inworld
slug: inworld-compliance
source_date: '2026-11-09'
source_filename: inworld-compliance.yml
source_heading: Compliance
source_page: https://inworld.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Inworld AI\naid: inworld\nurl: https://inworld.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/inworld-trust-center.yml\ntrust_center:\n  url: https://inworld.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: Security, Availability and Confidentiality\n  period: null\n  issuer: independent auditor\n  report_access: unstated\n  text: An independent auditor examines our security controls every year for SOC 2 Type II.\n- framework: HIPAA\n  type: HIPAA compliance\n  scope: US rules for protecting health information\n  period: null\n  issuer: null\n\
  \  report_access: unstated\n  text: We meet HIPAA, the US rules for protecting health information.\n- framework: GDPR\n  type: GDPR compliance\n  scope: EU regional deployment keeps processing and storage inside the EU\n  period: null\n  issuer: null\n  report_access: unstated\n  text: An EU regional deployment also keeps processing and storage inside the EU.\n"
source_yaml_url: https://artifacts.apis.io/inworld/compliance/inworld-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Inworld AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Voice
- Characters
- Games
- Conversational AI
- A2A
---
