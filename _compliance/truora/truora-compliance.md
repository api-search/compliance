---
api_specs:
- filename: truora-account-api-openapi.yml
  format: yaml
  label: Truora Account API
  slug: truora-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truora/openapi/truora-account-api-openapi.yml
- filename: truora-checks-api-openapi.yml
  format: yaml
  label: Truora Checks API
  slug: truora-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truora/openapi/truora-checks-api-openapi.yml
- filename: truora-continuous-monitoring-api-openapi.yml
  format: yaml
  label: Truora Continuous Monitoring API
  slug: truora-continuous-monitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truora/openapi/truora-continuous-monitoring-api-openapi.yml
- filename: truora-digital-identity-api-openapi.yml
  format: yaml
  label: Truora Digital Identity API
  slug: truora-digital-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truora/openapi/truora-digital-identity-api-openapi.yml
- filename: truora-validators-api-openapi.yml
  format: yaml
  label: Truora Validators API
  slug: truora-validators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truora/openapi/truora-validators-api-openapi.yml
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022
    type: certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27018
    type: certification
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27017
    type: certification
  - framework: ISO27001
    issuer: third-party agency
    period: null
    report_access: unstated
    scope: null
    source: https://www.truora.com/en/iso-27001-certification
    text: Truora has achieved ISO 27001 certification, the highest standard for preserving the confidentiality, integrity and security of information of our customers and suppliers.
    type: certification
  trust_center:
    url: https://app.vanta.com/truora.com/trust/dno2uof19v4enmupm1kenj
frameworks:
- ISO27001
- ISO27017
- ISO27018
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Truora
provenance_date: '2026-11-10'
provider_name: Truora
provider_slug: truora
slug: truora-compliance
source_date: '2026-11-10'
source_filename: truora-compliance.yml
source_heading: Compliance
source_page: https://app.vanta.com/truora.com/trust/dno2uof19v4enmupm1kenj
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Truora\naid: truora\nurl: https://app.vanta.com/truora.com/trust/dno2uof19v4enmupm1kenj\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/truora-trust-center.yml\n  sources:\n  - https://app.vanta.com/truora.com/trust/dno2uof19v4enmupm1kenj\n  - https://www.truora.com/en/iso-27001-certification\ntrust_center:\n  url: https://app.vanta.com/truora.com/trust/dno2uof19v4enmupm1kenj\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022\n- framework: ISO27018\n  type: certification\n  scope: null\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: ISO 27018\n- framework: ISO27017\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27017\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: third-party agency\n  report_access: unstated\n  text: Truora has achieved ISO 27001 certification, the highest standard for preserving the confidentiality, integrity\n    and security of information of our customers and suppliers.\n  source: https://www.truora.com/en/iso-27001-certification\n"
source_yaml_url: https://artifacts.apis.io/truora/compliance/truora-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Truora's own page on 2026-11-10.
synthetic: false
tags:
- Identity Verification
- KYC
- Background Checks
- Fraud Prevention
- Latin America
- WhatsApp
---
