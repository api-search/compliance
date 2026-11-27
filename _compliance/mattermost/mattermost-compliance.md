---
api_specs:
- filename: mattermost-asyncapi.yml
  format: yaml
  label: Mattermost WebSocket API
  slug: websocket-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/mattermost/asyncapi/mattermost-asyncapi.yml
- filename: mattermost-channels-api-openapi.yml
  format: yaml
  label: Mattermost Channels API
  slug: mattermost-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mattermost/openapi/mattermost-channels-api-openapi.yml
- filename: mattermost-posts-api-openapi.yml
  format: yaml
  label: Mattermost Posts API
  slug: mattermost-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mattermost/openapi/mattermost-posts-api-openapi.yml
- filename: mattermost-teams-api-openapi.yml
  format: yaml
  label: Mattermost Teams API
  slug: mattermost-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mattermost/openapi/mattermost-teams-api-openapi.yml
- filename: mattermost-users-api-openapi.yml
  format: yaml
  label: Mattermost Users API
  slug: mattermost-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mattermost/openapi/mattermost-users-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: on_request
    scope: null
    text: SOC 2 Type II Report (2025)
    type: SOC 2 Type II report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 3
    type: SOC 3 badge
  - framework: ISO27001
    issuer: null
    period: '2022'
    report_access: unstated
    scope: null
    text: Mattermost ISO 27001 (2022) Certificate pdf
    type: ISO 27001:2022 certificate
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: GDPR badge
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA
    type: CCPA badge
  trust_center:
    url: https://trust.mattermost.com/
frameworks:
- CCPA
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mattermost
provenance_date: '2026-11-10'
provider_name: Mattermost
provider_slug: mattermost
slug: mattermost-compliance
source_date: '2026-11-10'
source_filename: mattermost-compliance.yml
source_heading: Compliance
source_page: https://trust.mattermost.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mattermost\naid: mattermost\nurl: https://trust.mattermost.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/mattermost-trust-center.yml\ntrust_center:\n  url: https://trust.mattermost.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type II Report (2025)\n- framework: SOC2\n  type: SOC 3 badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 3\n- framework: ISO27001\n  type: ISO 27001:2022 certificate\n  scope: null\n  period: '2022'\n  issuer: null\n\
  \  report_access: unstated\n  text: Mattermost ISO 27001 (2022) Certificate pdf\n- framework: GDPR\n  type: GDPR badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: CCPA\n  type: CCPA badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA\n"
source_yaml_url: https://artifacts.apis.io/mattermost/compliance/mattermost-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Mattermost's own page on 2026-11-10.
synthetic: false
tags:
- Messaging
- Collaboration
- Team Chat
- Open Source
- DevOps
- Self-Hosted
- Real-Time
---
