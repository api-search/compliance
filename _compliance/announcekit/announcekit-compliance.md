---
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: a SOC 2 Type II examination currently in its final stage
    type: Type II examination (in progress)
  trust_center:
    url: https://trust.announcekit.app/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: AnnounceKit
provenance_date: '2026-11-09'
provider_name: AnnounceKit
provider_slug: announcekit
slug: announcekit-compliance
source_date: '2026-11-09'
source_filename: announcekit-compliance.yml
source_heading: Compliance
source_page: https://trust.announcekit.app/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: AnnounceKit\naid: announcekit\nurl: https://trust.announcekit.app/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/announcekit-trust-center.yml\ntrust_center:\n  url: https://trust.announcekit.app/\nattestations:\n- framework: SOC2\n  type: Type II examination (in progress)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: a SOC 2 Type II examination currently in its final stage\n"
source_yaml_url: https://artifacts.apis.io/announcekit/compliance/announcekit-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from AnnounceKit's own page on 2026-11-09.
synthetic: false
tags:
- Changelog
- Feature Requests
- NPS
- Notification
- Product Communication
- Roadmaps
- Software-as-a-Service
- Widgets
---
