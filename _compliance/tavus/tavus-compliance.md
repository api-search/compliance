---
api_specs:
- filename: tavus-conversations-api-openapi.yml
  format: yaml
  label: Tavus Conversations API
  slug: tavus-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavus/openapi/tavus-conversations-api-openapi.yml
- filename: tavus-documents-api-openapi.yml
  format: yaml
  label: Tavus Documents API
  slug: tavus-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavus/openapi/tavus-documents-api-openapi.yml
- filename: tavus-guardrails-api-openapi.yml
  format: yaml
  label: Tavus Guardrails API
  slug: tavus-guardrails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavus/openapi/tavus-guardrails-api-openapi.yml
- filename: tavus-objectives-api-openapi.yml
  format: yaml
  label: Tavus Objectives API
  slug: tavus-objectives-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavus/openapi/tavus-objectives-api-openapi.yml
- filename: tavus-personas-api-openapi.yml
  format: yaml
  label: Tavus Personas API
  slug: tavus-personas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavus/openapi/tavus-personas-api-openapi.yml
- filename: tavus-pronunciation-dictionaries-api-openapi.yml
  format: yaml
  label: Tavus Pronunciation Dictionaries API
  slug: tavus-pronunciation-dictionaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavus/openapi/tavus-pronunciation-dictionaries-api-openapi.yml
- filename: tavus-replacements-api-openapi.yml
  format: yaml
  label: Tavus Replacements API
  slug: tavus-replacements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavus/openapi/tavus-replacements-api-openapi.yml
- filename: tavus-replicas-api-openapi.yml
  format: yaml
  label: Tavus Replicas API
  slug: tavus-replicas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavus/openapi/tavus-replicas-api-openapi.yml
- filename: tavus-transcriptions-api-openapi.yml
  format: yaml
  label: Tavus Transcriptions API
  slug: tavus-transcriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavus/openapi/tavus-transcriptions-api-openapi.yml
- filename: tavus-videos-api-openapi.yml
  format: yaml
  label: Tavus Videos API
  slug: tavus-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavus/openapi/tavus-videos-api-openapi.yml
- filename: tavus-voices-api-openapi.yml
  format: yaml
  label: Tavus Voices API
  slug: tavus-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavus/openapi/tavus-voices-api-openapi.yml
- filename: tavus-lip-sync-api-openapi.yml
  format: yaml
  label: Tavus Lip Sync API
  slug: tavus-lip-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavus/openapi/tavus-lip-sync-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2
    type: SOC 2 Type 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: null
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: null
  trust_center:
    url: https://trust.tavus.io/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Tavus
provenance_date: '2026-11-10'
provider_name: Tavus
provider_slug: tavus
slug: tavus-compliance
source_date: '2026-11-10'
source_filename: tavus-compliance.yml
source_heading: Compliance
source_page: https://trust.tavus.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Tavus\naid: tavus\nurl: https://trust.tavus.io/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/tavus-trust-center.yml\ntrust_center:\n  url: https://trust.tavus.io/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n"
source_yaml_url: https://artifacts.apis.io/tavus/compliance/tavus-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Tavus's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Generative AI
- Video
- Conversational AI
- Avatars
- Replicas
- Personalization
- Real-Time
- CVI
- Webhook
---
