---
api_specs:
- filename: talkjs-conversations-api-openapi.yml
  format: yaml
  label: TalkJS Conversations API
  slug: talkjs-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkjs/openapi/talkjs-conversations-api-openapi.yml
- filename: talkjs-import-api-openapi.yml
  format: yaml
  label: TalkJS Import API
  slug: talkjs-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkjs/openapi/talkjs-import-api-openapi.yml
- filename: talkjs-messages-api-openapi.yml
  format: yaml
  label: TalkJS Messages API
  slug: talkjs-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkjs/openapi/talkjs-messages-api-openapi.yml
- filename: talkjs-participants-api-openapi.yml
  format: yaml
  label: TalkJS Participants API
  slug: talkjs-participants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkjs/openapi/talkjs-participants-api-openapi.yml
- filename: talkjs-users-api-openapi.yml
  format: yaml
  label: TalkJS Users API
  slug: talkjs-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkjs/openapi/talkjs-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security controls for protecting customer data, systems, and operational processes
    text: TalkJS is ISO 27001 certified, with audited information security controls for protecting customer data, systems, and operational processes.
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: acting as a data processor with EU hosting by default
    text: TalkJS is GDPR compliant, acting as a data processor with EU hosting by default and data processing terms included in our Terms of Service .
    type: compliance statement
  trust_center:
    url: https://talkjs.com/security/
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: TalkJS
provenance_date: '2026-11-10'
provider_name: TalkJS
provider_slug: talkjs
slug: talkjs-compliance
source_date: '2026-11-10'
source_filename: talkjs-compliance.yml
source_heading: Compliance
source_page: https://talkjs.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: TalkJS\naid: talkjs\nurl: https://talkjs.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/talkjs-trust-center.yml\ntrust_center:\n  url: https://talkjs.com/security/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: information security controls for protecting customer data, systems, and operational processes\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TalkJS is ISO 27001 certified, with audited information security controls for protecting customer data,\n    systems, and operational processes.\n- framework: GDPR\n  type: compliance statement\n\
  \  scope: acting as a data processor with EU hosting by default\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TalkJS is GDPR compliant, acting as a data processor with EU hosting by default and data processing terms\n    included in our Terms of Service .\n"
source_yaml_url: https://artifacts.apis.io/talkjs/compliance/talkjs-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from TalkJS's own page on 2026-11-10.
synthetic: false
tags:
- Chat
- Messaging
- Communications
- SDK
- Webhook
---
