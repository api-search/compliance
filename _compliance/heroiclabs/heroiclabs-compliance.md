---
api_specs:
- filename: heroiclabs-nakama-api-openapi.yml
  format: yaml
  label: Nakama API
  slug: nakama-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heroiclabs/openapi/heroiclabs-nakama-api-openapi.yml
- filename: heroiclabs-console-api-openapi.yml
  format: yaml
  label: Heroic Labs Console API
  slug: heroiclabs-console-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heroiclabs/openapi/heroiclabs-console-api-openapi.yml
- filename: heroiclabs-rpc-api-openapi.yml
  format: yaml
  label: Heroic Labs Rpc API
  slug: heroiclabs-rpc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heroiclabs/openapi/heroiclabs-rpc-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Heroic Cloud / Heroic Labs security, availability, and confidentiality controls
    text: The SOC 2 Type II report is available on request.
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Heroic Cloud, Nakama, and Satori
    text: Heroic Cloud, Nakama, and Satori are fully GDPR compliant.
    type: GDPR compliance claim
  trust_center:
    url: https://heroiclabs.com/docs/heroic-cloud/concepts/enterprise/privacy-compliance/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Heroic Labs
provenance_date: '2026-11-09'
provider_name: Heroic Labs
provider_slug: heroiclabs
slug: heroiclabs-compliance
source_date: '2026-11-09'
source_filename: heroiclabs-compliance.yml
source_heading: Compliance
source_page: https://heroiclabs.com/docs/heroic-cloud/concepts/enterprise/privacy-compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Heroic Labs\naid: heroiclabs\nurl: https://heroiclabs.com/docs/heroic-cloud/concepts/enterprise/privacy-compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://heroiclabs.com/docs/heroic-cloud/concepts/enterprise/privacy-compliance/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Heroic Cloud / Heroic Labs security, availability, and confidentiality controls\n  period: null\n  issuer: null\n  report_access: on_request\n  text: The SOC 2 Type II report is available on request.\n- framework: GDPR\n  type: GDPR compliance claim\n  scope: Heroic Cloud, Nakama, and Satori\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: Heroic Cloud, Nakama, and Satori are fully GDPR compliant.\n"
source_yaml_url: https://artifacts.apis.io/heroiclabs/compliance/heroiclabs-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Heroic Labs's own page on 2026-11-09.
synthetic: false
tags:
- Game Backend
- Multiplayer
- Real-Time
- WebSocket
- Matchmaking
- Leaderboards
- Social Gaming
- Open Source
- LiveOps
- gRPC
---
