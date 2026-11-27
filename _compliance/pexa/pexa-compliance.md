---
api_specs:
- filename: pexa-exchange-api-swagger.json
  format: json
  label: PEXA Exchange API
  slug: pexa-exchange-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexa/openapi/_original/pexa-exchange-api-swagger.json
- filename: pexa-billing-api-openapi.yml
  format: yaml
  label: PEXA Billing API
  slug: pexa-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexa/openapi/pexa-billing-api-openapi.yml
- filename: pexa-conversation-api-openapi.yml
  format: yaml
  label: PEXA Conversation API
  slug: pexa-conversation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexa/openapi/pexa-conversation-api-openapi.yml
- filename: pexa-document-api-openapi.yml
  format: yaml
  label: PEXA Document API
  slug: pexa-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexa/openapi/pexa-document-api-openapi.yml
- filename: pexa-invitation-api-openapi.yml
  format: yaml
  label: PEXA Invitation API
  slug: pexa-invitation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexa/openapi/pexa-invitation-api-openapi.yml
- filename: pexa-landtitle-api-openapi.yml
  format: yaml
  label: PEXA Landtitle API
  slug: pexa-landtitle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexa/openapi/pexa-landtitle-api-openapi.yml
- filename: pexa-notification-api-openapi.yml
  format: yaml
  label: PEXA Notification API
  slug: pexa-notification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexa/openapi/pexa-notification-api-openapi.yml
- filename: pexa-notification-service-api-openapi.yml
  format: yaml
  label: PEXA Notification Service [$] API
  slug: pexa-notification-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexa/openapi/pexa-notification-service-api-openapi.yml
- filename: pexa-notificationregistration-api-openapi.yml
  format: yaml
  label: PEXA Notification Registration API
  slug: pexa-notificationregistration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexa/openapi/pexa-notificationregistration-api-openapi.yml
- filename: pexa-project-api-openapi.yml
  format: yaml
  label: PEXA Project API
  slug: pexa-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexa/openapi/pexa-project-api-openapi.yml
- filename: pexa-settlement-api-openapi.yml
  format: yaml
  label: PEXA Settlement API
  slug: pexa-settlement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexa/openapi/pexa-settlement-api-openapi.yml
- filename: pexa-standalone-discharge-experience-api-openapi.yml
  format: yaml
  label: PEXA Standalone Discharge Experience API
  slug: pexa-standalone-discharge-experience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexa/openapi/pexa-standalone-discharge-experience-api-openapi.yml
- filename: pexa-subscriber-api-openapi.yml
  format: yaml
  label: PEXA Subscriber API
  slug: pexa-subscriber-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexa/openapi/pexa-subscriber-api-openapi.yml
- filename: pexa-titlesearch-api-openapi.yml
  format: yaml
  label: PEXA Title Search API
  slug: pexa-titlesearch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexa/openapi/pexa-titlesearch-api-openapi.yml
- filename: pexa-user-api-openapi.yml
  format: yaml
  label: PEXA User API
  slug: pexa-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexa/openapi/pexa-user-api-openapi.yml
- filename: pexa-workspace-api-openapi.yml
  format: yaml
  label: PEXA Workspace API
  slug: pexa-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexa/openapi/pexa-workspace-api-openapi.yml
- filename: pexa-workspaces-api-openapi.yml
  format: yaml
  label: PEXA Workspaces API
  slug: pexa-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexa/openapi/pexa-workspaces-api-openapi.yml
- filename: pexa-health-check-api-openapi.yml
  format: yaml
  label: PEXA Health Check API
  slug: pexa-health-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexa/openapi/pexa-health-check-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 Certifcate
    type: ISO 27001 certificate (title only)
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Audit Report
    type: SOC 2 audit report (title only)
  trust_center:
    url: https://compliance.pexa.com.au/s/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PEXA
provenance_date: '2026-11-10'
provider_name: PEXA
provider_slug: pexa
slug: pexa-compliance
source_date: '2026-11-10'
source_filename: pexa-compliance.yml
source_heading: Compliance
source_page: https://compliance.pexa.com.au/s/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PEXA\naid: pexa\nurl: https://compliance.pexa.com.au/s/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://compliance.pexa.com.au/s/\nattestations:\n- framework: ISO27001\n  type: ISO 27001 certificate (title only)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Certifcate\n- framework: SOC2\n  type: SOC 2 audit report (title only)\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Audit Report\n"
source_yaml_url: https://artifacts.apis.io/pexa/compliance/pexa-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from PEXA's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Australia
- Conveyancing
- Property Settlement
- Land Registry
- Title
- PropTech
- Mortgage
- Digital Signing
- Webhook
---
