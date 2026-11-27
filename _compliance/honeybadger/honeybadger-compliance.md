---
api_specs:
- filename: honeybadger-webhooks-asyncapi.yml
  format: yaml
  label: Honeybadger Outbound Webhook Notifications
  slug: webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/honeybadger/asyncapi/honeybadger-webhooks-asyncapi.yml
- filename: honeybadger-check-in-api-openapi.yml
  format: yaml
  label: Honeybadger Check In API
  slug: honeybadger-check-in-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honeybadger/openapi/honeybadger-check-in-api-openapi.yml
- filename: honeybadger-deploys-api-openapi.yml
  format: yaml
  label: Honeybadger Deploys API
  slug: honeybadger-deploys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honeybadger/openapi/honeybadger-deploys-api-openapi.yml
- filename: honeybadger-events-api-openapi.yml
  format: yaml
  label: Honeybadger Events API
  slug: honeybadger-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honeybadger/openapi/honeybadger-events-api-openapi.yml
- filename: honeybadger-notices-api-openapi.yml
  format: yaml
  label: Honeybadger Notices API
  slug: honeybadger-notices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honeybadger/openapi/honeybadger-notices-api-openapi.yml
- filename: honeybadger-projects-api-openapi.yml
  format: yaml
  label: Honeybadger Projects API
  slug: honeybadger-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honeybadger/openapi/honeybadger-projects-api-openapi.yml
- filename: honeybadger-source-maps-api-openapi.yml
  format: yaml
  label: Honeybadger Source Maps API
  slug: honeybadger-source-maps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honeybadger/openapi/honeybadger-source-maps-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Honeybadger is SOC2 Type II certified. Please contact us to obtain our report.
    type: Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We comply with Europe's General Data Protection Regulation (GDPR).
    type: null
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We also support HIPAA via a standard Business Associate Agreement (BAA).
    type: Business Associate Agreement
  trust_center:
    url: https://www.honeybadger.io/security/
frameworks:
- GDPR
- HIPAA
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Honeybadger
provenance_date: '2026-11-09'
provider_name: Honeybadger
provider_slug: honeybadger
slug: honeybadger-compliance
source_date: '2026-11-09'
source_filename: honeybadger-compliance.yml
source_heading: Compliance
source_page: https://www.honeybadger.io/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Honeybadger\naid: honeybadger\nurl: https://www.honeybadger.io/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/honeybadger-trust-center.yml\ntrust_center:\n  url: https://www.honeybadger.io/security/\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Honeybadger is SOC2 Type II certified. Please contact us to obtain our report.\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We comply with Europe's General Data Protection Regulation (GDPR).\n\
  - framework: HIPAA\n  type: Business Associate Agreement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We also support HIPAA via a standard Business Associate Agreement (BAA).\n"
source_yaml_url: https://artifacts.apis.io/honeybadger/compliance/honeybadger-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Honeybadger's own page on 2026-11-09.
synthetic: false
tags:
- Error Monitoring
- Exception Tracking
- Application Performance Monitoring
- Uptime Monitoring
- Cron Monitoring
- Observability
---
