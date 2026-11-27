---
api_specs:
- filename: pingone-platform-api
  format: yaml
  label: PingOne Platform API
  slug: platform-api
  spec_type: Postman
  url: https://www.postman.com/ping-identity/pingone/collection/xu0baxr/pingone-platform-api
- filename: pingone-applications-api-openapi.yml
  format: yaml
  label: PingOne Applications API
  slug: pingone-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pingone/openapi/pingone-applications-api-openapi.yml
- filename: pingone-authentication-api-openapi.yml
  format: yaml
  label: PingOne Authentication API
  slug: pingone-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pingone/openapi/pingone-authentication-api-openapi.yml
- filename: pingone-environments-api-openapi.yml
  format: yaml
  label: PingOne Environments API
  slug: pingone-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pingone/openapi/pingone-environments-api-openapi.yml
- filename: pingone-populations-api-openapi.yml
  format: yaml
  label: PingOne Populations API
  slug: pingone-populations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pingone/openapi/pingone-populations-api-openapi.yml
- filename: pingone-users-api-openapi.yml
  format: yaml
  label: PingOne Users API
  slug: pingone-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pingone/openapi/pingone-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Ping Identity Service
    text: Ping Identity will maintain SOC 2 and ISO 27001 certifications or their equivalents during the term of the Agreement.
    type: certification/audit report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Ping Identity Service
    text: Ping Identity will maintain SOC 2 and ISO 27001 certifications or their equivalents during the term of the Agreement.
    type: certification
  trust_center:
    url: https://www.pingidentity.com/en-us/docs/legal/security-exhibit
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: PingOne
provenance_date: '2026-11-10'
provider_name: PingOne
provider_slug: pingone
slug: pingone-compliance
source_date: '2026-11-10'
source_filename: pingone-compliance.yml
source_heading: Compliance
source_page: https://www.pingidentity.com/en-us/docs/legal/security-exhibit
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: PingOne\naid: pingone\nurl: https://www.pingidentity.com/en-us/docs/legal/security-exhibit\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/pingone-trust-center.yml\ntrust_center:\n  url: https://www.pingidentity.com/en-us/docs/legal/security-exhibit\nattestations:\n- framework: SOC2\n  type: certification/audit report\n  scope: Ping Identity Service\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Ping Identity will maintain SOC 2 and ISO 27001 certifications or their equivalents during the term of the\n    Agreement.\n- framework: ISO27001\n  type: certification\n  scope: Ping\
  \ Identity Service\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Ping Identity will maintain SOC 2 and ISO 27001 certifications or their equivalents during the term of the\n    Agreement.\n"
source_yaml_url: https://artifacts.apis.io/pingone/compliance/pingone-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from PingOne's own page on 2026-11-10.
synthetic: false
tags:
- Identity
- Authentication
- Authorization
- SSO
- Multi-Factor Authentication
- Identity and Access Management
- CIAM
- Identity Federation
---
