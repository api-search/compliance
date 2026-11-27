---
api_specs:
- filename: zulip-events-asyncapi.yml
  format: yaml
  label: Zulip REST API
  slug: rest-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/zulip/asyncapi/zulip-events-asyncapi.yml
- filename: zulip-events-asyncapi.yml
  format: yaml
  label: Zulip Events API
  slug: events-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/zulip/asyncapi/zulip-events-asyncapi.yml
- filename: zulip-authentication-api-openapi.yml
  format: yaml
  label: Zulip Authentication API
  slug: zulip-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zulip/openapi/zulip-authentication-api-openapi.yml
- filename: zulip-bots-api-openapi.yml
  format: yaml
  label: Zulip Bots API
  slug: zulip-bots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zulip/openapi/zulip-bots-api-openapi.yml
- filename: zulip-channels-api-openapi.yml
  format: yaml
  label: Zulip Channels API
  slug: zulip-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zulip/openapi/zulip-channels-api-openapi.yml
- filename: zulip-drafts-api-openapi.yml
  format: yaml
  label: Zulip Drafts API
  slug: zulip-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zulip/openapi/zulip-drafts-api-openapi.yml
- filename: zulip-invites-api-openapi.yml
  format: yaml
  label: Zulip Invites API
  slug: zulip-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zulip/openapi/zulip-invites-api-openapi.yml
- filename: zulip-messages-api-openapi.yml
  format: yaml
  label: Zulip Messages API
  slug: zulip-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zulip/openapi/zulip-messages-api-openapi.yml
- filename: zulip-mobile-api-openapi.yml
  format: yaml
  label: Zulip Mobile API
  slug: zulip-mobile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zulip/openapi/zulip-mobile-api-openapi.yml
- filename: zulip-navigation-views-api-openapi.yml
  format: yaml
  label: Zulip Navigation Views API
  slug: zulip-navigation-views-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zulip/openapi/zulip-navigation-views-api-openapi.yml
- filename: zulip-real-time-events-api-openapi.yml
  format: yaml
  label: Zulip Real Time Events API
  slug: zulip-real-time-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zulip/openapi/zulip-real-time-events-api-openapi.yml
- filename: zulip-reminders-api-openapi.yml
  format: yaml
  label: Zulip Reminders API
  slug: zulip-reminders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zulip/openapi/zulip-reminders-api-openapi.yml
- filename: zulip-scheduled-messages-api-openapi.yml
  format: yaml
  label: Zulip Scheduled Messages API
  slug: zulip-scheduled-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zulip/openapi/zulip-scheduled-messages-api-openapi.yml
- filename: zulip-server-and-organizations-api-openapi.yml
  format: yaml
  label: Zulip Server And Organizations API
  slug: zulip-server-and-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zulip/openapi/zulip-server-and-organizations-api-openapi.yml
- filename: zulip-users-api-openapi.yml
  format: yaml
  label: Zulip Users API
  slug: zulip-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zulip/openapi/zulip-users-api-openapi.yml
- filename: zulip-webhooks-api-openapi.yml
  format: yaml
  label: Zulip Webhooks API
  slug: zulip-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zulip/openapi/zulip-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Zulip
    text: GDPR and CCPA compliant
    type: compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: Zulip
    text: GDPR and CCPA compliant
    type: compliance statement
  trust_center:
    url: https://zulip.com/security/
frameworks:
- CCPA
- GDPR
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Zulip
provenance_date: '2026-11-10'
provider_name: Zulip
provider_slug: zulip
slug: zulip-compliance
source_date: '2026-11-10'
source_filename: zulip-compliance.yml
source_heading: Compliance
source_page: https://zulip.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Zulip\naid: zulip\nurl: https://zulip.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/zulip-trust-center.yml\ntrust_center:\n  url: https://zulip.com/security/\nattestations:\n- framework: GDPR\n  type: compliance statement\n  scope: Zulip\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR and CCPA compliant\n- framework: CCPA\n  type: compliance statement\n  scope: Zulip\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR and CCPA compliant\n"
source_yaml_url: https://artifacts.apis.io/zulip/compliance/zulip-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Zulip's own page on 2026-11-10.
synthetic: false
tags:
- Collaboration
- Messaging
- Team Chat
- Webhook
---
