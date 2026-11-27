---
api_specs:
- filename: clevercarehealthplan-drug-formulary-api-openapi.yml
  format: yaml
  label: Clever Care Health Plan Drug Formulary API
  slug: clevercarehealthplan-drug-formulary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clevercarehealthplan/openapi/clevercarehealthplan-drug-formulary-api-openapi.yml
- filename: clevercarehealthplan-patient-access-api-openapi.yml
  format: yaml
  label: Clever Care Health Plan Patient Access API
  slug: clevercarehealthplan-patient-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clevercarehealthplan/openapi/clevercarehealthplan-patient-access-api-openapi.yml
- filename: clevercarehealthplan-provider-directory-api-openapi.yml
  format: yaml
  label: Clever Care Health Plan Provider Directory API
  slug: clevercarehealthplan-provider-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clevercarehealthplan/openapi/clevercarehealthplan-provider-directory-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA Compliant
    type: compliance badge
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CCPA Compliant
    type: compliance badge
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Medicare Compliant
    type: compliance badge (Medicare)
  trust_center:
    url: https://clevercarehealthplan.com/medicare-compliance/
frameworks:
- CCPA
- HIPAA
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Clever Care Health Plan
provenance_date: '2026-11-09'
provider_name: Clever Care Health Plan
provider_slug: clevercarehealthplan
slug: clevercarehealthplan-compliance
source_date: '2026-11-09'
source_filename: clevercarehealthplan-compliance.yml
source_heading: Compliance
source_page: https://clevercarehealthplan.com/medicare-compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Clever Care Health Plan\naid: clevercarehealthplan\nurl: https://clevercarehealthplan.com/medicare-compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://clevercarehealthplan.com/medicare-compliance/\nattestations:\n- framework: HIPAA\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA Compliant\n- framework: CCPA\n  type: compliance badge\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CCPA Compliant\n- framework: other\n  type: compliance badge (Medicare)\n  scope: null\n  period: null\n  issuer:\
  \ null\n  report_access: unstated\n  text: Medicare Compliant\n"
source_yaml_url: https://artifacts.apis.io/clevercarehealthplan/compliance/clevercarehealthplan-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Clever Care Health Plan's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Insurance
- Medicare Advantage
- FHIR
- Interoperability
- Patient Access
- Provider Directory
- Drug Formulary
- CMS-9115-F
---
