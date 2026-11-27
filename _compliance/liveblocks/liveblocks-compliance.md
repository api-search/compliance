---
api_specs:
- filename: liveblocks-comments-api-openapi.yml
  format: yaml
  label: Liveblocks Comments API
  slug: liveblocks-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-comments-api-openapi.yml
- filename: liveblocks-storage-api-openapi.yml
  format: yaml
  label: Liveblocks Storage API
  slug: liveblocks-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-storage-api-openapi.yml
- filename: liveblocks-yjs-api-openapi.yml
  format: yaml
  label: Liveblocks Yjs API
  slug: liveblocks-yjs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-yjs-api-openapi.yml
- filename: liveblocks-ai-api-openapi.yml
  format: yaml
  label: Liveblocks AI API
  slug: liveblocks-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-ai-api-openapi.yml
- filename: liveblocks-auth-api-openapi.yml
  format: yaml
  label: Liveblocks Auth API
  slug: liveblocks-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-auth-api-openapi.yml
- filename: liveblocks-feeds-api-openapi.yml
  format: yaml
  label: Liveblocks Feeds API
  slug: liveblocks-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-feeds-api-openapi.yml
- filename: liveblocks-groups-api-openapi.yml
  format: yaml
  label: Liveblocks Groups API
  slug: liveblocks-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-groups-api-openapi.yml
- filename: liveblocks-management-api-openapi.yml
  format: yaml
  label: Liveblocks Management API
  slug: liveblocks-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-management-api-openapi.yml
- filename: liveblocks-notifications-api-openapi.yml
  format: yaml
  label: Liveblocks Notifications API
  slug: liveblocks-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-notifications-api-openapi.yml
- filename: liveblocks-room-api-openapi.yml
  format: yaml
  label: Liveblocks Room API
  slug: liveblocks-room-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-room-api-openapi.yml
- filename: liveblocks-version-history-api-openapi.yml
  format: yaml
  label: Liveblocks Version History API
  slug: liveblocks-version-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liveblocks/openapi/liveblocks-version-history-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: SOC 2 Type 2
    type: Type 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: HIPAA
    type: null
  trust_center:
    url: https://liveblocks.safebase.us/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Liveblocks
provenance_date: '2026-11-09'
provider_name: Liveblocks
provider_slug: liveblocks
slug: liveblocks-compliance
source_date: '2026-11-09'
source_filename: liveblocks-compliance.yml
source_heading: Compliance
source_page: https://liveblocks.safebase.us/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Liveblocks\naid: liveblocks\nurl: https://liveblocks.safebase.us/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/liveblocks-trust-center.yml\ntrust_center:\n  url: https://liveblocks.safebase.us/\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 2\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: HIPAA\n"
source_yaml_url: https://artifacts.apis.io/liveblocks/compliance/liveblocks-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Liveblocks's own page on 2026-11-09.
synthetic: false
tags:
- Real-Time
- Collaboration
- Multiplayer
- Presence
- CRDT
- Yjs
- Comments
- Threads
- Notification
- WebSocket
---
