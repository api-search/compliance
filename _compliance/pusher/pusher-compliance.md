---
api_specs:
- filename: pusher-asyncapi.yml
  format: yaml
  label: Pusher Channels API
  slug: channels-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/pusher/asyncapi/pusher-asyncapi.yml
- filename: pusher-channels-api-openapi.yml
  format: yaml
  label: Pusher Channels API
  slug: pusher-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pusher/openapi/pusher-channels-api-openapi.yml
- filename: pusher-events-api-openapi.yml
  format: yaml
  label: Pusher Events API
  slug: pusher-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pusher/openapi/pusher-events-api-openapi.yml
- filename: pusher-users-api-openapi.yml
  format: yaml
  label: Pusher Users API
  slug: pusher-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pusher/openapi/pusher-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Pusher infrastructure and associated products
    text: Pusher infrastructure and the products associated are ISO/IEC 27001:2013 certified.
    type: certification
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: on_request
    scope: Pusher services
    text: A completed Consensus Assessments Initiative Questionnaire (CAIQ)is available on request .
    type: CAIQ questionnaire
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: MessageBird business
    text: MessageBird conducts its business in accordance with all applicable laws and regulations, including General Data Protection Regulation (GDPR).
    type: regulatory compliance statement
  trust_center:
    url: https://pusher.com/security/
frameworks:
- CSA-STAR
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Pusher
provenance_date: '2026-11-10'
provider_name: Pusher
provider_slug: pusher
slug: pusher-compliance
source_date: '2026-11-10'
source_filename: pusher-compliance.yml
source_heading: Compliance
source_page: https://pusher.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Pusher\naid: pusher\nurl: https://pusher.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/pusher-trust-center.yml\ntrust_center:\n  url: https://pusher.com/security/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: Pusher infrastructure and associated products\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Pusher infrastructure and the products associated are ISO/IEC 27001:2013 certified.\n- framework: CSA-STAR\n  type: CAIQ questionnaire\n  scope: Pusher services\n  period: null\n  issuer: null\n  report_access: on_request\n  text: A completed\
  \ Consensus Assessments Initiative Questionnaire (CAIQ)is available on request .\n- framework: GDPR\n  type: regulatory compliance statement\n  scope: MessageBird business\n  period: null\n  issuer: null\n  report_access: unstated\n  text: MessageBird conducts its business in accordance with all applicable laws and regulations, including General\n    Data Protection Regulation (GDPR).\n"
source_yaml_url: https://artifacts.apis.io/pusher/compliance/pusher-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Pusher's own page on 2026-11-10.
synthetic: false
tags:
- Real-Time
- WebSocket
- Pub/Sub
- Push Notifications
- Messaging
---
