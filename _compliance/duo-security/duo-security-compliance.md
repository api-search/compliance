---
api_specs:
- filename: duo-security-bulk-api-openapi.yml
  format: yaml
  label: Duo Security Bulk API
  slug: duo-security-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duo-security/openapi/duo-security-bulk-api-openapi.yml
- filename: duo-security-bypass-codes-api-openapi.yml
  format: yaml
  label: Duo Security Bypass Codes API
  slug: duo-security-bypass-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duo-security/openapi/duo-security-bypass-codes-api-openapi.yml
- filename: duo-security-groups-api-openapi.yml
  format: yaml
  label: Duo Security Groups API
  slug: duo-security-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duo-security/openapi/duo-security-groups-api-openapi.yml
- filename: duo-security-phones-api-openapi.yml
  format: yaml
  label: Duo Security Phones API
  slug: duo-security-phones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duo-security/openapi/duo-security-phones-api-openapi.yml
- filename: duo-security-tokens-api-openapi.yml
  format: yaml
  label: Duo Security Tokens API
  slug: duo-security-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duo-security/openapi/duo-security-tokens-api-openapi.yml
- filename: duo-security-users-api-openapi.yml
  format: yaml
  label: Duo Security Users API
  slug: duo-security-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duo-security/openapi/duo-security-users-api-openapi.yml
- filename: duo-security-webauthn-api-openapi.yml
  format: yaml
  label: Duo Security WebAuthn API
  slug: duo-security-webauthn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duo-security/openapi/duo-security-webauthn-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Duo data centers
    text: Duo’s data centers are ISO27001 and SOC2 compliant
    type: compliance statement
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Duo data centers
    text: Duo’s data centers are ISO27001 and SOC2 compliant
    type: compliance statement
  trust_center:
    url: https://duo.com/support/security-and-reliability
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Duo Security
provenance_date: '2026-11-09'
provider_name: Duo Security
provider_slug: duo-security
slug: duo-security-compliance
source_date: '2026-11-09'
source_filename: duo-security-compliance.yml
source_heading: Compliance
source_page: https://duo.com/support/security-and-reliability
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Duo Security\naid: duo-security\nurl: https://duo.com/support/security-and-reliability\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/duo-security-trust-center.yml\ntrust_center:\n  url: https://duo.com/support/security-and-reliability\nattestations:\n- framework: ISO27001\n  type: compliance statement\n  scope: Duo data centers\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Duo’s data centers are ISO27001 and SOC2 compliant\n- framework: SOC2\n  type: compliance statement\n  scope: Duo data centers\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Duo’s data\
  \ centers are ISO27001 and SOC2 compliant\n"
source_yaml_url: https://artifacts.apis.io/duo-security/compliance/duo-security-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Duo Security's own page on 2026-11-09.
synthetic: false
tags:
- Authentication
- MFA
- Zero Trust
- Identity
- Identity Federation
- Security
- Multi-Factor Authentication
- Identity and Access Management
- Cloud Services
- Enterprise
---
