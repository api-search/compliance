---
api_specs:
- filename: koala-io-accounts-api-openapi.yml
  format: yaml
  label: Koala Accounts API
  slug: koala-io-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koala-io/openapi/koala-io-accounts-api-openapi.yml
- filename: koala-io-collection-api-openapi.yml
  format: yaml
  label: Koala Collection API
  slug: koala-io-collection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koala-io/openapi/koala-io-collection-api-openapi.yml
- filename: koala-io-deletion-api-openapi.yml
  format: yaml
  label: Koala Deletion API
  slug: koala-io-deletion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koala-io/openapi/koala-io-deletion-api-openapi.yml
- filename: koala-io-sdk-api-openapi.yml
  format: yaml
  label: Koala SDK API
  slug: koala-io-sdk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koala-io/openapi/koala-io-sdk-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II certified
    type: SOC 2 Type II certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Koala is compliant with the General Data Protection Regulation (GDPR) and California Consumer Privacy Act (CCPA).
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR & CCPA compliant
    type: compliance
  trust_center:
    url: https://getkoala.com/security
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Koala
provenance_date: '2026-11-09'
provider_name: Koala
provider_slug: koala-io
slug: koala-io-compliance
source_date: '2026-11-09'
source_filename: koala-io-compliance.yml
source_heading: Compliance
source_page: https://getkoala.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Koala\naid: koala-io\nurl: https://getkoala.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/koala-io-trust-center.yml\ntrust_center:\n  url: https://getkoala.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II certified\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Koala is compliant with the General Data Protection Regulation (GDPR) and California Consumer Privacy Act\n    (CCPA).\n\
  - framework: CCPA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR & CCPA compliant\n"
source_yaml_url: https://artifacts.apis.io/koala-io/compliance/koala-io-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Koala's own page on 2026-11-09.
synthetic: false
tags:
- Buyer Intent
- Visitor Identification
- De-anonymization
- Data Enrichment
- Go-To-Market
- Sales Intelligence
- B2B
- A2A
---
