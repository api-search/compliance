---
api_specs:
- filename: albato-automations-api-openapi.yml
  format: yaml
  label: Albato Automations API
  slug: albato-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/albato/openapi/albato-automations-api-openapi.yml
- filename: albato-connectors-api-openapi.yml
  format: yaml
  label: Albato Connectors API
  slug: albato-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/albato/openapi/albato-connectors-api-openapi.yml
- filename: albato-executions-api-openapi.yml
  format: yaml
  label: Albato Executions API
  slug: albato-executions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/albato/openapi/albato-executions-api-openapi.yml
- filename: albato-teams-api-openapi.yml
  format: yaml
  label: Albato Teams API
  slug: albato-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/albato/openapi/albato-teams-api-openapi.yml
- filename: albato-templates-api-openapi.yml
  format: yaml
  label: Albato Templates API
  slug: albato-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/albato/openapi/albato-templates-api-openapi.yml
- filename: albato-users-api-openapi.yml
  format: yaml
  label: Albato Users API
  slug: albato-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/albato/openapi/albato-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Albato is SOC 2 Type 2 Certified
    type: SOC 2 Type 2 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: all data management practices
    text: we ensure that all data management practices comply with the General Data Protection Regulation (GDPR)
    type: compliance with regulation
  trust_center:
    url: https://albato.com/security
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Albato
provenance_date: '2026-11-09'
provider_name: Albato
provider_slug: albato
slug: albato-compliance
source_date: '2026-11-09'
source_filename: albato-compliance.yml
source_heading: Compliance
source_page: https://albato.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Albato\naid: albato\nurl: https://albato.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/albato-trust-center.yml\ntrust_center:\n  url: https://albato.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Albato is SOC 2 Type 2 Certified\n- framework: GDPR\n  type: compliance with regulation\n  scope: all data management practices\n  period: null\n  issuer: null\n  report_access: on_request\n  text: we ensure that all data management practices comply with the General Data Protection\
  \ Regulation (GDPR)\n"
source_yaml_url: https://artifacts.apis.io/albato/compliance/albato-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Albato's own page on 2026-11-09.
synthetic: false
tags:
- No-Code Automation
- Workflow Automation
- Embedded iPaaS
- App Integration
- Integration
- Webhook
- White Label
---
