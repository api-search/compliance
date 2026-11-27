---
api_specs:
- filename: fyno-fire-an-event-api-openapi.yml
  format: yaml
  label: Fyno Fire an Event API
  slug: fyno-fire-an-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fyno/openapi/fyno-fire-an-event-api-openapi.yml
- filename: fyno-fyno-verify-api-openapi.yml
  format: yaml
  label: Fyno Verify API
  slug: fyno-fyno-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fyno/openapi/fyno-fyno-verify-api-openapi.yml
- filename: fyno-manage-user-profiles-api-openapi.yml
  format: yaml
  label: Fyno Manage User Profiles API
  slug: fyno-manage-user-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fyno/openapi/fyno-manage-user-profiles-api-openapi.yml
- filename: fyno-manage-user-subscriptions-preferences-api-openapi.yml
  format: yaml
  label: Fyno Manage User Subscriptions & Preferences API
  slug: fyno-manage-user-subscriptions-preferences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fyno/openapi/fyno-manage-user-subscriptions-preferences-api-openapi.yml
- filename: fyno-suppression-list-api-openapi.yml
  format: yaml
  label: Fyno Suppression List API
  slug: fyno-suppression-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fyno/openapi/fyno-suppression-list-api-openapi.yml
- filename: fyno-user-properties-api-openapi.yml
  format: yaml
  label: Fyno User Properties API
  slug: fyno-user-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fyno/openapi/fyno-user-properties-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Compliant
    type: compliance badge
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 Compliant
    type: compliance badge
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: compliance badge
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: RBI SAR Compliant
    type: compliance badge (RBI SAR)
  trust_center:
    url: https://trust.fyno.io/
frameworks:
- GDPR
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Fyno
provenance_date: '2026-11-09'
provider_name: Fyno
provider_slug: fyno
slug: fyno-compliance
source_date: '2026-11-09'
source_filename: fyno-compliance.yml
source_heading: Compliance
source_page: https://trust.fyno.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Fyno\naid: fyno\nurl: https://trust.fyno.io/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/fyno-trust-center.yml\ntrust_center:\n  url: https://trust.fyno.io/\nattestations:\n- framework: SOC2\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Compliant\n- framework: ISO27001\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Compliant\n- framework: GDPR\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\
  \ Compliant\n- framework: other\n  type: compliance badge (RBI SAR)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: RBI SAR Compliant\n"
source_yaml_url: https://artifacts.apis.io/fyno/compliance/fyno-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Fyno's own page on 2026-11-09.
synthetic: false
tags:
- Notification
- Messaging
- Communications
- Push Notifications
- Email
- SMS
- WhatsApp
- In-App
- Orchestration
- Multi-Channel
---
