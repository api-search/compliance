---
api_specs:
- filename: keyo-authentication-api-openapi.yml
  format: yaml
  label: Keyo Authentication API
  slug: keyo-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keyo/openapi/keyo-authentication-api-openapi.yml
- filename: keyo-identities-api-openapi.yml
  format: yaml
  label: Keyo Identities API
  slug: keyo-identities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keyo/openapi/keyo-identities-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We are proud to have earned our SOCII accreditation
    type: accreditation
  trust_center:
    url: https://keyo.com/security
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Keyo
provenance_date: '2026-11-09'
provider_name: Keyo
provider_slug: keyo
slug: keyo-compliance
source_date: '2026-11-09'
source_filename: keyo-compliance.yml
source_heading: Compliance
source_page: https://keyo.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Keyo\naid: keyo\nurl: https://keyo.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://keyo.com/security\nattestations:\n- framework: SOC2\n  type: accreditation\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are proud to have earned our SOCII accreditation\n"
source_yaml_url: https://artifacts.apis.io/keyo/compliance/keyo-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Keyo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biometrics
- Identity
- Authentication
- Palm Recognition
- Access Control
- Payments
- Identity Verification
---
