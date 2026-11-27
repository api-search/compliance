---
api_specs:
- filename: port-io-blueprints-api-openapi.yml
  format: yaml
  label: Port Blueprints API
  slug: port-io-blueprints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/port-io/openapi/port-io-blueprints-api-openapi.yml
- filename: port-io-entities-api-openapi.yml
  format: yaml
  label: Port Entities API
  slug: port-io-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/port-io/openapi/port-io-entities-api-openapi.yml
- filename: port-io-action-runs-api-openapi.yml
  format: yaml
  label: Port Action Runs API
  slug: port-io-action-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/port-io/openapi/port-io-action-runs-api-openapi.yml
- filename: port-io-actions-api-openapi.yml
  format: yaml
  label: Port Actions API
  slug: port-io-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/port-io/openapi/port-io-actions-api-openapi.yml
- filename: port-io-ai-api-openapi.yml
  format: yaml
  label: Port AI API
  slug: port-io-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/port-io/openapi/port-io-ai-api-openapi.yml
- filename: port-io-apps-api-openapi.yml
  format: yaml
  label: Port Apps API
  slug: port-io-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/port-io/openapi/port-io-apps-api-openapi.yml
- filename: port-io-audit-api-openapi.yml
  format: yaml
  label: Port Audit API
  slug: port-io-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/port-io/openapi/port-io-audit-api-openapi.yml
- filename: port-io-authentication-authorization-api-openapi.yml
  format: yaml
  label: Port Authentication / Authorization API
  slug: port-io-authentication-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/port-io/openapi/port-io-authentication-authorization-api-openapi.yml
- filename: port-io-folders-api-openapi.yml
  format: yaml
  label: Port Folders API
  slug: port-io-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/port-io/openapi/port-io-folders-api-openapi.yml
- filename: port-io-integrations-api-openapi.yml
  format: yaml
  label: Port Integrations API
  slug: port-io-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/port-io/openapi/port-io-integrations-api-openapi.yml
- filename: port-io-migrations-api-openapi.yml
  format: yaml
  label: Port Migrations API
  slug: port-io-migrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/port-io/openapi/port-io-migrations-api-openapi.yml
- filename: port-io-organization-api-openapi.yml
  format: yaml
  label: Port Organization API
  slug: port-io-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/port-io/openapi/port-io-organization-api-openapi.yml
- filename: port-io-pages-api-openapi.yml
  format: yaml
  label: Port Pages API
  slug: port-io-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/port-io/openapi/port-io-pages-api-openapi.yml
- filename: port-io-scorecard-groups-api-openapi.yml
  format: yaml
  label: Port Scorecard Groups API
  slug: port-io-scorecard-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/port-io/openapi/port-io-scorecard-groups-api-openapi.yml
- filename: port-io-scorecards-api-openapi.yml
  format: yaml
  label: Port Scorecards API
  slug: port-io-scorecards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/port-io/openapi/port-io-scorecards-api-openapi.yml
- filename: port-io-teams-api-openapi.yml
  format: yaml
  label: Port Teams API
  slug: port-io-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/port-io/openapi/port-io-teams-api-openapi.yml
- filename: port-io-users-api-openapi.yml
  format: yaml
  label: Port Users API
  slug: port-io-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/port-io/openapi/port-io-users-api-openapi.yml
- filename: port-io-webhook-api-openapi.yml
  format: yaml
  label: Port Webhook API
  slug: port-io-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/port-io/openapi/port-io-webhook-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 Certified
    type: SOC 2 Type 2 Certified
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: GDPR Compliant
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 Compliant
    type: ISO 27001 Compliant
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA Compliant
    type: CCPA Compliant
  trust_center:
    url: https://www.port.io/security
frameworks:
- CCPA
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Port
provenance_date: '2026-11-10'
provider_name: Port
provider_slug: port-io
slug: port-io-compliance
source_date: '2026-11-10'
source_filename: port-io-compliance.yml
source_heading: Compliance
source_page: https://www.port.io/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Port\naid: port-io\nurl: https://www.port.io/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/port-io-trust-center.yml\ntrust_center:\n  url: https://www.port.io/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 Certified\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Certified\n- framework: GDPR\n  type: GDPR Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n- framework: ISO27001\n  type: ISO 27001 Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: ISO 27001 Compliant\n- framework: CCPA\n  type: CCPA Compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA Compliant\n"
source_yaml_url: https://artifacts.apis.io/port-io/compliance/port-io-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Port's own page on 2026-11-10.
synthetic: false
tags:
- Internal Developer Portal
- Service Catalog
- Self-Service Actions
- Platform Engineering
- Scorecards
- Developer Experience
- Developer Portal
---
