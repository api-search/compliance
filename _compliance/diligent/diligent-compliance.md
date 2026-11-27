---
api_specs:
- filename: diligent-cdd-api-openapi.yml
  format: yaml
  label: Diligent CDD API
  slug: diligent-cdd-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diligent/openapi/diligent-cdd-api-openapi.yml
- filename: diligent-company-api-openapi.yml
  format: yaml
  label: Diligent Company API
  slug: diligent-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diligent/openapi/diligent-company-api-openapi.yml
- filename: diligent-instant-screening-experimental-api-openapi.yml
  format: yaml
  label: Diligent Instant Screening (experimental) API
  slug: diligent-instant-screening-experimental-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diligent/openapi/diligent-instant-screening-experimental-api-openapi.yml
- filename: diligent-monitorings-api-openapi.yml
  format: yaml
  label: Diligent Monitorings API
  slug: diligent-monitorings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diligent/openapi/diligent-monitorings-api-openapi.yml
- filename: diligent-name-screening-api-openapi.yml
  format: yaml
  label: Diligent Name Screening API
  slug: diligent-name-screening-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diligent/openapi/diligent-name-screening-api-openapi.yml
- filename: diligent-webhooks-api-openapi.yml
  format: yaml
  label: Diligent Webhooks API
  slug: diligent-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diligent/openapi/diligent-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC2 - TYPE 2 Certified
    type: Type 2 certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001 Certified
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR Compliant
    type: compliant
  trust_center:
    url: https://www.godiligent.ai/security
frameworks:
- GDPR
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Diligent
provenance_date: '2026-11-09'
provider_name: Diligent
provider_slug: diligent
slug: diligent-compliance
source_date: '2026-11-09'
source_filename: diligent-compliance.yml
source_heading: Compliance
source_page: https://www.godiligent.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Diligent\naid: diligent\nurl: https://www.godiligent.ai/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.godiligent.ai/security\nattestations:\n- framework: SOC2\n  type: Type 2 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 - TYPE 2 Certified\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Certified\n- framework: GDPR\n  type: compliant\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR Compliant\n"
source_yaml_url: https://artifacts.apis.io/diligent/compliance/diligent-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Diligent's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Compliance
- RegTech
- KYC
- AML
- Financial Crime
- Due Diligence
- Screening
- Sanctions
- Monitoring
- Artificial Intelligence
- Fintech
- Webhook
---
