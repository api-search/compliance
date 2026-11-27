---
api_specs:
- filename: fireflies-transcripts-api-openapi.yml
  format: yaml
  label: Fireflies.ai Transcripts API
  slug: fireflies-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fireflies/openapi/fireflies-transcripts-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type II certified. You can request the report via the "Resources" tab
    type: SOC 2 Type II report
  - framework: ISO42001
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: ISO 42001 certified. You can request the report via the "Resources" tab
    type: ISO/IEC 42001:2023 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: GDPR compliant with comprehensive DPA. You can request the report via the "Resources" tab or here
    type: GDPR compliance with DPA
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Enterprise clients that enable Private Storage
    text: HIPAA compliant with BAA signed for Enterprise clients that enable Private Storage
    type: HIPAA compliance with BAA for Enterprise clients with Private Storage
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: Enterprise clients that enable Private Storage
    text: FERPA compliant with DSA signed for Enterprise clients that enable Private Storage
    type: FERPA compliance with DSA for Enterprise clients with Private Storage
  trust_center:
    url: https://trust.fireflies.ai/
frameworks:
- GDPR
- HIPAA
- ISO42001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Fireflies.ai
provenance_date: '2026-11-09'
provider_name: Fireflies.ai
provider_slug: fireflies
slug: fireflies-compliance
source_date: '2026-11-09'
source_filename: fireflies-compliance.yml
source_heading: Compliance
source_page: https://trust.fireflies.ai/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Fireflies.ai\naid: fireflies\nurl: https://trust.fireflies.ai/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.fireflies.ai/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type II certified. You can request the report via the \"Resources\" tab\n- framework: ISO42001\n  type: ISO/IEC 42001:2023 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ISO 42001 certified. You can request the report via the \"Resources\" tab\n- framework: GDPR\n  type:\
  \ GDPR compliance with DPA\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: GDPR compliant with comprehensive DPA. You can request the report via the \"Resources\" tab or here\n- framework: HIPAA\n  type: HIPAA compliance with BAA for Enterprise clients with Private Storage\n  scope: Enterprise clients that enable Private Storage\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA compliant with BAA signed for Enterprise clients that enable Private Storage\n- framework: other\n  type: FERPA compliance with DSA for Enterprise clients with Private Storage\n  scope: Enterprise clients that enable Private Storage\n  period: null\n  issuer: null\n  report_access: on_request\n  text: FERPA compliant with DSA signed for Enterprise clients that enable Private Storage\n"
source_yaml_url: https://artifacts.apis.io/fireflies/compliance/fireflies-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Fireflies.ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Meeting Assistant
- Transcription
- Summary
- Action Items
- GraphQL
- Meetings
- Productivity
- Collaboration
- Conversation Intelligence
- A2A
---
