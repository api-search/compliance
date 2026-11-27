---
api_specs:
- filename: transcriptfetch-system-api-openapi.yml
  format: yaml
  label: TranscriptFetch System API
  slug: transcriptfetch-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptfetch/openapi/transcriptfetch-system-api-openapi.yml
- filename: transcriptfetch-transcripts-api-openapi.yml
  format: yaml
  label: TranscriptFetch Transcripts API
  slug: transcriptfetch-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptfetch/openapi/transcriptfetch-transcripts-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CSA STAR Registry Level 1 CAIQ self-assessment, published on the Cloud Security Alliance registry
    type: Level 1 CAIQ self-assessment
  trust_center:
    url: https://transcriptfetch.com/trust
frameworks:
- CSA-STAR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: TranscriptFetch
provenance_date: '2026-11-10'
provider_name: TranscriptFetch
provider_slug: transcriptfetch
slug: transcriptfetch-compliance
source_date: '2026-11-10'
source_filename: transcriptfetch-compliance.yml
source_heading: Compliance
source_page: https://transcriptfetch.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: TranscriptFetch\naid: transcriptfetch\nurl: https://transcriptfetch.com/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/transcriptfetch-trust-center.yml\ntrust_center:\n  url: https://transcriptfetch.com/trust\nattestations:\n- framework: CSA-STAR\n  type: Level 1 CAIQ self-assessment\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA STAR Registry Level 1 CAIQ self-assessment, published on the Cloud Security Alliance registry\n"
source_yaml_url: https://artifacts.apis.io/transcriptfetch/compliance/transcriptfetch-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from TranscriptFetch's own page on 2026-11-10.
synthetic: false
tags:
- Transcripts
- Speech-to-Text
- Captions
- YouTube
- TikTok
- Instagram
- Podcasts
- MCP
- Llms.txt
- OpenAPI
- Transcription
- Video
- AI/LLM
- RAG
- Agents
- Developer Tools
- Media
- Content
- Spotify
- Apple Podcasts
---
