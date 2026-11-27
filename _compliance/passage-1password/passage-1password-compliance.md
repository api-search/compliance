---
api_specs:
- filename: passage-1password-devices-api-openapi.yml
  format: yaml
  label: Passage by 1Password Devices API
  slug: passage-1password-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/passage-1password/openapi/passage-1password-devices-api-openapi.yml
- filename: passage-1password-magic-links-api-openapi.yml
  format: yaml
  label: Passage by 1Password Magic Links API
  slug: passage-1password-magic-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/passage-1password/openapi/passage-1password-magic-links-api-openapi.yml
- filename: passage-1password-tokens-api-openapi.yml
  format: yaml
  label: Passage by 1Password Tokens API
  slug: passage-1password-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/passage-1password/openapi/passage-1password-tokens-api-openapi.yml
- filename: passage-1password-users-api-openapi.yml
  format: yaml
  label: Passage by 1Password Users API
  slug: passage-1password-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/passage-1password/openapi/passage-1password-users-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 1Password is SOC 2 type 2 certified
    type: SOC 2 Type 2
  trust_center:
    url: https://1password.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Passage by 1Password
provenance_date: '2026-11-10'
provider_name: Passage by 1Password
provider_slug: passage-1password
slug: passage-1password-compliance
source_date: '2026-11-10'
source_filename: passage-1password-compliance.yml
source_heading: Compliance
source_page: https://1password.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Passage by 1Password\naid: passage-1password\nurl: https://1password.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/passage-1password-trust-center.yml\ntrust_center:\n  url: https://1password.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 1Password is SOC 2 type 2 certified\n"
source_yaml_url: https://artifacts.apis.io/passage-1password/compliance/passage-1password-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Passage by 1Password's own page on 2026-11-10.
synthetic: false
tags:
- Authentication
- Passkeys
- WebAuthn
- Passwordless
- Identity
- Magic Links
---
