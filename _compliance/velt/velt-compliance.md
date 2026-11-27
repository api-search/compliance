---
api_specs:
- filename: velt-auth-api-openapi.yml
  format: yaml
  label: Velt Auth API
  slug: velt-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/velt/openapi/velt-auth-api-openapi.yml
- filename: velt-comments-api-openapi.yml
  format: yaml
  label: Velt Comments API
  slug: velt-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/velt/openapi/velt-comments-api-openapi.yml
- filename: velt-documents-api-openapi.yml
  format: yaml
  label: Velt Documents API
  slug: velt-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/velt/openapi/velt-documents-api-openapi.yml
- filename: velt-notifications-api-openapi.yml
  format: yaml
  label: Velt Notifications API
  slug: velt-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/velt/openapi/velt-notifications-api-openapi.yml
- filename: velt-organizations-api-openapi.yml
  format: yaml
  label: Velt Organizations API
  slug: velt-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/velt/openapi/velt-organizations-api-openapi.yml
- filename: velt-users-api-openapi.yml
  format: yaml
  label: Velt Users API
  slug: velt-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/velt/openapi/velt-users-api-openapi.yml
- filename: velt-webhooks-api-openapi.yml
  format: yaml
  label: Velt Webhooks API
  slug: velt-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/velt/openapi/velt-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: maintaining compliance with SOC 2 Type II and HIPAA
    type: SOC 2 Type II
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: maintaining compliance with SOC 2 Type II and HIPAA
    type: HIPAA
  trust_center:
    url: https://trust.velt.dev/
frameworks:
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Velt
provenance_date: '2026-11-10'
provider_name: Velt
provider_slug: velt
slug: velt-compliance
source_date: '2026-11-10'
source_filename: velt-compliance.yml
source_heading: Compliance
source_page: https://trust.velt.dev/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Velt\naid: velt\nurl: https://trust.velt.dev/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/velt-trust-center.yml\ntrust_center:\n  url: https://trust.velt.dev/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: maintaining compliance with SOC 2 Type II and HIPAA\n- framework: HIPAA\n  type: HIPAA\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: maintaining compliance with SOC 2 Type II and HIPAA\n"
source_yaml_url: https://artifacts.apis.io/velt/compliance/velt-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Velt's own page on 2026-11-10.
synthetic: false
tags:
- Real-Time Collaboration
- Comments
- Presence
- Notification
- SDK
- Webhook
---
