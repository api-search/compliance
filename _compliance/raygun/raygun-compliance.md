---
api_specs:
- filename: raygun-applications-api-openapi.yml
  format: yaml
  label: Raygun Applications API
  slug: raygun-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-applications-api-openapi.yml
- filename: raygun-errors-api-openapi.yml
  format: yaml
  label: Raygun Errors API
  slug: raygun-errors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-errors-api-openapi.yml
- filename: raygun-deployments-api-openapi.yml
  format: yaml
  label: Raygun Deployments API
  slug: raygun-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-deployments-api-openapi.yml
- filename: raygun-source-maps-api-openapi.yml
  format: yaml
  label: Raygun Source Maps API
  slug: raygun-source-maps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-source-maps-api-openapi.yml
- filename: raygun-sessions-api-openapi.yml
  format: yaml
  label: Raygun Sessions API
  slug: raygun-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-sessions-api-openapi.yml
- filename: raygun-pages-api-openapi.yml
  format: yaml
  label: Raygun Pages API
  slug: raygun-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-pages-api-openapi.yml
- filename: raygun-customers-api-openapi.yml
  format: yaml
  label: Raygun Customers API
  slug: raygun-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-customers-api-openapi.yml
- filename: raygun-metrics-api-openapi.yml
  format: yaml
  label: Raygun Metrics API
  slug: raygun-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-metrics-api-openapi.yml
- filename: raygun-flutter-symbols-api-openapi.yml
  format: yaml
  label: Raygun Flutter Symbols API
  slug: raygun-flutter-symbols-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-flutter-symbols-api-openapi.yml
- filename: raygun-teams-api-openapi.yml
  format: yaml
  label: Raygun Teams API
  slug: raygun-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-teams-api-openapi.yml
- filename: raygun-invitations-api-openapi.yml
  format: yaml
  label: Raygun Invitations API
  slug: raygun-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-invitations-api-openapi.yml
- filename: raygun-plans-api-openapi.yml
  format: yaml
  label: Raygun Plans API
  slug: raygun-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-plans-api-openapi.yml
- filename: raygun-webhooks-asyncapi.yml
  format: yaml
  label: Raygun Outbound Webhooks
  slug: raygun-webhooks-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-webhooks-asyncapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: entirety of products and services
    text: Raygun is committed to GDPR compliance across the entirety of our products and services.
    type: self-stated compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: crash reporting and performance products, including e-PHI
    text: Raygun is configured for HIPAA compliance, including electronically protected health information (e-PHI).
    type: self-stated compliance
  trust_center:
    url: https://raygun.com/security
frameworks:
- GDPR
- HIPAA
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Raygun
provenance_date: '2026-11-10'
provider_name: Raygun
provider_slug: raygun
slug: raygun-compliance
source_date: '2026-11-10'
source_filename: raygun-compliance.yml
source_heading: Compliance
source_page: https://raygun.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Raygun\naid: raygun\nurl: https://raygun.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/raygun-trust-center.yml\ntrust_center:\n  url: https://raygun.com/security\nattestations:\n- framework: GDPR\n  type: self-stated compliance\n  scope: entirety of products and services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Raygun is committed to GDPR compliance across the entirety of our products and services.\n- framework: HIPAA\n  type: self-stated compliance\n  scope: crash reporting and performance products, including e-PHI\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Raygun is configured for HIPAA compliance, including electronically protected health information (e-PHI).\n"
source_yaml_url: https://artifacts.apis.io/raygun/compliance/raygun-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Raygun's own page on 2026-11-10.
synthetic: false
tags:
- Observability
- Crash Reporting
- Real User Monitoring
- Application Performance Monitoring
- Error Tracking
- Errors
- Monitoring
- DevOps
- Source Maps
- Deployment
---
