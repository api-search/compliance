---
api_specs:
- filename: signzy-authentication-api-openapi.yml
  format: yaml
  label: Signzy Authentication API
  slug: signzy-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signzy/openapi/signzy-authentication-api-openapi.yml
- filename: signzy-banking-api-openapi.yml
  format: yaml
  label: Signzy Banking API
  slug: signzy-banking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signzy/openapi/signzy-banking-api-openapi.yml
- filename: signzy-identity-india-api-openapi.yml
  format: yaml
  label: Signzy Identity (India) API
  slug: signzy-identity-india-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signzy/openapi/signzy-identity-india-api-openapi.yml
- filename: signzy-identity-us-api-openapi.yml
  format: yaml
  label: Signzy Identity (US) API
  slug: signzy-identity-us-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signzy/openapi/signzy-identity-us-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 Certified
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Compliant
    type: compliance
  trust_center:
    url: https://www.signzy.com/
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Signzy
provenance_date: '2026-11-10'
provider_name: Signzy
provider_slug: signzy
slug: signzy-compliance
source_date: '2026-11-10'
source_filename: signzy-compliance.yml
source_heading: Compliance
source_page: https://www.signzy.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Signzy\naid: signzy\nurl: https://www.signzy.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/signzy-trust-center.yml\ntrust_center:\n  url: https://www.signzy.com/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Certified\n- framework: SOC2\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Compliant\n"
source_yaml_url: https://artifacts.apis.io/signzy/compliance/signzy-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Signzy's own page on 2026-11-10.
synthetic: false
tags:
- Identity Verification
- KYC
- KYB
- AML
- Onboarding
- Compliance
- RegTech
---
