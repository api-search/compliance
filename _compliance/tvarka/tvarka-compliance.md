---
api_specs:
- filename: auth.json
  format: json
  label: Tvarka ATK API Tvarka ATK API
  slug: tvarka-atk-api-tvarka-atk-api-api
  spec_type: Postman
  url: https://atk.tvarka.pro/postman/auth.json
- filename: auth.json
  format: json
  label: Tvarka ATK API Tvarka ATK QES Signing API (paid Tier Addendum) API
  slug: tvarka-atk-api-tvarka-atk-qes-signing-api-paid-tier-addendum-api
  spec_type: Postman
  url: https://atk.tvarka.pro/postman/auth.json
- filename: tvarka-sign-api-openapi.yml
  format: yaml
  label: Tvarka Sign API
  slug: tvarka-sign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-sign-api-openapi.yml
- filename: tvarka-auth-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Auth API
  slug: tvarka-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-auth-api-openapi.yml
- filename: tvarka-batches-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Batches API
  slug: tvarka-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-batches-api-openapi.yml
- filename: tvarka-erasure-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Erasure API
  slug: tvarka-erasure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-erasure-api-openapi.yml
- filename: tvarka-files-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Files API
  slug: tvarka-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-files-api-openapi.yml
- filename: tvarka-ltv-api-openapi.yml
  format: yaml
  label: Tvarka ATK API LTV API
  slug: tvarka-ltv-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-ltv-api-openapi.yml
- filename: tvarka-pairing-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Pairing API
  slug: tvarka-pairing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-pairing-api-openapi.yml
- filename: tvarka-signings-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Signings API
  slug: tvarka-signings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-signings-api-openapi.yml
- filename: tvarka-tvarka-atk-api-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Tvarka ATK API
  slug: tvarka-tvarka-atk-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-tvarka-atk-api-api-openapi.yml
- filename: tvarka-tvarka-sign-api-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Tvarka Sign API
  slug: tvarka-tvarka-sign-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-tvarka-sign-api-api-openapi.yml
- filename: tvarka-validation-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Validation API
  slug: tvarka-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-validation-api-openapi.yml
- filename: tvarka-well-known-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Well Known API
  slug: tvarka-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-well-known-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    text: Saugoma ES BDAR 27001 · 9001 · 31000 DSS CCPA
    type: badge
  - framework: ISO9001
    issuer: null
    period: null
    report_access: unstated
    scope: unstated
    text: Saugoma ES BDAR 27001 · 9001 · 31000 DSS CCPA
    type: badge
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data processing
    text: Asmens duomenys tvarkomi pagal BDAR.
    type: statement
  trust_center:
    url: https://tvarka.pro/saugumas/
frameworks:
- GDPR
- ISO27001
- ISO9001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Tvarka ATK API
provenance_date: '2026-11-10'
provider_name: Tvarka ATK API
provider_slug: tvarka
slug: tvarka-compliance
source_date: '2026-11-10'
source_filename: tvarka-compliance.yml
source_heading: Compliance
source_page: https://tvarka.pro/saugumas/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Tvarka ATK API\naid: tvarka\nurl: https://tvarka.pro/saugumas/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://tvarka.pro/saugumas/\nattestations:\n- framework: ISO27001\n  type: badge\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Saugoma ES BDAR 27001 · 9001 · 31000 DSS CCPA\n- framework: ISO9001\n  type: badge\n  scope: unstated\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Saugoma ES BDAR 27001 · 9001 · 31000 DSS CCPA\n- framework: GDPR\n  type: statement\n  scope: personal data processing\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: Asmens duomenys tvarkomi pagal BDAR.\n"
source_yaml_url: https://artifacts.apis.io/tvarka/compliance/tvarka-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Tvarka ATK API's own page on 2026-11-10.
synthetic: false
tags:
- Authentication
- Digital Signature
- eIDAS
- QES
- Lithuania
- OpenAPI
- eID
- Smart-ID
- Mobile-ID
- NFC
- Timestamping
- LTV
- Webhook
- Identity
- Trust Services
- GDPR
---
