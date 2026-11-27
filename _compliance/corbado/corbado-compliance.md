---
api_specs:
- filename: corbado-exports-api-openapi.yml
  format: yaml
  label: Corbado Exports API
  slug: corbado-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corbado/openapi/corbado-exports-api-openapi.yml
- filename: corbado-identifiers-api-openapi.yml
  format: yaml
  label: Corbado Identifiers API
  slug: corbado-identifiers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corbado/openapi/corbado-identifiers-api-openapi.yml
- filename: corbado-passkeyevents-api-openapi.yml
  format: yaml
  label: Corbado PasskeyEvents API
  slug: corbado-passkeyevents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corbado/openapi/corbado-passkeyevents-api-openapi.yml
- filename: corbado-passkeys-api-openapi.yml
  format: yaml
  label: Corbado Passkeys API
  slug: corbado-passkeys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corbado/openapi/corbado-passkeys-api-openapi.yml
- filename: corbado-sessions-api-openapi.yml
  format: yaml
  label: Corbado Sessions API
  slug: corbado-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corbado/openapi/corbado-sessions-api-openapi.yml
- filename: corbado-users-api-openapi.yml
  format: yaml
  label: Corbado Users API
  slug: corbado-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corbado/openapi/corbado-users-api-openapi.yml
- filename: corbado-connect-tokens-api-openapi.yml
  format: yaml
  label: Corbado Connect Tokens API
  slug: corbado-connect-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corbado/openapi/corbado-connect-tokens-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management system
    text: Our information security management system is ISO 27001:2022 certified and overseen by our CISO
    type: certification
  - framework: SOC2
    issuer: An independent auditor
    period: null
    report_access: nda
    scope: security, availability and confidentiality, including Corbado Observe
    text: The report is available under NDA.
    type: SOC 2 Type II audit
  trust_center:
    url: https://www.corbado.com/security
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Corbado
provenance_date: '2026-11-09'
provider_name: Corbado
provider_slug: corbado
slug: corbado-compliance
source_date: '2026-11-09'
source_filename: corbado-compliance.yml
source_heading: Compliance
source_page: https://www.corbado.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Corbado\naid: corbado\nurl: https://www.corbado.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/corbado-trust-center.yml\ntrust_center:\n  url: https://www.corbado.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: information security management system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our information security management system is ISO 27001:2022 certified and overseen by our CISO\n- framework: SOC2\n  type: SOC 2 Type II audit\n  scope: security, availability and confidentiality, including Corbado Observe\n  period: null\n\
  \  issuer: An independent auditor\n  report_access: nda\n  text: The report is available under NDA.\n"
source_yaml_url: https://artifacts.apis.io/corbado/compliance/corbado-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Corbado's own page on 2026-11-09.
synthetic: false
tags:
- Authentication
- Passkeys
- WebAuthn
- Passwordless
- CIAM
- Identity
---
