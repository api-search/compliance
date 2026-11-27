---
api_specs:
- filename: wellsaid-clips-api-openapi.yml
  format: yaml
  label: WellSaid Labs Clips API
  slug: wellsaid-clips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wellsaid/openapi/wellsaid-clips-api-openapi.yml
- filename: wellsaid-pronunciation-api-openapi.yml
  format: yaml
  label: WellSaid Labs Pronunciation API
  slug: wellsaid-pronunciation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wellsaid/openapi/wellsaid-pronunciation-api-openapi.yml
- filename: wellsaid-text-to-speech-api-openapi.yml
  format: yaml
  label: WellSaid Labs Text-to-Speech API
  slug: wellsaid-text-to-speech-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wellsaid/openapi/wellsaid-text-to-speech-api-openapi.yml
- filename: wellsaid-voices-api-openapi.yml
  format: yaml
  label: WellSaid Labs Voices API
  slug: wellsaid-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wellsaid/openapi/wellsaid-voices-api-openapi.yml
- filename: wellsaid-voice-avatars-api-openapi.yml
  format: yaml
  label: WellSaid Labs Voice Avatars API
  slug: wellsaid-voice-avatars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wellsaid/openapi/wellsaid-voice-avatars-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type I
    type: Type I
  - framework: SOC2
    issuer: null
    period: '2026'
    report_access: on_request
    scope: null
    text: SOC 2 Type II - 2026
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data
    text: upholding the compliance standards for personal data under General Data Protection Regulation (GDPR)
    type: null
  trust_center:
    url: https://trust.wellsaidlabs.com/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: WellSaid Labs
provenance_date: '2026-11-10'
provider_name: WellSaid Labs
provider_slug: wellsaid
slug: wellsaid-compliance
source_date: '2026-11-10'
source_filename: wellsaid-compliance.yml
source_heading: Compliance
source_page: https://trust.wellsaidlabs.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: WellSaid Labs\naid: wellsaid\nurl: https://trust.wellsaidlabs.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/wellsaid-trust-center.yml\ntrust_center:\n  url: https://trust.wellsaidlabs.com/\nattestations:\n- framework: SOC2\n  type: Type I\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type I\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type II - 2026\n- framework: GDPR\n  type: null\n  scope: personal data\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: upholding the compliance standards for personal data under General Data Protection Regulation (GDPR)\n"
source_yaml_url: https://artifacts.apis.io/wellsaid/compliance/wellsaid-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from WellSaid Labs's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Text-to-Speech
- Voice
- Audio
---
