---
api_specs:
- filename: dataedo-public-api-openapi.yml
  format: yaml
  label: Dataedo Public API
  slug: dataedo-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataedo/openapi/dataedo-public-api-openapi.yml
- filename: dataedo-public-api-openapi.yml
  format: yaml
  label: Dataedo Public API
  slug: dataedo-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataedo/openapi/dataedo-public-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management system (ISMS)
    text: ISO 27001 Certified
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data protection
    text: Dataedo is GDPR-compliant
    type: compliance
  trust_center:
    url: https://dataedo.com/security
frameworks:
- GDPR
- ISO27001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Dataedo
provenance_date: '2026-11-09'
provider_name: Dataedo
provider_slug: dataedo
slug: dataedo-compliance
source_date: '2026-11-09'
source_filename: dataedo-compliance.yml
source_heading: Compliance
source_page: https://dataedo.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Dataedo\naid: dataedo\nurl: https://dataedo.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://dataedo.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: information security management system (ISMS)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 Certified\n- framework: GDPR\n  type: compliance\n  scope: personal data protection\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Dataedo is GDPR-compliant\n"
source_yaml_url: https://artifacts.apis.io/dataedo/compliance/dataedo-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Dataedo's own page on 2026-11-09.
synthetic: false
tags:
- Data Governance
- Data Quality
- Metadata Management
- Data Catalog
- Business Intelligence
---
